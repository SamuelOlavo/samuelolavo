Atualizar tipografia do Site:

- Utilizando o conceito de pseudo-elemento para a montagem.
p::first-letter { font-size:xx-large; }
Seleciona a primeira letra de todos os parágrafos.

- Ajustar o viweport, para que o ajuste do viewport seja feito pelo Navegador, é necessário que a página HTML traga no <head> a seguinte linha: 
<meta name="viewport" content="width=device-width, initial-scale=1">

- Utilizar o conceito de media querie para melhorar a apresentação da pagina no mobile. As media queries são filtros que podem ser aplicados aos estilos CSS com base em alguma característica do dispositivo onde a página é apresentada para selecionar as regras que serão aplicadas :
Adicionar no heead um link chamando a folha de estilo que possui o ajuste para mobile:
https://developer.mozilla.org/en-US/docs/Web/CSS/@mediawq

