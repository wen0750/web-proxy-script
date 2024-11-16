# web-proxy-script

A minimalist, private web proxy script written in PHP code.

## Running the Project Locally

To run the project locally, you need to have PHP installed on your machine. The required PHP version is 7.4 or higher. Additionally, you need to have the cURL extension enabled.

1. Clone the repository:
   ```sh
   git clone https://github.com/heiswayi/web-proxy-script.git
   cd web-proxy-script
   ```

2. Start the PHP built-in web server:
   ```sh
   php -S localhost:8000
   ```

3. Open your web browser and navigate to `http://localhost:8000/proxy.php`.

## Using Docker

To build and run the Docker container, follow these steps:

1. Build the Docker image:
   ```sh
   docker build -t web-proxy-script .
   ```

2. Run the Docker container:
   ```sh
   docker run -p 80:80 web-proxy-script
   ```

3. Open your web browser and navigate to `http://localhost/proxy.php`.

## License

[MIT](LICENSE)
