# asterisk
Servidor Asterisk basico:

DESCARGA:
docker pull bikotek/asterisk

EJECUCION:
docker run --net host --name ASTERISK -v /directorio_etc_asterisk/:/etc/asterisk -v /directorio_sonidos_castellano/:/usr/share/asterisk/sounds/es/ -d asterisk


docker exec -it asterisk asterisk -rvvv
