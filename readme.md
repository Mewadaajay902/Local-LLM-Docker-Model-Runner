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

   ### Some ScreenShot From Practical
Running Model on Localhost
<img width="1456" alt="Screenshot 2025-04-14 at 11 30 09 PM" src="https://github.com/user-attachments/assets/4359c56c-b125-445e-9a9b-355070b6def8" />

Running model on Local CLI

<img width="1250" alt="Screenshot 2025-04-14 at 11 32 56 PM" src="https://github.com/user-attachments/assets/e61fccae-dd7d-49bf-b880-33513cbb0968" />
<img width="1456" alt="Screenshot 2025-04-14 at 11 31 52 PM" src="https://github.com/user-attachments/assets/668dac44-38b0-494d-a340-9bf40303954c" />



