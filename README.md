# aws-loadbalancer-app-demo
HTML static pages and docker file to generate the containers used on the medium tutorial.

# Gerando imagem da Página 1 e subindo app na porta 80
$ docker build -t pagina1 .
$ docker run -dit --name pagina1 -p 80:80 pagina1

# Gerando imagem da Página 1 e subindo app na porta 443
$ docker build -t pagina2 .
$ docker run -dit --name pagina2 -p 443:80 pagina2

