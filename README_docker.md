# Hello world MCP Tool Containerization

## Create Image

```bash
docker build -f dockerfile.hello_world -t hello-world-mcp .
```

## List docker images
```bash
docker images
```

## Run Docker Image
```bash
docker run --rm -it --name hello-world-mcp -p 6277:6277 -p 6274:6274 -p 3000:3000 hello-world-mcp 
```

# Weather MCP Tool Containerization

## Create Image

```bash
docker build -f dockerfile.weather_tool -t weather-mcp-tool .
```

## List docker images
```bash
docker images
```

## Run Docker Image
```bash
docker run --rm -it --name weather-mcp-tool -p 6277:6277 -p 6274:6274 -p 3000:3000 weather-mcp-tool 
```

