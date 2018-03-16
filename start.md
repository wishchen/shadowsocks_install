`wget --no-check-certificate  https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks.sh`

`chmod +x shadowsocks.sh`

`./shadowsocks.sh 2>&1 | tee shadowsocks.log`

修改密码
`vi /etc/shadowsocks.json`

`service shadowsocks restart`
`service shadowsocks status`
