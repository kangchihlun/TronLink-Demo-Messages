## TRON Message Board

[View online demo](https://tronwatch.github.io/TronLink-Demo-Messages/)

This is a simple DApp demo built for TRON. It allows you to post messages,
tip messages and receive tips on your messages. It's powered by [TronWeb](https://github.com/tronprotocol/tron-web)
and integrated using [TronLink](https://github.com/TronWatch/TronLink).

Whilst you do not need TronLink installed to view the site, we recommend installing
it if you want to interact with any messages. You can [install TronLink from the Chrome Webstore](https://chrome.google.com/webstore/detail/ibnejdfjmmkpcnlpebklmnkoeoihofec/).

# Tronlink dapp 開發練習
修改成 solidity 0.5.4 版本(每個地址都要加入 payable 修飾字)
建置步驟(記得到.env補上私鑰)
```
tronbox compile --compile-all
tronbox migrate --reset --network shasta
```
