# Use the official Python image as the base image
FROM python:3.8
COPY . /app
# Set the working directory in the container
WORKDIR /app

# Copy the dependencies file to the working directory
COPY requirements.txt .

# Install Flask and other dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Copy the rest of the application code to the working directory


# Expose the port the app runs on
EXPOSE 5000

# Command to run the application
CMD ["python", "app.py"]
