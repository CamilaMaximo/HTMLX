 


## Aprendendo HTMLX 

 introdução
htmx dá acesso a AJAX , transições CSS , WebSockets e eventos enviados pelo servidor diretamente em HTML, usando atributos , para que você possa construir interfaces de usuário modernas com a simplicidade e o poder do hipertexto

htmx é pequeno ( ~14k min.gz'd ), livre de dependências , extensível , compatível com IE11 e reduziu o tamanho da base de código em 67% quando comparado com react

motivação
Por que só deveria <a>e <form>ser capaz de fazer solicitações HTTP?
Por que apenas click& submiteventos deveriam ativá-los?
Por que apenas GET& POSTmétodos deveriam estar disponíveis ?
Por que você só deveria poder substituir a tela inteira ?
Ao remover essas restrições, o htmx completa o HTML como um hipertexto



começo rápido
  <script src="https://unpkg.com/htmx.org@1.9.10"></script>
  <!-- have a button POST a click via AJAX -->
  <button hx-post="/clicked" hx-swap="outerHTML">
    Click Me
  </button>




Os atributos hx-poste hx-swapneste botão informam ao htmx:

“Quando um usuário clica neste botão, emita uma solicitação AJAX para /clicked e substitua o botão inteiro pela resposta HTML”

htmx é o sucessor do intercooler.js

Leia a introdução dos documentos para uma introdução mais aprofundada.

