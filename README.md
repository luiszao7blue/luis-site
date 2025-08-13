# Lady Gaga - Página Inicial

Este projeto é uma página simples sobre **Lady Gaga**, criada em HTML e CSS, com foco em apresentar informações e imagens da artista.

## 📌 Estrutura do Projeto

- **index.html** → Página inicial com a apresentação da artista.
- **/css/** → Arquivos de estilo (se aplicável).
- **/img/** → Pasta opcional para armazenar imagens locais (atualmente usando links do Wikimedia Commons).


A seção **index** é a parte principal da página, contendo:
- Um título com o nome da artista.
- Uma imagem oficial de domínio público ou licença aberta.
- Um breve texto de apresentação.

Exemplo do bloco HTML da seção:

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
