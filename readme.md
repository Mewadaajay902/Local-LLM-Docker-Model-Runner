# Docker Model Runner

This project demonstrates how to use Docker to pull and run AI models locally.  
**Note:** This project uses the [hello-genai](https://github.com/docker/hello-genai) repository for practical purposes. I have not built or worked on the `hello-genai` project.

## Quick Start

### On Terminal

1. Pull the AI model:
   ```bash
   docker model pull ai/smollm2
   ```

2. Run the AI model:
   ```bash
   docker model run ai/smollm2 "Hello what is kubernetes ?"
   docker model run ai/smollm2
   ```

### On Web at localhost

1. Clone the repository:
   ```bash
   git clone https://github.com/docker/hello-genai.git
   cd hello-genai
   ```

2. Make changes in `.env` to point to `ai/smollm2` instead of the default present.

3. Run the script:
   ```bash
   ./run.sh
   ```

4. Access it on: [http://localhost:8081](http://localhost:8081)

