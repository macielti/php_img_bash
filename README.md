# php_img_bash
Este projeto tem como base o [Shell semi-interativo PHP - Arraxel](https://github.com/Arrexel/phpbash).
Neste projeto adiciono uma nova funcionalidade, que a possibilidade de empacotar o Shell PHP em uma imagem.
Assim quando abrirmos a imagem dentro do servidor, o arquivo **grego.php** será gerado no mesmo diretório da imagem, então é só acessa-lo para ter o seu Shell rodando a partir do navegador.

## Como usar:
1. Primeiramente precisamos baixar o [cavalo.php](https://github.com/macielti/php_img_bash) que está no [nosso repositório](https://github.com/macielti/php_img_bash). Precisamos de uma imagem qualquer que seja aceita pelo sistema de upload do site.

2. Agora devemos concatenar o conteúdo de **cavalo.php** na **imagem.jpg**:
* $ cat cavalo.php >> imagem.jpg
3. Depois temos que renomear a imagem de modo que o site, ao mesmo tempo, encare o arquivo como uma imagem e que também seja interpretado como php quando acessarmos o arquivo, geralmente alterando a extenção para **.jpg.php** ou **.jpg.php5**.
4. Quando acessarmos a url da imagem dentro do servidor, a execução da imagem vai gerar o arquivo **grego.php** no mesmo diretório da imagem.
5. Acesse o arquivo **grego.php** no mesmo diretório da imagem, assim terá acesso a uma shell pelo navegador.

## Vídeo de Demonstração <Em Breve>
