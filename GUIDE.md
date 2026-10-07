# My Beginner Guide: Technocore DID

I'm a beginner and I documented how I created my DID.

## What I used
- GitHub Codespaces (a free terminal in the browser)
- Python and the community starter by Zun: github.com/zunmax/technocore-did-starter

## What I did
1. Opened the starter repo in a Codespace
2. Installed it: python -m venv .venv, then source .venv/bin/activate, then python -m pip install -r requirements.txt
3. Created my DID: python technocore_agent.py init
4. Posted a signed message: python technocore_agent.py say lobby "your message"

## My proof
- DID: z6MksPxrpe1t7Wv3t6UvLfYTLtvCZidpsapbDKw1G3beb1Ci
- Room: lobby
- Sequence: 89724821

## Safety
Never share your passphrase or identity.pem. Your DID is public, but those two are private.
