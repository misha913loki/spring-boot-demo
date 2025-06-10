# Spring Boot Docker Hello World Example

This project is a simple Spring Boot application packaged with Docker that outputs "hello docker".

## Technologies Used

*   Java
*   Spring Boot
*   Docker

## Setup and Usage

To build and run this project using Docker:

1.  **Build the Docker image:**
    ```bash
    docker build -t spring-boot-docker-hello -f Dockerfile-publish .
    ```

2.  **Run the Docker container:**
    ```bash
    docker run -p 8080:8080 spring-boot-docker-hello
    ```

3.  **Access the application:**
    Open your web browser and go to [http://localhost:8080](http://localhost:8080). You should see the "hello docker" message.

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

## License

This project is unlicensed.
