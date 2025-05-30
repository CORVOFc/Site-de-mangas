  ![04](https://github.com/user-attachments/assets/c8642032-fd24-4e90-81d4-57d7dec1c01e)


# MangaViewers

MangaViewers é uma aplicação web moderna e responsiva, feita para quem ama mangás. Ela oferece uma experiência fluida para você descobrir e curtir uma enorme variedade de títulos, com uma interface limpa, buscas eficientes e um design fácil de usar.

---

## Funcionalidades

* **Design Responsivo:** Funciona bem em qualquer aparelho, seja desktop ou celular, pra você ter sempre a melhor experiência.
* **Mangás em Destaque:** Navegue por uma seleção especial de títulos de mangás, com detalhes e tags pra te ajudar a escolher.
* **Navegação Fácil:** Acesse rapidamente as seções "Mangás", "Listas" e "Scans" pelo menu principal.
* **Login de Usuário:** Uma página de login dedicada pra você acessar suas funcionalidades personalizadas.
* **Tela de Carregamento (Preloader):** Uma tela de carregamento visualmente legal com uma barra de progresso que aparece enquanto o site carrega.

---

## Tecnologias Usadas

* **HTML5:** Pra estruturar as páginas do site.
* **CSS3:** Pra estilizar tudo e deixar o site responsivo.
* **JavaScript:** Pra dar vida aos elementos interativos, tipo a tela de carregamento.
* **Google Fonts (Inter):** Pra usar uma fonte moderna e limpa.
* **Font Awesome:** Pra ter ícones escaláveis e bonitos.

---

## Estrutura do Projeto

├── img/

│   67f56131eb428.png

│   67eecac034889.png

│   67f7ef8924e0a.png

│   67fc091255187.png

│   67fc0954ec242.png

│   mangaviewers.png

│   ui_user_profile_person_icon_208878.svg

├── teste.css

├── entrar.css

├── index.html


└── entrar.html


---

* `index.html`: É a página principal, onde você vê os mangás em destaque.
* `entrar.html`: A página de login pra você entrar na sua conta.
* `teste.css`: O arquivo de estilos para a página principal.
* `entrar.css`: O arquivo de estilos para a página de login.
* `img/`: Onde ficam todas as imagens usadas no projeto.

---


## Como Usar

* **Página Inicial (`index.html`):** Mostra uma grade de cards com os mangás, suas descrições e tags. Uma tela de carregamento com barra de progresso aparece antes do conteúdo.
* **Navegação:** Use os links no cabeçalho (`Mangás`, `Listas`, `Scans`) pra ir pras outras seções (esses links levam pra um site externo no código ).
* **Página de Login (`entrar.html`):** Clique em "Entrar" no cabeçalho pra acessar o formulário de login.

---

## Pra Personalizar

* **Conteúdo:** Pra mudar os mangás em destaque, edite os elementos `<article class="card">` dentro da seção `<main>` do `index.html`.
* **Estilo:** Mexa no `teste.css` pros estilos da página principal e no `entrar.css` pros estilos da página de login pra deixar do seu jeito.
* **Tela de Carregamento:** Altere a duração do `setTimeout` na tag `<script>` dentro do `index.html` pra mudar quanto tempo a tela de carregamento aparece. Você também pode mexer nas propriedades de `animation` no `teste.css` pra `.progress-bar`.

---




