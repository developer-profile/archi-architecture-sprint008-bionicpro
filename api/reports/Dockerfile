# Build stage
FROM golang:1.24.6-alpine

WORKDIR /build
# Expose port
EXPOSE 8000

COPY . .

# Start nginx
CMD ["go", "run", "main.go"]