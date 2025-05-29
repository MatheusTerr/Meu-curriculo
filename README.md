# 💼 Meu Currículo Interativo Online

Bem-vindo ao repositório do meu currículo online! Este projeto foi desenvolvido como uma forma dinâmica, moderna e interativa de apresentar minhas qualificações, experiências e projetos. Em vez de um PDF tradicional, optei por criar uma página web responsiva e rica em funcionalidades.

🔗 **Acesse o currículo online aqui:** [**Meu Currículo**](https://matheusterr.github.io/Meu-curriculo/)

---

## ✨ Funcionalidades Implementadas

Este currículo vai além de uma simples página estática, oferecendo uma experiência de usuário aprimorada com:

* **🎨 Modo Claro/Escuro:** Alternância de tema para conforto visual, com a preferência salva no navegador do usuário.
* **🌐 Troca de Idioma (PT/EN):** Conteúdo disponível em Português e Inglês, com seleção fácil e persistência da escolha.
* **🚀 Animações de Rolagem (Scroll Reveal):** Elementos e seções surgem suavemente conforme o usuário rola a página, tornando a navegação mais fluida e engajadora.
* **⬆️ Botão "Voltar ao Topo":** Facilita a navegação, permitindo retornar rapidamente ao início da página com uma animação suave.
* **☀️ Mensagem Dinâmica de Saudação:** Uma saudação personalizada ("Bom dia!", "Boa tarde!", "Boa noite!") é exibida com base na hora local do visitante.
* **⌨️ Animação de Digitação no Cabeçalho:** Um efeito de "máquina de escrever" no subtítulo do cabeçalho adiciona um toque moderno.
* **📱 Design Responsivo:** Totalmente adaptável a diferentes tamanhos de tela, de desktops a dispositivos móveis.
* **📄 Impressão Otimizada para PDF:** Configurações para uma impressão limpa e profissional, tentando remover cabeçalhos/rodapés do navegador e mantendo a nota sobre o projeto visível no PDF.

---

## 🛠️ Tecnologias Utilizadas

A construção deste projeto envolveu as seguintes tecnologias e ferramentas:

* **HTML5:** Estruturação semântica do conteúdo.
* **Tailwind CSS (via Play CDN para a versão online):** Framework CSS utility-first para estilização rápida e responsiva.
* **JavaScript (Vanilla):** Para todas as interatividades.
* **Font Awesome (via CDN):** Para os ícones utilizados na interface.
* **Google Fonts (Inter):** Para uma tipografia moderna e legível.
* **Node.js, npm, PostCSS, Tailwind CLI:** Para o ambiente de desenvolvimento local e processo de build do CSS (detalhado abaixo).
* **GitHub Pages:** Para hospedagem e deploy do currículo online.

---

## 🏗️ Estrutura de Desenvolvimento e Deploy

Este repositório inclui uma configuração completa para desenvolvimento local com Tailwind CSS, utilizando Node.js para gerenciar dependências (`package.json`) e ferramentas como PostCSS e o CLI do Tailwind para processar um arquivo `input.css` (localizado em `src/`) e gerar um `output.css` otimizado. Este é um fluxo de trabalho robusto, ideal para projetos maiores, pois permite total personalização e otimização do CSS.

No entanto, para a versão demonstrativa online hospedada no GitHub Pages (e para facilitar a visualização baixando apenas o `index.html`), este currículo utiliza o **Tailwind CSS Play CDN**. Isso permite que as classes utilitárias e a diretiva `@apply` (usada na tag `<style>` do `index.html`) sejam processadas diretamente no navegador, sem a necessidade de um arquivo CSS compilado separadamente para a demonstração.

**Resumindo:** O arquivo `index.html` é autossuficiente para visualização online graças ao Play CDN. A estrutura de pastas e arquivos de configuração no repositório (como `tailwind.config.js`, `postcss.config.js`, `input.css`) reflete o ambiente de desenvolvimento local que utilizei para construir e refinar os estilos antes de simplificar para o deploy com CDN.

---

## 🚀 Como Visualizar

1.  **Online (Recomendado):** A forma mais fácil é acessando o link: [**Meu Currículo**](https://matheusterr.github.io/Meu-curriculo/)
2.  **Localmente (Versão CDN Simples):**
    * Baixe apenas o arquivo `index.html`.
    * Abra-o em qualquer navegador moderno.
3.  **Localmente (Com Ambiente de Desenvolvimento Completo):**
    * Clone este repositório: `git clone https://github.com/MatheusTerr/Meu-curriculo.git`
    * Navegue até a pasta do projeto: `cd Meu-curriculo`
    * Instale as dependências: `npm install`
    * Execute o script para compilar o CSS (ex: `npm run build` ou `npm run dev`, dependendo de como configurou no seu `package.json`) para gerar o `output.css` a partir do `src/input.css`.
    * (Opcional) Se for testar o build local, comente a linha do Play CDN no `index.html` e adicione o link para o seu `output.css` gerado.
    * Abra o `index.html` no navegador.

---

## 📝 Observações Adicionais

* A funcionalidade de troca de idioma requer que os textos traduzidos estejam presentes no HTML, devidamente marcados com atributos `lang="pt"` e `lang="en"` (ou `data-lang`).

---

## 📄 Sobre

Desenvolvido por **Matheus Queiroz Batista** como uma forma criativa, visual e interativa de destacar experiências, habilidades e projetos de forma online e acessível. Este projeto em si é um reflexo da minha paixão por desenvolvimento web e atenção aos detalhes.

---

Espero que goste da apresentação! Sinta-se à vontade para explorar o código e, se tiver alguma sugestão, ficarei feliz em ouvir.
