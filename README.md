# 🚀 MrDilz Command Package (.deb)

> Welcome, Terminal Warriors! All MrDilz commands are ready to use. Just
> type in your terminal, press Enter, and boom! ✨\
> No complicated setup --- **Executor is ready out of the box**! 😎

------------------------------------------------------------------------

## 📋 Full Command List

  -------------------------------------------------------------------------------
  Command              Short Description
  -------------------- ----------------------------------------------------------
  `mrdilz_setup`       ⚙️ Setup -- Configure API & Wallet

  `mrdilz_chain`       🔗 Chains -- Add / Update / Remove permit chain

  `mrdilz_eip7702`     🔌 EIP-7702 -- Add / Update / Remove EIP-7702 chain

  `approvall`          ✅ Approval -- Run main approval

  `call`               ▶️ Execute -- Run calldata execution

  `call2`              ▶️ Execute V2 -- Run calldata execution V2

  `call_maker`         🛠️ Maker -- Create universal calldata

  `call_pance`         🥞 Pancake Call -- PancakeSwap Maker V2 swap calldata

  `call_panceuniv`     🌐 Pancake Universal -- Pancake universal route swap

  `call_read`          📞 Call Read -- Execute contract read function

  `call_send`          ✉️ Send Call -- Create calldata to send token / NFT

  `call_uniswap`       🦄 Uniswap Call -- Uniswap Maker V2 swap calldata

  `call_uniswapuniv`   🌐 Uniswap Universal -- Uniswap universal route swap

  `call_unwrap`        💎 Unwrap Call -- Unwrap token calldata

  `cek_allow`          🔍 Allowance -- Check spender allowance

  `cek_eip7702`        🧪 RPC EIP-7702 -- Check RPC EIP-7702 support

  `cek_inter`          🔍 Interaction -- Check wallet interactions

  `cek_rpc`            🌐 RPC Check -- Check wallet RPC interaction

  `dbank`              🏦 DBank -- Batch wallet scan via DBank

  `dbank2`             🏦 DBank V2 -- Batch wallet scan via DBank V2

  `eip7702`            ⚡ Delegation -- Execute EIP-7702 delegation

  `exec`               🚀 Exec -- Direct calldata execution

  `executor`           👨‍💻 Executor -- Run calldata executor

  `extract`            📦 Extract -- Extract DBank result data

  `extract_pv`         🔑 Key Extract -- Extract private key

  `farm`               🌾 Farming -- Scan farming on other contracts

  `hold`               💰 Holdings -- Scan wallet balances from contracts

  `hybrid`             ⚡ Hybrid -- Wallet monitoring process

  `hybrid2`            ⚡ Hybrid V2 -- Wallet monitoring process V2

  `nft_trace`          🔎 NFT Trace -- Track NFT positions in wallet

  `norelay`            🚫 No Relay -- Operate without relayer

  `norelay2`           🚫 No Relay V2 -- Operate without relayer V2

  `pancake`            🥞 Swap -- PancakeSwap V3 token swap

  `permit_maker`       📝 Permit -- Create permit call

  `relay`              🚀 Relayer -- Execute permit with relayer

  `relaynft`           🖼️ Relay NFT -- Execute NFT relay

  `rm_pancake`         ♻️ Remove LP -- Remove PancakeSwap V2 liquidity

  `rm_uniswap`         ♻️ Remove LP -- Remove Uniswap V3 liquidity

  `rm_univ2`           ♻️ Remove LP -- Remove Uniswap V2 liquidity

  `scan`               🔎 Scan -- Batch wallet scan (Blockscout API)

  `scan_alc`           🧪 Scan -- Batch wallet scan (Alchemy API)

  `send`               💰 Transfer -- Send native token for execution

  `sushiswap`          🍣 Swap -- Sushiswap V2

  `uniswap`            🦄 Swap -- Uniswap V3 token swap

  `uniswapv2`          🔄 Swap -- Uniswap V2 token swap *(Recommended)*

  `unwrap`             💸 Unwrap -- Unwrap token

  `wd`                 💳 Withdraw/Redeem -- Create withdraw/redeem call

  `zk`                 🌀 zkSync -- Paymaster service & interaction
  -------------------------------------------------------------------------------

> 💡 Tip: All commands can be executed directly from your terminal.
> Type, press Enter, and enjoy! 😎

------------------------------------------------------------------------

## 📥 Install `.deb` (Quick Setup)

``` bash
# Clone repository
git clone https://github.com/dhilz/mrdilz.git
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
