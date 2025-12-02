FROM python:3.12.0-slim-bookworm

# Set working directory
WORKDIR /app

# Copy and install dependencies
COPY requirements.txt /app/
RUN pip3 install -r requirements.txt

# Copy application files
COPY . /app/

# Create a non-root user with UID 1000
RUN useradd -u 1000 -m myuser

# Change ownership of /app to the non-root user
RUN chown -R 1000:1000 /app

# Make entrypoint executable
RUN chmod +x /app/entrypoint.sh

# Switch to non-root user by numeric UID
USER 1000

# Expose the application port
EXPOSE 8000

# Set entrypoint and default command
ENTRYPOINT ["/bin/bash", "/app/entrypoint.sh"]
CMD ["gunicorn", "--bind", ":8000", "--workers", "3", "djangoproj.wsgi"]