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
  
Install termius : https://termius.com/download/windows

- Install termius on your device.

#### lets start configuring node

- Open termius application
- signup with email account
- click new host
- enter username root
- enter your password

Update your system
```
sudo apt update && sudo apt upgrade -y
```
Install required packages
```
sudo apt install -y build-essential pkg-config libssl-dev git-all
```
Install Rust using rustup & rust environment
```
curl --proto '=https' --tlsv1.3 https://sh.rustup.rs -sSf | sh
```
press 1 and click enter
```
 . "$HOME/.cargo/env
```
Verify rust installation & reboot
```
rustc --version
```
```
cargo --version
```
```
sudo reboot
```




























### Account setup
