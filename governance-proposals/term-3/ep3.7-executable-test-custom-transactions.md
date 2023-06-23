| description                                                                                        |
| -------------------------------------------------------------------------------------------------- |
| A very long description  A very long description  A very long description A very long description  |

# [Executable] Test custom transactions

  
  | **Status**            | Pending                                                                                                                                      |
  | --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
  | **Discussion Thread** |                                                                                                 |
  | **Votes**             | On chain                                                                                                                                     |
  

# Abstract 
 This proposal executes all three Working Group funding requests for Q1/Q2 2023 as passed in EP 3.1.1, EP 3.1.2, and EP 3.1.3. For more detail, view the ENS Governance docs or view the links below.
1. Q1
2. Q2

# Specification 
 - Transfer 935,000 USDC to 0xbf64C6eCBab9EEf61E1aA3770B35F9D2Cd73208A
- Transfer 125 ETH to 0xbf64C6eCBab9EEf61E1aA3770B35F9D2Cd73208A
- Transfer 3,500 ENS to 0xbf64C6eCBab9EEf61E1aA3770B35F9D2Cd73208A
- Approve ENS to spender 0xbf64C6eCBab9EEf61E1aA3770B35F9D2Cd73208A for max amount

# Transactions 
 | Address                                    | Value   | Function | Argument | Value                                                                          |
| ------------------------------------------ | ------- | -------- | -------- | ------------------------------------------------------------------------------ |
| 0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48 |         | transfer | to       | 0xbf64C6eCBab9EEf61E1aA3770B35F9D2Cd73208A                                     |
|                                            |         |          | amount   | 935000000000                                                                   |
| 0xbf64C6eCBab9EEf61E1aA3770B35F9D2Cd73208A | 125 ETH |          |          |                                                                                |
| 0xC18360217D8F7Ab5e7c516566761Ea12Ce7F9D72 |         | transfer | to       | 0xbf64C6eCBab9EEf61E1aA3770B35F9D2Cd73208A                                     |
|                                            |         |          | amount   | 3500000000000000000000                                                         |
| 0xC18360217D8F7Ab5e7c516566761Ea12Ce7F9D72 | 0 ETH   | approve  | spender  | 0xbf64C6eCBab9EEf61E1aA3770B35F9D2Cd73208A                                     |
|                                            |         |          | amount   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |