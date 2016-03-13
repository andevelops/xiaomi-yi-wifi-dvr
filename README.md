# xiaomi-yi-wifi-dvr

Script just copies records from Xiaomi Yi Smart Wifi Cam locally.

Works only with cameras having custom firmware from http://4pda.ru/forum/index.php?showtopic=638230&st=3320#entry44957200 (only ftp-server needed)

## Usage

Just put line like this into your crontab

	*/5 * * * * /home/user/dvr/dvr 192.168.0.100 /home/user/dvr-records/
