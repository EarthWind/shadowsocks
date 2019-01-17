# shadowsocks
> file shadowsocks.sh is a cool way to create shadowsocks server, more detail please visit [https://www.abcdocker.com/abcdocker/2778](https://www.abcdocker.com/abcdocker/2778)

> System Required:  CentOS 6+, Debian 7+, Ubuntu 12+ 

## How to use
- download shadowsocks.sh 
````
wget https://github.com/EarthWind/shadowsocks/blob/master/shadowsocks.sh
````
- change privileges
````
chmod u+x shadowsocks.sh
`````
- execute script
````
sudo ./shadowsocks.sh
````
- input your property and until the script show the message of enjoying it

- start the showdowsocks
````
sudo systemctl status shadowsocks
sudo systemctl start shadowsocks
`````

