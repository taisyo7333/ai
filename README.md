# AI

## ollama
https://github.com/ollama/ollama

### How to install ollama

```sh
brew install ollama
```

### How to use ollama

```sh
ollama serve
```

```sh
ollama run llama3.1 
```

## How to use open-webui
https://github.com/open-webui/open-webui
https://docs.openwebui.com/getting-started/quick-start

```sh
podman run -d -p 3000:8080 -v open-webui:/app/backend/data --name open-webui ghcr.io/open-webui/open-webui:main
```
