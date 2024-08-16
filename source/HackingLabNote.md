---
title: Haking Lab Note
date: 2024-8-15
---
### Haking Lab の実験で使った技術の個人ノート(随時更新)
「ハッキング・ラボのつくりかた 完全版 仮想環境におけるハッカー体験学習」 IPUSIRON 著

### #01 Potato
- Wiresharkでパケットをキャプチャー  
- Nmapでポートスキャン  
- FTPでアクセス  
- Burp SuiteでHTTPリクエストを編集  
### #02 DC-1
- Metasploit Frameworkを用いたexploits  
- droopescanでDrupalなどのCMSをスキャン  
- Exploit DatabaseでExploitやPoCコードなどを調査  
- GTFOBinsでLinuxnoローカル権限昇格を調査  
### #03 DC-2

### #04 Napping
- netenumコマンド：ネットワーク内をpingスイープしIPアドレスを特定するツール  
~~~
$ sudo netenum 192.168.x.0/24 [タイムアウト値] [冗長モード0~3(1以上で端末数の出力)]
~~~  
- hpingコマンド：Pingやポートスキャン  
- 脆弱性：タブナビング攻撃  
- Wfuzzでファジングを実現する  
  
### #05 Victim  
- netdiscoverでLAN内の端末IPを特定
-
commitの確認１




