# Easy-bypass
Easy 

## Installation

Install curl:
```bash
sudo apt install curl -y
```

Add the Brave key:
```bash
sudo curl -fsSLo /usr/share/keyrings/brave-browser-archive-keyring.gpg https://brave-browser-apt-release.s3.brave.com/brave-browser-archive-keyring.gpg
```

Add the repository:
```bash
echo "deb [signed-by=/usr/share/keyrings/brave-browser-archive-keyring.gpg] https://brave-browser-apt-release.s3.brave.com/ stable main" | sudo tee /etc/apt/sources.list.d/brave-browser-release.list
```

Install it:
```bash
sudo apt update && sudo apt install brave-browser -y
```
