# pingserver_http_go

Http isteği ile çalışan ping sunucusu

## Kurulum:

```shell
git clone https://github.com/HsmTeknoloji/pingserver_http_go.git
cd pingserver_http_go/devhsmtekpingserver
go mod init github.com/HsmTeknoloji/pingserver_http_go/devhsmtekpingserver
go get
go build
sudo ./devhsmtekpingserver  -port 10001
#veya
./devhsmtekpingserver -h
```

## Kullanım:

```
http://127.0.0.1:{port}?ipaddress=192.168.1.1&count=5&timeout=5&v=1
```

## Geliştirici Bilgileri:
<img src="https://github.com/HsmTeknoloji/companyfiles/blob/master/hsmtek-logo.png?raw=true" width="200"/>
Web Site        : www.hsmteknoloji.com <br />
Developer Groups : https://t.me/HsmTeknoloji/ <br />