# shadowsocks-android-java

Last release: [Download](https://github.com/dawei101/shadowsocks-android-java/releases)


This version of shadowsocks for android is pure java version.
Beacuse of the way of implementation, some feature would not work (icmp protocol, and correct dns result under command line)

Most code is merged from [smartproxy](https://github.com/hedaode/SmartProxy) and [shadowsocks-java](https://github.com/blakey22/shadowsocks-java)
This app inherit Smartproxy's feature: tiny/low power cost/simple operation


shadowsocks settings format

```
ss://method:password@host:port
ss://base64encode(method:password@host:port)
```

And also it inherited the support of http proxy from Smartproxy , Set the url as stardand http(s) proxy format when use it. 

http proxy foramt:

```
http://(username:passsword)@host:port
```
Support methods of encryption:

```
bf-cfb
seed-cfb
aes-128-cfb
aes-192-cfb
aes-256-cfb
aes-128-ofb
aes-192-ofb
aes-256-ofb
camellia-128-cfb
camellia-192-cfb
camellia-256-cfb
chacha20
chacha20-ietf
rc4-md5
```
```
ss://method:password@host:port
ss://base64encode(method:password@host:port)
```
```
http://(username:passsword)@host:port
```
```
bf-cfb
seed-cfb
aes-128-cfb
aes-192-cfb
aes-256-cfb
aes-128-ofb
aes-192-ofb
aes-256-ofb
camellia-128-cfb
camellia-192-cfb
camellia-256-cfb
chacha20
chacha20-ietf
rc4-md5
```

Brother version

##### [Shadowsocks android(Scala)](https://github.com/shadowsocks/shadowsocks-android)

[shadowsocks windows，mac osx，linux](https://github.com/dawei101/tongsheClient.shadowsocks-go)



