### REMOTE INSTALL
### RECOMMENDED OS: ubuntu-24.04.2-live-server-amd64.iso
### PASTE THESE LINES IN THE TERMINAL
### Access in your browser http://<ip>:8080

sudo apt update;

sudo apt install -y unzip;

sudo curl -L -o "nodeapp.zip" "https://github.com/GitNothing/translatellm/raw/refs/heads/main/nodeapp.zip";

sudo unzip nodeapp.zip;

cd nodeapp;

sudo chmod +x install.sh;

sudo ./install.sh;
