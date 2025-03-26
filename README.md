# SeismicSys-Devnet-Deployment
A simple guide and script to deploy a contract on SeismicSys Devnet and earn the Magnitude 1.0 role.

# SeismicSys Devnet Deployment 🚀

A simple guide to deploying a contract on **SeismicSys Devnet** and earning the **Magnitude 1.0** role.

## 🛠 Requirements
- A VPS running Ubuntu 22.04
- If on Windows, install WSL and set up Ubuntu:

## 🚀 Quick Deployment
Run the following command in your VPS terminal:
```bash
bash <(curl -sL https://raw.githubusercontent.com/solotop999/blockchain_scripts/main/Seismic_deploy_contract.sh)
```bash

This script will:  Install dependencies
- Deploy the contract
- Interact with the deployed contract
Follow any prompts that appear (e.g., Press Enter, visit Seismic Faucet to get gas).

Final Steps
Take a screenshot after successful deployment

Post it on X (Twitter) – Example: x.com/0xstephen_

Join Seismic Discord : https://discord.gg/WyrsANwd

Share your X (Twitter) post in #Champion

Post your screenshot & feedback in #devnet

Wait for the Magnitude 1.0 role

✅ DONE! (No need to keep the VPS running after this.)

Additional Commands
Manually Deploy Contract
bash
cd /root/try-devnet/packages/contract/ && bash script/deploy.sh
Interact with the Contract
bash
cd /root/try-devnet/packages/cli/ && bash script/transact.sh
Uninstall & Remove Data
bash
rm -rf /root/.seismic/ /root/try-devnet/
📢 Credits
Special thanks to solotop999 for providing the original script.
