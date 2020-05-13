# pingserver_http_go

Http isteği ile çalışan ping sunucusu

## Kurulum:

```shell
git clone https://github.com/AfatekDevelopers/pingserver_http_go.git
cd pingserver_http_go/devafatekpingserver
go mod init github.com/AfatekDevelopers/pingserver_http_go/devafatekpingserver
go get
go build
sudo ./devafatekpingserver  -port 10001
#veya
./devafatekpingserver -h
```

## Kullanım

```
http://127.0.0.1:{port}?ipaddress=192.168.1.1&count=5&timeout=5&v=1
```

## Geliştirici Bilgileri:
<img src="https://github.com/AfatekDevelopers/companyfiles/blob/master/afatek-logo.png?raw=true" width="200"/>
Web Site        : www.afatek.com.tr <br />
Developer Groups : https://t.me/Afatek/ <br />