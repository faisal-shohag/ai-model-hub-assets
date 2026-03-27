<img src="https://ai-model-hub.netlify.app/logo.png">


# Generating Fake Data
Generate a JSON array of AI tools/products with the following structure:
```
- id: unique integer
- title: name of the AI tool
- description: 2 short lines separated by a newline character (\n)
- price: number (use 0 for free tools, otherwise monthly price in USD)
- image: a valid public URL to the tool's logo
- status: one of ["popular", "favourite", "mostwanted"]
```