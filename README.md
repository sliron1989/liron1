# liron1

bla bla

## Quick Start

### Prerequisites
- Go 1.26+
- Docker (optional)

### Run Locally

```bash
go run main.go
```

The service starts on port 8080.

### Endpoints

| Method | Path | Description |
|--------|------|-------------|
| GET | / | Welcome message |
| GET | /health | Health check |

### Using Docker

```bash
docker build -t liron1 .
docker run -p 8080:8080 liron1
```

### Test

```bash
curl http://localhost:8080/
curl http://localhost:8080/health
```

## CI/CD

This repository includes a GitHub Actions workflow that runs golangci-lint on pull requests.

## License

MIT License - see [LICENSE](LICENSE) for details.
