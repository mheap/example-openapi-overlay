# Example OpenAPI Overlay

This repo shows how to work with [OpenAPI Overlays](https://github.com/OAI/Overlay-Specification) using [openapi-overlays-js](https://github.com/lornajane/openapi-overlays-js)

It's a small example that adds a description to an existing endpoint.

## Usage

```bash
git clone https://github.com/mheap/example-openapi-overlay.git
cd example-openapi-overlay
git clone https://github.com/lornajane/openapi-overlays-js.git
cd openapi-overlays-js
npm install
node index.js --openapi ../openapi.yaml --overlay ../overlay.yaml
```

The combined OpenAPI spec will be printed to `stdout`
