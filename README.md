#Docker HTTPS

Servidor Nginx para ambiente de desenvolvimento em HTTPS utilizando certificado auto assinado.

Comando abaixo gera o certificado e sua chave para utilizar no Nginx válido por um ano:

openssl req -x509 -nodes -newkey rsa:2048 -keyout cert.key -out cert.crt -days 365