# langflow-docker-ollama
Langflow Docker Image

```docker build -f DockerFile . -t nightranger/langflow:latest```

```docker run -d --restart always --add-host=host.docker.internal:host-gateway -p 7860:7860 -it --name langflow nightranger/langflow:latest```

Set Ollama Base url to:

```http://host.docker.internal:11434```
