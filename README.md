# 🌐 Projeto de Layout Responsivo

## 🖥️ Preview das Telas
<p align="center">
  <img src="./assets/Mockup pc_phone.png" width="80%" alt="Mockup do site em PC e smartphone">
</p>

## 💡 Abordagem e Detalhes Técnicos

**Abordagem Desktop-First:**  
Estilizei o site todo pensando no computador primeiro e usei uma regra `@media (max-width: 500px)` no final do CSS para adaptar o layout para as telas de celular.

**Menu Fixo e Compacto:**  
No celular, fixei o cabeçalho no topo da tela (`position: fixed`) e diminuí o tamanho da fonte e dos botões para garantir que todos os links do menu coubessem em uma única linha.

**De Lado a Lado para Empilhado:**  
No desktop, deixei a imagem e os textos lado a lado usando **Flexbox**. Já no celular, mudei para `display: block`, o que fez a imagem ficar em cima e o texto embaixo, melhorando a leitura na tela estreita.

**Aproveitamento de Espaço:**  
Removi as margens laterais grandes que existiam no texto para ele ocupar **100% da tela do celular**, e adicionei uma margem extra no topo (`margin-top`) para o conteúdo não ficar escondido atrás do menu que deixei fixo.

**Resumindo:**  
Ajustei os tamanhos das fontes e elementos, e empilhei o conteúdo que antes ficava lado a lado!

---

📁 **Visualização:**  
Basta abrir o arquivo `index.html` no navegador ou acessar o projeto publicado no GitHub Pages.

---

✏️ **Autor:** Alisson  
📅 **Mês/Ano:** 04/2026  
