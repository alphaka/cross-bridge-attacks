## Cross-bridge-attacks: Multichain Exploit January 2022

- This repo analyses the Multichain cross bridge attack and propose solution to fixing the buggy router contract leading to the exploit.
- Contains the buggy contracts involved in the attacks
- Linked to the simulation for the attack can be found here on Tenderly.
`` https://dashboard.tenderly.co/tx/mainnet/0xe50ed602bd916fc304d53c4fed236698b71691a95774ff0aeeb74b699c6227f7/debugger?trace=0.1 ``
- The address to the malicuous contract is 
`` https://etherscan.io/address/0xb5c827fdbbee6f6e9df3a5cb499aedf5927de1b8 ``.

- Our lack of finding the source code the malicious contracts contrained us from replicating original attack using foundry. However, we are certainly the report above sheds light on the attack and presents a robust solition to eliminate this particular type of cross bridge attacks.