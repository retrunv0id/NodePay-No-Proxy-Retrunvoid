# 🌟 NodePay Monitor - No Proxy 🌟

### To run the NodePay Monitor, you'll need to set up your environment and install the necessary dependencies. 

## Configuration
### Get NP_TOKEN
1. Go to [NodePay](https://app.nodepay.ai/register?ref=yyk8pF3JHwKj6Rl)
2. Sign in with your account
3. Inspect Element and go to the local storage tab select https://app.nodepay.ai
4. NP_TOKEN : eyJhbGciOiJIUzUxMiJ9xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

### Add NP_TOKEN to the code
1. Open `np_retrunvoid.txt` in a text editor
2. Replace token_info = 'eyJhbGciOiJIUzxxxxxxxxxxxxxxxxxxxxxxxxxxx' with your NP_TOKEN

### Prerequisites

- Python 3.6 or later
- `pip` (Python package installer)

### Install screen if it's not already installed:

```bash
sudo apt install screen -y
```
Start a new screen session:

```bash
screen -S nodepay
```

```bash
screen -r nodepay
```

### 🛠️ Clone the Repository

```bash
sudo apt update && sudo apt upgrade -y
```
```bash
sudo apt install python3 python3-pip -y
```
```bash
git clone https://github.com/retrunv0id/NodePay-No-Proxy-Retrunvoid.git
```
```bash
cd NodePay-No-Proxy-Retrunvoid
```
```bash
pip install -r requirements.txt
```
Edit Paste You NP TOKEN
```bash
nano np_retrunvoid.txt
```
- Run your script:

```bash
python3 nodepay.py
```
- Detach from the screen session by pressing Ctrl + A, then D. You can reattach later using:

### 🌟 All risks are borne by the user 🌟

## Donasi

If you find this bot helpful, you can provide support via:

- EVM : `0x513569F2a68f29BA2feeEA57664fa919791F3E0D`
- Btc : `bc1pcmctyrzu302zm7u9hxd0usc3mt89vqzuj7n27xdksdvs6lsaylmsf60w7l`

## Disclaimer

This bot is provided without any warranty. Users are fully responsible for the use of bots and the risks that may arise.

## License

MIT License - see the [LICENSE](LICENSE) file for complete details.
