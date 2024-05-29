# Use the official Python image as the base image
FROM python:3.9-slim

# Set the working directory inside the container
WORKDIR /usr/src/app

# Set the environment variable with your custom message
ENV CUSTOM_MESSAGE "tum mujhe bhul jao yh ho ni skta mai tumhe bhul jau yh mai hone nhi duga!"

# Expose port 80 to allow outside access to the HTTP server
EXPOSE 80

# Command to run the HTTP server when the container starts
CMD ["sh", "-c", "echo $CUSTOM_MESSAGE | python -m http.server 80"]

