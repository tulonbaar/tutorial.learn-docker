# Use the official Golang image
FROM golang:1.25.3-alpine
ENV PORT=8991

# Set the working directory
# inside the container
WORKDIR /app

# Copy the current directory
# contents into the container
COPY /src/goserver/* .

RUN go build

# command when the container runs
CMD ["./goserver"]