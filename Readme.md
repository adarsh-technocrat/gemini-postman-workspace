# Gemini API Postman Workspace

<div align="center">
  <img src="https://s.yimg.com/fz/api/res/1.2/IxLAfFMg_CgLgqu8l9eEzw--~C/YXBwaWQ9c3JjaGRkO2ZpPWZpdDtoPTI0MDtxPTgwO3c9MzMy/https://s.yimg.com/zb/imgv1/2404ede1-f764-3aa5-86d5-3bacae8af77e/t_500x300" alt="Gemini Logo" width="200"/>

[![API Version](https://img.shields.io/badge/API%20Version-v1-blue)](https://ai.google.dev/gemini-api/docs)
[![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)](https://www.postman.com/)
[![License](https://img.shields.io/badge/License-Apache%202.0-green.svg)](LICENSE)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](CONTRIBUTING.md)
[![GitHub stars](https://img.shields.io/github/stars/google-deepmind/gemini-postman-workspace?style=social)](https://github.com/google-deepmind/gemini-postman-workspace/stargazers)

</div>

This repository contains comprehensive Postman collections, environments, and documentation for Google's Gemini APIs, making it easier to explore and integrate with Gemini's powerful AI capabilities.

## 🚀 Quick Start

1. Clone this repository
2. Import the collections into Postman
3. Set up your API key in the environment variables
4. Start making requests to the Gemini API

## 📁 Repository Structure

```
gemini-postman-workspace/
├── collections/
│   ├── gemini-text-generation.json        # Text generation API requests
│   ├── gemini-chat.json                   # Chat API requests
│   ├── gemini-image-generation.json       # Image generation API requests
│   ├── gemini-code-generation.json        # Code generation API requests
│   └── gemini-complete-collection.json    # Combined collection for importing
├── environments/
│   ├── gemini-development.json            # Development environment variables
│   └── gemini-production.json             # Production environment variables
├── documentation/
│   ├── getting-started.md                 # Quick start guide
│   ├── authentication.md                  # Authentication instructions
│   ├── text-generation-guide.md           # Text generation tutorial
│   ├── chat-guide.md                      # Chat implementation tutorial
│   ├── image-generation-guide.md          # Image generation tutorial
│   └── code-generation-guide.md           # Code generation tutorial
├── scripts/
│   ├── update-collection.js               # Script to update collections from API docs
│   └── tests/                             # Test scripts for validation
├── .github/
│   └── workflows/
│       └── update-postman.yml             # GitHub Action for automatic updates
└── README.md                              # Main documentation
```

## 🧩 Main Components

### Collections

- **Text Generation**: Requests for generating text with various parameters
- **Chat**: Interactive conversation API endpoints with streaming support
- **Image Generation**: Endpoints for creating and modifying images
- **Code Generation**: Specialized endpoints for generating and manipulating code

### Environments

- **Development**: Variables optimized for testing and development
- **Production**: Configured for production use with rate limiting consideration

### Documentation

Comprehensive guides to help you get started and make the most of the Gemini API capabilities.

## 🔑 Authentication

To use the Gemini API, you'll need to:

1. Get an API key from [Google AI Studio](https://ai.google.dev/)
2. Add your API key to the Postman environment variables
3. Select the appropriate environment before making requests

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📜 License

This project is licensed under the Apache 2.0 License - see the LICENSE file for details.

## 🔗 Useful Links

- [Gemini API Documentation](https://ai.google.dev/gemini-api/docs)
- [Google AI Studio](https://ai.google.dev/)
- [Postman Learning Center](https://learning.postman.com/)
- [DeepMind Gemini Research](https://deepmind.google/technologies/gemini/)

---

<div align="center">
  <p>Made with ❤️ for the AI developer community</p>
</div>
