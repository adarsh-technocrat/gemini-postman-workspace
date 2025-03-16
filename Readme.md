# Gemini API Postman Workspace

This repository contains Postman collections, environments, and documentation for Google's Gemini APIs.

## Repository Structure

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

## Main Components

1. **Collections**: Postman API request collections organized by Gemini feature
2. **Environments**: Pre-configured environment variables for different deployment scenarios
3. **Documentation**: Guides and tutorials for using the Gemini APIs
4. **Scripts**: Utility scripts for maintenance and updates
5. **GitHub Actions**: Automation for keeping collections up to date