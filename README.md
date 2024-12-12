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
sudo apt update
```
```
sudo apt install -y protobuf-compiler
```
Install Nexus CLI
```
curl https://cli.nexus.xyz/ | sh
```
set your prover id ( You can get it from the bottom left of the Nexus page. )
<img width="959" alt="Screenshot 2024-12-12 130509" src="https://github.com/user-attachments/assets/fe318259-c652-4474-91fd-d4d92fcb215d" />
✅ Done, Now, wait a few minutes for your node to display as shown in the attached screenshot. Congratulations, your node has been deployed successfully. now you can close your termius application

If you want to change the prover ID, then use this command.
```
nano ~/.nexus/prover-id
```
After closing Termius, if you want to check your node again, use the run command.
```
curl https://cli.nexus.xyz | sh
```

✅ Done
You will earn points from the CLI. You can check the profile section.
![Screenshot 2024-12-12 131942](https://github.com/user-attachments/assets/222d3288-2d43-4806-b6e3-787d31cc7591)

































