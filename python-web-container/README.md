# Python Web Container

This project is a small web application built with Flask that runs in a Docker container. It listens on all network interfaces and serves a simple HTML page.

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd python-web-container
   ```

2. **Build the Docker image:**
   ```bash
   docker build -t python-web-container .
   ```

3. **Run the application using Docker Compose:**
   ```bash
   docker-compose up
   ```

4. **Access the application:**
   Open your web browser and go to `http://localhost:5000` to view the application.

## Usage

The application serves a simple HTML page located in the `src/templates` directory. You can modify the `index.html` file to change the content displayed.

## Testing

To run the unit tests, use the following command:
```bash
pytest tests/test_app.py
```

## License

This project is licensed under the MIT License.