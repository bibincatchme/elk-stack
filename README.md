 vi openssl.cnf




sudo openssl req -x509 -days 365 -batch -nodes -newkey rsa:2048 -keyout logstash-forwarder.key -out logstash-forwarder.crt
