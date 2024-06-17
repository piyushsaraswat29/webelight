# Use an official Go runtime as a parent image
FROM golang:1.18

# Set the working directory inside the container
WORKDIR /app

# Copy the local package files to the container's workspace
COPY . .

# Build the Go application
RUN go build -o myapp .

# Run the Go application
CMD ["./myapp"]

