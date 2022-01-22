# cats-dogs-YOLOv4
Detecção de gatos e cachorros utilizando YOLOv4

## Tecnologias utilizadas
- Google Colab
- YOLOv4
- opencv
- python

## Para utiizar
- É necessário fazer o download do arquivo yolov4.zip disponibilizado por este link: https://drive.google.com/file/d/1-FVZZIzgDCip7_pj9DubeoQ5iuFBYMdy/view?usp=sharing
- Subir para o google drive
- trocar o diretório que está no colab para o seu
- Ao testar imagens, trocar o diretório para não gerar erros.
- É necessário o opencv versão 4.4.0 + 

## OBS:

- Neste projeto, foi limitado as predições para apenas gatos e cachorros. Caso queria mudar, basta excluir a variável classes no tópico *definindo algumas configurações*, além de apagar o código *if labels[IDclass[i]] in classes:* dentro do tópico *resultado*. Dessa forma, poderá reconhecer todos os objetos que a rede foi treinada.
