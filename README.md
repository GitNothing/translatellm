# TRANSLATELLM REMOTE INSTALL
#### RECOMMENDED OS: ubuntu-24.04.2-live-server-amd64.iso
#### RECOMMENDED AZURE SIZE FOR SMALL SCALE: D2s_v3 
#### ACCESS FROM YOUR BROWSER AT: http://your_server_ip:8080
##### What is installed? unzip -> docker -> docker compose -> ollama with gemma3 -> open webui -> translatellm app
#### Pull gemma3 model to verify installation before using translatellm
## PASTE THESE LINES IN THE TERMINAL

```bash
sudo apt update;

sudo apt install -y unzip;

sudo curl -L -o "nodeapp.zip" "https://github.com/GitNothing/translatellm/raw/refs/heads/main/nodeapp.zip";

sudo unzip nodeapp.zip;

cd nodeapp;

sudo chmod +x install.sh;

sudo ./install.sh;
```
