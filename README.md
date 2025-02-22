# Sparkchain BOT
Sparkchain BOT

- Register Here : [Sparkchain](https://sparkchain.ai/register/?r=46814955)
- Use Code : 46814955

## Features

  - Auto Get Account Information
  - Auto Run With [Monosans](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/all.txt) Proxy - Choose 1
  - Auto Run With Private Proxy - Choose 2
  - Auto Run Without Proxy - Choose 3
  - Auto Complete Available Tasks
  - Auto Connect and Reconnect Websocket
  - Supports Multi Nodes For Each Account
  - Multi Accounts With Threads

Note: 
1. Only running 1 node if run without proxy.
2. If GET Device ID Failed. Try Login Your Sparkchain Extension First

## Requiremnets

- Make sure you have Python3.9 or higher installed and pip.

## Instalation

1. **Clone The Repositories:**
   ```bash
   git clone https://github.com/bilalrai12/Spark.git
   ```
   ```bash
   cd Spark
   ```

2. **Install Requirements:**
   ```bash
   pip install -r requirements.txt
   ```

## Configuration
  ```bash
  nano accounts.json
```
- **accounts.json:** You will find the file `accounts.json` inside the project directory. Make sure `accounts.json` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    [
        {
            "Email": "your email address 1",
            "Password": "your password 1"
        },
        {
            "Email": "your email address 2",
            "Password": "your password 2"
        }
    ]
  ```

- **proxy.txt:** You will find the file `proxy.txt` inside the project directory. Make sure `proxy.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    nano proxy.txt
  ```

## Run

```bash
python bot.py 
```
