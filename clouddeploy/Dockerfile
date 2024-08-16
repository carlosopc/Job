# Use the official Python 3.9 image as the base
FROM python:3.9

# Set the working directory inside the container
WORKDIR /app

# Copy the requirements file to the working directory
COPY requirements.txt .

# Install the Python dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Copy the application code to the working directory
COPY . .

# Define the entrypoint for the job
ENTRYPOINT ["python", "main.py"]
