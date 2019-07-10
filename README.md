# mysql
Bastille Jail MRTG Template


After this is built you need to add the hosts you want to monitor to MRTG


	
	cfgmaker --global 'WorkDir: /usr/local/www/mrtg' \
	   --global 'Options[_]: growright,bits' \
	   --global 'WithPeak[_]: yes' \
	   --output /usr/local/etc/mrtg/mrtg.cfg \
	   community@host1.example.org community@host2.example.org



