# nexus-labs-node-setup

## What is nexus labs ? 
Nexus is building a supercomputer that will enable the Verifiable Internet, revolutionizing online trust, security, and transparency.

Nexus labs raised $27.2 Million funding.

## Lets begin

visit here : https://beta.nexus.xyz
- Go to profile section at the bottom left
- Submit email and complete email verification
- Go to home page
- Click connect

## Node setup

### 1. Method one

Setup node via mintair : https://www.mintair.xyz/onboarding?ref=NAVE-ENCN
- Just purchase node using crypto
- Submit your prover ID ( you can get from at the botton left )
- chcek Back In 5-10mins. Your Node Should Be Running.
  
### 2. Method Two

Purchase VPS : https://vpsdime.com/a/4114/linux-vps

- signup with email accout
- Purchase a basic Linux VPS for one month.

![Screenshot 2024-12-11 165849](https://github.com/user-attachments/assets/10dff796-b22e-4f00-824d-c35a5f210815)

  
Install termius : https://termius.com/download/windows

- Install termius on your device.

#### lets start configuring node

- Open termius application
- signup with email account
- click new host
- enter username root
- enter your password

System Update and Initial Setup
```
sudo apt update && sudo apt upgrade -y
```
```
sudo apt install -y build-essential curl wget git
```
Install Rust and Update Toolchain
```
apt install rustup
```
```
rustup update stable
```
```
sudo add-apt-repository universe
```
```
sudo apt update
```
```
sudo apt install -y protobuf-compiler
```
Install Nexus CLI
```
curl https://cli.nexus.xyz/ | sh
```
There will be an Error, don’t worry, keep going
```
source $HOME/.cargo/env
```
```
echo 'source $HOME/.cargo/env' >> ~/.rc
```
Install Additional Dependencies
```
sudo apt install -y pkg-config
```
```
sudo apt install -y libssl-dev
```
```
sudo apt install -y protobuf-compiler
```

set prover ID ( replace "YOUR_PROVER_ID" to your prover ID )
```
echo "YOUR_PROVER_ID" > ~/.nexus/prover-id
```
You can get it from the bottom left of the Nexus page.
<img width="959" alt="Screenshot 2024-12-12 130509" src="https://github.com/user-attachments/assets/bb91767b-4881-4047-b5b6-af526b797062" />
Save Your screen
```
screen -S nexus
```
run verifier
```
curl https://cli.nexus.xyz | sh
```
Press 'Control+A+D'
✅ Done
You will earn points from the CLI. You can check the profile section.
![Screenshot 2024-12-12 131942](https://github.com/user-attachments/assets/222d3288-2d43-4806-b6e3-787d31cc7591)

































### Account setup
