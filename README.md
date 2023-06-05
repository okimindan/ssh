# ssh
## ssh接続できるまでの準備
- openssh-serverをインストール

*インストールされたかは下記コマンドで確認
 ```
 systemctl status sshd.service
 ```
 
*22番ポートが開いているか下記コマンドで確認
```
ss -atn
```
