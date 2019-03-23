# icecast setup

## installation de icecast2
### login 
- admin
- hackme
- port 8000

## fichier de log 
/var/log/icecast2  
access.log pour voir qui se connecte  
error.log  

## fichier de config 
/etc/icecast2/icecast.xml  
<admin-password> password pour le weg gui admin page.  
<listen-socket> both port and bind-address. La bind address dans mon icecat.xml est commentée.  

## Il nous faut 
- un source client
Icecast2 server est lancé.  
Il nous faut maintenant un source server.  
On va avoir besoin de :
	- Adresse IP du server icecast2 on le trouve dans le <listen-socket> de icecast.xml.
   - Port du server on le trouve dans le <listen-socket> de icecast.xml.  
   - source password de <source-password>





