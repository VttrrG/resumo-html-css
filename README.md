# 🌐 Guia Rápido de HTML e CSS

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/Web%20Development-000000?style=for-the-badge&logo=internetexplorer&logoColor=white"/>
</p>

> 📚 **Resumo detalhado** sobre HTML e CSS para consulta rápida e aprendizado — perfeito para iniciantes e como referência rápida para projetos.

---

## 📖 1. O que é HTML?
**HTML** (*HyperText Markup Language*) é a **linguagem de marcação** que define a estrutura e o conteúdo de uma página web.  
Ele determina **o que** será exibido no navegador: textos, imagens, vídeos, links e formulários.

### 🛠 Estrutura básica de um documento HTML
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Página</title>
</head>
<body>
    <h1>Olá, Mundo!</h1>
    <p>Este é meu primeiro site usando HTML e CSS.</p>
</body>
</html>


📖 2. Principais Elementos HTML

Títulos: <h1> até <h6>

Parágrafos: <p>

Links: <a href="url">Texto</a>

Imagens: <img src="imagem.jpg" alt="Descrição">

Listas:

Ordenada: <ol><li>Item</li></ol>

Não ordenada: <ul><li>Item</li></ul>

Formulários: <form>, <input>, <textarea>, <button>

O que é CSS?

CSS (Cascading Style Sheets) é a linguagem de estilo que controla como o conteúdo HTML será exibido.
Permite mudar cores, fontes, tamanhos, espaçamentos, alinhamentos e até criar animações.

Formas de usar CSS

Inline — dentro do elemento HTML

<p style="color: blue;">Texto azul</p>

Interno — dentro da tag <style>

<style>
    p { color: blue; }
</style>

Externo — arquivo separado .css

🔤 4. Sintaxe Básica do CSS

seletor {
    propriedade: valor;
}

Exemplo:

h1 {
    color: #ff0000; /* Vermelho */
    font-size: 32px;
    text-align: center;
}


🧩 5. Seletores Comuns

Por tag: p { color: blue; }

Por classe: .classe { color: green; }

Por ID: #meuId { color: red; }

Aninhamento: div p { color: purple; }

Pseudo-classes:

a:hover { color: orange; }

input:focus { border: 2px solid blue; }

📦 6. Conceitos Importantes

Box Model:
Todo elemento é uma caixa com:

content

padding

border

margin

Display:
Define o comportamento do elemento:

block, inline, inline-block, flex, grid, none

Responsividade:
Uso de media queries:

@media (max-width: 768px) {
    body { background-color: lightgray; }
}


💻 7. Exemplo Completo HTML + CSS

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo HTML e CSS</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 20px;
        }
        h1 {
            color: #007bff;
            text-align: center;
        }
        p {
            color: #333;
            line-height: 1.5;
        }
        a {
            color: #ff6600;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <h1>Meu Primeiro Site</h1>
    <p>Este é um exemplo de site simples usando HTML e CSS.</p>
    <p>Visite meu <a href="#">GitHub</a> para ver mais projetos.</p>
</body>
</html>



<link rel="stylesheet" href="style.css">

📌 Conclusão

HTML → Estrutura e conteúdo

CSS → Estilo e aparência

📢 Juntos, eles formam a base do desenvolvimento web, permitindo criar páginas bonitas e funcionais.
