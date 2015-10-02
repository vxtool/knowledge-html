Basic structure
========

Um documento HTML válido precisa seguir obrigatoriamente a estrutura composta pelas tags `<html>`, `<head>` e `<body>` e a instrução <!DOCTYPE>.
~~~
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Título da página</title>
  </head>
  <body>
  </body>
</html>
~~~
A tag <html>

Na estrutura do nosso documento, antes de tudo, inserimos uma tag `<html>`. Dentro dessa tag, é necessário declarar outras duas tags: `<head>` e `<body>`. Essas duas tags são "irmãs", pois estão no mesmo nível hierárquico em relação à sua tag "pai", que é `<html>`.


A tag `<head>`

A tag `<head>` contém informações sobre nosso documento que são de interesse somente do navegador, e não dos visitantes do nosso site. São informações que não serão exibidas na área do documento no navegador.
A especificação obriga a presença da tag de conteúdo `<title>` dentro do nosso `<head>`, permitindo especificar o título do nosso documento, que normalmente será exibido na barra de título da janela do navegador ou na aba do documento.

Outra configuração muito utilizada, principalmente em documentos cujo conteúdo é escrito em um idioma como o português, que tem caracteres como acentos e cedilha, é a configuração da codificação de caracteres, chamado de encoding ou charset.


A tag `<meta charset="utf-8">`
Podemos configurar qual codificação queremos utilizar em nosso documento por meio da configuração de charset na tag `<meta>`. Um dos valores mais comuns usados hoje em dia é o UTF-8, também chamado de Unicode. Há outras possibilidades, como o latin1, muito usado antigamente.

O UTF-8 é a recomendação atual para encoding na Web por ser amplamente suportada em navegadores e editores de código, além de ser compatível com praticamente todos os idiomas do mundo.


A tag `<body>`

A tag `<body>` contém o corpo do nosso documento, que é exibido pelo navegador em sua janela. É necessário que o `<body>` tenha ao menos um elemento "filho", ou seja, uma ou mais tags HTML dentro dele.


A instrução DOCTYPE

O DOCTYPE não é uma tag HTML, mas uma instrução especial. Ela indica para o navegador qual versão do HTML deve ser utilizada para renderizar a página. Utilizaremos `<!DOCTYPE html>`, que indica para o navegador a utilização da versão mais recente do HTML - a versão 5, atualmente.

Há muitos comandos complicados nessa parte de DOCTYPE que eram usados em versões anteriores do HTML e do XHTML. Hoje em dia, nada disso é mais importante. O recomendado é sempre usar a última versão do HTML, usando a declaração de DOCTYPE simples:

<!DOCTYPE html>
