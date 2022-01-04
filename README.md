## 使い方
ローカルにPull
1. PJPrefixとして、プロジェクト名を入力
2. SSHを許可するCIDR範囲を指定
3. SSHするためのキーペアを予め作成する

## トラブルシューティング
ALBのDNSでアクセスし、502BATGatewayになるなら
EC2にSSHして、sudo service httpd start入力してApacheを再起動する。