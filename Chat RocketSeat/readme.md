Criação de um página estática simulando um chat.

-> HTML:
Icones de "X" e "Enviar" adicionado pelo phosphor icons, adicionando o script no "header" (<script src="https://unpkg.com/phosphor-icons"></script>)

Fonte Roboto 400 e 700 pelo Google fonts, adicionando ao "header"

Javascript mínimo para mostrar sempre a última mensagem enviada no chat, adicionado ao próprio arquivo HTML.

-> CSS:
Resete básico usando:

- {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  }

E transformando o tamanho em pix para rem, no root com:
:root {
font-size: 62.5%; /_ 1rem = 10px _/
}

Assim, 1 rem = 10px.
