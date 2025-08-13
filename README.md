# 🎤 Lady Gaga - Página Inicial

Este projeto é uma página em HTML e CSS dedicada à artista **Lady Gaga**, apresentando informações, imagens e um design com plano de fundo multicolorido.

---

## 📂 Estrutura do Projeto

- **index.html** → Página principal com o conteúdo sobre Lady Gaga.
- **/css/** → Arquivos de estilo (se houver).
- **/img/** → Pasta opcional para imagens locais (no momento, todas as imagens são carregadas via URL externa).

---

## 🖼️ Imagens Utilizadas

Todas as imagens foram obtidas do **Wikimedia Commons** e possuem licenças abertas para uso.

| Descrição | Link da Imagem | Licença |
|-----------|----------------|---------|
| Lady Gaga no Grammy Awards 2017 | [Ver Imagem](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e2/Lady_Gaga_Grammys_2017.png/800px-Lady_Gaga_Grammys_2017.png) | [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/deed.pt) |
| Lady Gaga em apresentação ao vivo | [Ver Imagem](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4a/Lady_Gaga_-_ArtRave_-_The_Artpop_Ball_Tour_%2814210479935%29.jpg/800px-Lady_Gaga_-_ArtRave_-_The_Artpop_Ball_Tour_%2814210479935%29.jpg) | [CC BY 2.0](https://creativecommons.org/licenses/by/2.0/deed.pt) |
| Lady Gaga em tapete vermelho | [Ver Imagem](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9d/Lady_Gaga_at_the_2019_Grammy_Awards.png/800px-Lady_Gaga_at_the_2019_Grammy_Awards.png) | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.pt) |

---

## 📌 Estrutura da Página

A página é dividida em seções:

1. **Cabeçalho** → Nome e navegação.
2. **Seção Index** → Apresenta Lady Gaga com imagem e breve introdução.
3. **Galeria** → Outras imagens da artista.
4. **Rodapé** → Créditos e informações legais.

---

## 💻 Código da Seção Index

```html
<section id="index" class="container my-5 text-center">
    <h1 class="mb-4">Lady Gaga</h1>

    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e2/Lady_Gaga_Grammys_2017.png/800px-Lady_Gaga_Grammys_2017.png"
         alt="Lady Gaga no Grammy Awards 2017"
         class="img-fluid rounded shadow mb-3" loading="lazy">
    <p class="text-muted small">
        Imagem: Rogue Artists / CC BY 3.0
    </p>

    <p class="lead">
        Lady Gaga é uma cantora, compositora e atriz norte-americana, conhecida por sua originalidade e versatilidade artística.
    </p>
</section>
