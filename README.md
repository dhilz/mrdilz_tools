# 🚀 MrDilz Command Package (.deb)

> Welcome, Terminal Warriors!\
> All MrDilz commands are ready to use. Just type in your terminal,
> press Enter, and boom! ✨\
> No complicated setup --- **Executor is ready out of the box**! 😎

------------------------------------------------------------------------

## 📋 Full Command List (Numbered)

1.  `mrdilz_setup` -- ⚙️ Setup -- Configure API & Wallet\
2.  `mrdilz_chain` -- 🔗 Chains -- Add / Update / Remove permit chain\
3.  `mrdilz_eip7702` -- 🔌 EIP-7702 -- Add / Update / Remove EIP-7702
    chain\
4.  `approvall` -- ✅ Approval -- Run main approval\
5.  `call` -- ▶️ Execute -- Run calldata execution\
6.  `call2` -- ▶️ Execute V2 -- Run calldata execution V2\
7.  `call_maker` -- 🛠️ Maker -- Create universal calldata\
8.  `call_pance` -- 🥞 Pancake Call -- PancakeSwap Maker V2 swap
    calldata\
9.  `call_panceuniv` -- 🌐 Pancake Universal -- Pancake universal route
    swap\
10. `call_read` -- 📞 Call Read -- Execute contract read function\
11. `call_send` -- ✉️ Send Call -- Create calldata to send token / NFT\
12. `call_uniswap` -- 🦄 Uniswap Call -- Uniswap Maker V2 swap calldata\
13. `call_uniswapuniv` -- 🌐 Uniswap Universal -- Uniswap universal
    route swap\
14. `call_unwrap` -- 💎 Unwrap Call -- Unwrap token calldata\
15. `cek_allow` -- 🔍 Allowance -- Check spender allowance\
16. `cek_eip7702` -- 🧪 RPC EIP-7702 -- Check RPC EIP-7702 support\
17. `cek_inter` -- 🔍 Interaction -- Check wallet interactions\
18. `cek_rpc` -- 🌐 RPC Check -- Check wallet RPC interaction\
19. `dbank` -- 🏦 DBank -- Batch wallet scan via DBank\
20. `dbank2` -- 🏦 DBank V2 -- Batch wallet scan via DBank V2\
21. `eip7702` -- ⚡ Delegation -- Execute EIP-7702 delegation\
22. `exec` -- 🚀 Exec -- Direct calldata execution\
23. `executor` -- 👨‍💻 Executor -- Run calldata executor\
24. `extract` -- 📦 Extract -- Extract DBank result data\
25. `extract_pv` -- 🔑 Key Extract -- Extract private key\
26. `farm` -- 🌾 Farming -- Scan farming on other contracts\
27. `hold` -- 💰 Holdings -- Scan wallet balances from contracts\
28. `hybrid` -- ⚡ Hybrid -- Wallet monitoring process\
29. `hybrid2` -- ⚡ Hybrid V2 -- Wallet monitoring process V2\
30. `nft_trace` -- 🔎 NFT Trace -- Track NFT positions in wallet\
31. `norelay` -- 🚫 No Relay -- Operate without relayer\
32. `norelay2` -- 🚫 No Relay V2 -- Operate without relayer V2\
33. `pancake` -- 🥞 Swap -- PancakeSwap V3 token swap\
34. `permit_maker` -- 📝 Permit -- Create permit call\
35. `relay` -- 🚀 Relayer -- Execute permit with relayer\
36. `relaynft` -- 🖼️ Relay NFT -- Execute NFT relay\
37. `rm_pancake` -- ♻️ Remove LP -- Remove PancakeSwap V2 liquidity\
38. `rm_uniswap` -- ♻️ Remove LP -- Remove Uniswap V3 liquidity\
39. `rm_univ2` -- ♻️ Remove LP -- Remove Uniswap V2 liquidity\
40. `scan` -- 🔎 Scan -- Batch wallet scan (Blockscout API)\
41. `scan_alc` -- 🧪 Scan -- Batch wallet scan (Alchemy API)\
42. `send` -- 💰 Transfer -- Send native token for execution\
43. `sushiswap` -- 🍣 Swap -- Sushiswap V2\
44. `uniswap` -- 🦄 Swap -- Uniswap V3 token swap\
45. `uniswapv2` -- 🔄 Swap -- Uniswap V2 token swap *(Recommended)*\
46. `unwrap` -- 💸 Unwrap -- Unwrap token\
47. `wd` -- 💳 Withdraw/Redeem -- Create withdraw/redeem call\
48. `zk` -- 🌀 zkSync -- Paymaster service & interaction

> 💡 Tip: All commands can be executed directly from your terminal.
> Type, press Enter, and enjoy! 😎

------------------------------------------------------------------------

## 📥 Install `.deb` (Quick Setup)

``` bash
# Clone repository
git clone of the link repo / private repo
cd mrdilz

# Grant execute permission to the .deb file
chmod +x *.deb

# Install package
sudo dpkg -i *.deb

# Run initial configuration setup
sudo mrdilz_setup
```

------------------------------------------------------------------------

## 🗑️ Uninstall

``` bash
# Remove package
sudo dpkg -r mrdilz

# Remove configuration files (optional)
sudo rm -rf /opt/MrDilz
```

------------------------------------------------------------------------

> ⚠️ Disclaimer: Use this software responsibly and at your own risk.\
> ⚠️ For Relayer whitelist access, please DM Telegram: @dilz232.
