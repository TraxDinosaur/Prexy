# Prexy API

Prexy API is a API application that provides access to over 20k HTTP, HTTPS, SOCKS4, and SOCKS5 proxies sourced from external providers. This API is useful for various web scraping, security, and anonymization tasks.

## Features

- Fetches over 20k proxies from external sources.
- Provides endpoints for HTTP, HTTPS, SOCKS4, SOCKS5, and all proxies.
- Requests are handled asynchronously for optimal performance.

## Usage

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/TraxDinosaur/Prexy.git
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### Running the API

Run the following command to start the API server:

```bash
uvicorn main:app --host 0.0.0.0 --port 8080
```

### Endpoints

- `/http`: Get HTTP proxies.
- `/socks4`: Get SOCKS4 proxies.
- `/socks5`: Get SOCKS5 proxies.
- `/all`: Get all proxies.

### Example

```bash
curl http://localhost:8080/http
```

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

## License

This project is licensed under the [MIT License](LICENSE).
