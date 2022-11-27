## Cross-bridge-attacks: Multichain Exploit January 2022

- This repo analyses the Multichain cross bridge attack and propose solution to fixing the buggy router contract leading to the exploit.
- Contains the buggy contracts involved in the attacks
- The link to the simulation for this attack can be found below on Tenderly.
`` https://dashboard.tenderly.co/tx/mainnet/0xe50ed602bd916fc304d53c4fed236698b71691a95774ff0aeeb74b699c6227f7/debugger?trace=0.1 ``
- The address of the malicuous contract is 
`` https://etherscan.io/address/0xb5c827fdbbee6f6e9df3a5cb499aedf5927de1b8 ``.

- Our lack of finding the source code to the malicious contracts contrained us from replicating original attack using foundry, thus could not conduct test on our local machine. However, we are certain the report above sheds light on the attack. And then presents a robust solition to eliminating this particular type of cross bridge attacks.
