# Listarr

A modern web application for managing and organizing lists, built with a frontend and backend architecture.

## 🚀 Features

- Frontend built with Bun and modern web technologies
- Backend API service
- Docker containerization
- Modular architecture with submodules

## 📋 Prerequisites

- Docker and Docker Compose
- Git (for submodule management)
- Bun (for frontend development)

## 🛠️ Installation

1. Clone the repository with submodules:
```bash
git clone --recursive https://github.com/unfaiyted/listarr.git
cd listarr
```

2. Initialize and update submodules:
```bash
git submodule update --init --recursive
```

## 🏗️ Development Setup

### Frontend
```bash
cd listarr-frontend
bun install
bun run dev
```

### Backend
```bash
cd listarr-backend
# Add backend setup instructions here
```

## 🐳 Docker Deployment

Build and run the entire stack:
```bash
docker-compose up --build
```

Individual services can be built and run separately:
```bash
# Frontend only
docker-compose up frontend

# Backend only
docker-compose up backend
```

## 🏗️ Project Structure

```
listarr/
├── docker-compose.yml
├── frontend/    # Frontend submodule
└── backend/     # Backend submodule
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with Bun
- Docker containerization
- All contributors and maintainers

