

## 📱 Responsividade

Este projeto foca em **dispositivos com telas grandes** (desktop), utilizando `@media screen and (min-width: 500px)` para ativar a sidebar interativa e a disposição em grid.

[Clique aqui](https://youtube-gridlayout1.netlify.app/), para acessar o site do projeto.


## 🎨 Tecnologias utilizadas

- HTML5
- CSS3 (com Grid Layout e Transições)
- JavaScript (DOM + Toggle de classes)



## 🧠 Como funciona a sidebar?

Ao clicar no botão de menu:

1. O JavaScript aplica a classe `.collapsed` ao container principal.
2. O CSS ajusta automaticamente o `grid-template-columns`, reduzindo a largura da sidebar.
3. Os textos dentro da sidebar (com classe `.sidebar-text`) são ocultados com transição.

