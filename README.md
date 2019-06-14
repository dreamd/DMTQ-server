DMTQ-server

Introduction

A dead game's server for playing.


Client Installion

1) Install the certs and trust it
2) change the dns setting to make the official domain to redirect to your server
3) Play
4) reset the dns setting after your play

Server Installion
1) install PHP, apache with SQLITE support
2) enable www.neonapi.com, pmangplus.com, dmqglb.mb.pmang.com to point it to your folder path
3) download the song data inside dmqglb.mb.pmang.com\DMQ\Songs.txt and unzip to `Songs` folder
4) edit apache config to bind 443 and set https support and load the cert inside _info
5) maybe you need to modifty these two files to your absolute path  `line 19 login_dmq.php inside www.neonapi.com and pmangplus.com`
6) set a dns server to point that three domain to your server ip
