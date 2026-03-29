# Use a lightweight Python image
FROM python:3.9-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the script from your local machine to the container
COPY . .

RUN pip install --no-cache-dir -r requirements.txt || true

# Command to run the script
CMD ["python","-u", "script.py"]