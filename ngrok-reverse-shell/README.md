# Ngrok-reverse-shell 
Used for getting a reverse shell.

**Note: Only for educational purposes.**

[Medium post](https://thetorjancaptain.medium.com/reverse-shell-over-ngrok-using-ncat-windows-linux-setup-guide-6ee35ae05e1c) to explain detailed steps.

## In Linux target, we use a Bash script:reverse.sh
1. Save [reverse.sh](https://github.com/TheTorjanCaptain/Vulnerable-POC-Syntax/blob/7e29098772e2ec1deea63038fa0f189f4aa5812e/ngrok-reverse-shell/reverse.sh)
2. Make it executable: ```chmod +x reverse.sh```
3. Run it: ```./reverse.sh```


## In Windows target we got two options: Batch or Powershell
### Batch: [reverse.bat](https://github.com/TheTorjanCaptain/Vulnerable-POC-Syntax/blob/7e29098772e2ec1deea63038fa0f189f4aa5812e/ngrok-reverse-shell/reverse.bat) file for ncat
Just double click to run.

### Powershell Script: [reverse.ps1](https://github.com/TheTorjanCaptain/Vulnerable-POC-Syntax/blob/7e29098772e2ec1deea63038fa0f189f4aa5812e/ngrok-reverse-shell/reverse.ps1) file
To run: ```powershell -ExecutionPolicy Bypass -File reverse.ps1```
