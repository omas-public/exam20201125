# CyberSecurity I Exam 2020 問題用紙

## 問1 [netcat]

netcatを用いて簡易Chatを行い，サーバー側，クライアント側のコマンドをそれぞれ記述せよ

## 問2 [Password Crack]

リポジトリ上の shadow 及び passwd ファイルから 辞書攻撃を用いて omas及びomas2の パスワードを解析せよ，辞書ファイルはリポジトリ上の passwd.listを用いよ。

回答は **ユーザー名:パスワード** の形式でマークダウンのリスト形式で記述せよ。

## 問3 [Port Scanner]

1. nmap を用い 192.168.33.0 - 192.168.33.127 の範囲のIPをPingスキャンするコマンドを記述せよ。
2. nmap を用い metasploitable2のすべてのポートに対してヴァージョンスキャンを行うコマンドを記述せよ。

## 問4 [Metasploit Framework]

Metasploit Frameworkを用いて Metasploitable2上のvftpd の Backdoorを開く Exploit を作成するコマンドをすべて記述せよ

## 問5 [Online Password Cracker]

Hydraを用いてMetasploitable2上のftpアカウントを辞書攻撃で解析する
コマンドおよび結果を記述せよ。 なお辞書はリポジトリ上の user.list および passwd.list とする。

## 問6 [Packet Sniffer]

tcpdump または wireshark にて metasploitable2 との http 通信のみキャプチャーする フィルターコマンドを記述せよ


## 問7

リポジトリの secure.log はここ2週間のアクセスログである
SSHの不正アクセスは正規表現 grep -P 'sshd\[\d+\]: Failed password' で取得できる。以下の質問に答えよ

1. 不正アクセスのrootアクセスの件数を数えよ
2. 不正アクセスのroot以外の不正アクセスユーザー(invalid user)のユーザーのTOP3をリスト形式で記述せよ
3. 不正アクセスが一番多いIPアドレスのアクセス件数と発信国を記述せよ

## 問8

この講義の自分に対して評価点をつけるとすると100点満点中何点をあげますか，点数を記述せよ

## 問9

この講義で学んだことをリスト形式であげ，全体を通しての感想を記述せよ
