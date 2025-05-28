# Contributing to Skip Tracing POC

Thank you for considering contributing to our Skip Tracing POC! This project aims to create a professional demonstration platform for skip tracing capabilities.

## 🤝 Code of Conduct

- Use welcoming and inclusive language
- Be respectful of differing viewpoints and experiences
- Focus on what is best for the community and project
- Show empathy towards other community members

## 🛠️ Development Setup

### Prerequisites
- **Node.js 18+** and npm
- **Git** for version control
- **Claude Desktop** with MCP configuration
- **Supabase account** for database access
- **Apify account** for skip tracing APIs

### Initial Setup

1. **Fork and clone the repository**
   ```bash
   git clone https://github.com/GautaVaid/Skip_Tracing.git
   cd Skip_Tracing
   ```

2. **Set up development branches**
   ```bash
   git checkout develop
   git checkout -b feature/your-feature-name
   ```

3. **Configure environment**
   ```bash
   cp .env.example .env
   # Edit .env with your API keys and configuration
   ```

## 🔄 Pull Request Process

### Development Standards
- **File Size Limit**: Maximum 500 lines per file
- **Modular Design**: Single responsibility per module
- **Documentation**: All functions and classes must be documented
- **Testing**: Add tests for new functionality

### Commit Standards
We use [Conventional Commits](https://www.conventionalcommits.org/):

```bash
feat: add confidence scoring algorithm for search results
fix: resolve mobile responsive layout on results page
docs: update API documentation for export endpoints
test: add end-to-end tests for search functionality
```

### Code Quality Checks
```bash
npm run lint          # ESLint validation  
npm run format        # Prettier formatting
npm run test          # Full test suite
npm run test:coverage # Ensure 80%+ coverage
```

## 📏 Coding Standards

### File Organization
- **File Size Limit**: Maximum 500 lines per file
- **Modular Architecture**: Single responsibility per module
- **ES6+ Features**: Use modern JavaScript features
- **Error Handling**: Comprehensive try/catch blocks

### Testing Requirements
- **Minimum Coverage**: 80% overall code coverage
- **Critical Paths**: 100% coverage for core functionality
- **New Features**: Must include comprehensive tests
- **Bug Fixes**: Must include regression tests

## 🐛 Issue Guidelines

### Bug Reports
Include:
- Clear title and description
- Environment details (OS, browser, Node.js version)
- Steps to reproduce
- Expected vs actual behavior
- Screenshots and console logs

### Feature Requests
Include:
- Problem statement
- Proposed solution
- User stories and acceptance criteria

## 📚 Documentation

- **Function Comments**: JSDoc format for all functions
- **API Documentation**: OpenAPI/Swagger documentation
- **README Updates**: Keep documentation current with changes
- **Examples**: Include code examples and usage patterns

## 🚀 Development Workflow

1. **Start Fresh**: Pull latest from develop branch
2. **Create Branch**: Feature branch for your work
3. **Make Changes**: Follow coding standards
4. **Test Locally**: Run full test suite
5. **Create PR**: Use provided PR template
6. **Code Review**: At least one maintainer approval required

## 🆘 Getting Help

- **GitHub Issues**: For bug reports and feature requests
- **GitHub Discussions**: For questions and general discussion
- **Documentation**: Check `/docs` directory for detailed guides

---

**Questions?** Don't hesitate to ask! We're here to help and want to make contributing as smooth as possible.