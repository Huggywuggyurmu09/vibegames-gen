# vibegames-gen
a generator for vibegames.com - a free host

### disclaimer
i am not responsible for what you do with the accounts

## features
⚡ accounts made fast  
⚡ socks5 proxies support  
⚡ request-based, no browser needed  
⚡ multi-threaded generation

## usage
1. install dependencies: `pip install -r requirements.txt`
2. add socks5 proxies to `data/proxies.txt` (format: `ip:port`)
3. run: `python gen.py`
4. follow prompts to generate accounts
5. accounts saved to `output/accs.txt`

## video showcase
https://github.com/user-attachments/assets/ac817b57-6918-4c26-b716-cfd307fe7b5f

## requirements
- python 3.8+
- `requests[socks]`
- `colorama`

## proxy format (example)
1.2.3.4:1080
5.6.7.8:1080
9.10.11.12:1080
