<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lady Gaga - Vida e Carreira</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.3/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-icons/1.11.3/font/bootstrap-icons.min.css">
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <header class="p-5 bg-dark text-white">
        <nav class="container d-flex justify-content-between align-items-center">
            <h1 class="h3">Lady Gaga</h1>
            <ul class="nav">
                <li class="nav-item"><a class="nav-link text-white" href="#inicio">Início</a></li>
                <li class="nav-item"><a class="nav-link text-white" href="#biografia">Biografia</a></li>
                <li class="nav-item"><a class="nav-link text-white" href="#galeria">Galeria</a></li>
                <li class="nav-item"><a class="nav-link text-white" href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <main class="container my-5">

        <!-- INÍCIO -->
        <section id="inicio" class="text-center">
            <h2 class="display-4">Bem-vindo ao universo de Lady Gaga</h2>
            <p class="lead">Explore a trajetória de uma das maiores artistas do século XXI.</p>
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7c/Lady_Gaga_presents_artRAVE_Artpop_Ball_2014.jpg/800px-Lady_Gaga_presents_artRAVE_Artpop_Ball_2014.jpg"
                alt="Lady Gaga no artRAVE: The ARTPOP Ball Tour, 2014"
                class="img-fluid rounded shadow" loading="lazy">
            <p class="text-muted small mt-2">Imagem: Justin Higuchi / CC BY 2.0</p>
        </section>

        <!-- BIOGRAFIA -->
        <section id="biografia" class="my-5">
            <div class="row align-items-center">
                <div class="col-md-6">
                    <h2>Quem é Lady Gaga?</h2>
                    <p>Lady Gaga, nascida Stefani Joanne Angelina Germanotta em 28 de março de 1986, é uma cantora,
                        compositora, atriz e produtora musical americana. Reconhecida por sua versatilidade musical e visuais ousados, Gaga alcançou fama mundial com o álbum "The Fame" (2008), que trouxe hits como "Just Dance" e "Poker Face".</p>
                    <p>Além da música, Lady Gaga é reconhecida por seu ativismo em causas sociais e por suas atuações premiadas no cinema, como em *Nasce Uma Estrela* (2018) e *Casa Gucci* (2021).</p>
                </div>
                <div class="col-md-6 text-center">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b5/Lady_Gaga_with_Obama_staffers.jpg/800px-Lady_Gaga_with_Obama_staffers.jpg"
                        alt="Lady Gaga com equipe do governo Obama"
                        class="img-fluid rounded-4 shadow" loading="lazy">
                    <p class="text-muted small mt-2">Imagem: Pete Souza / Domínio Público</p>
                </div>
            </div>
        </section>

        <!-- GALERIA -->
        <section id="galeria" class="my-5">
            <h2 class="text-center">Galeria</h2>
            <div class="row g-4 mt-3">
                <div class="col-md-4">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5a/Lady_Gaga_artRAVE_Paris_2014_4.jpg/640px-Lady_Gaga_artRAVE_Paris_2014_4.jpg"
                        class="img-fluid rounded-3" alt="Lady Gaga performando" loading="lazy">
                    <p class="text-muted small">Imagem: Justin Higuchi / CC BY 2.0</p>
                </div>
                <div class="col-md-4">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1d/Lady_Gaga_on_Nov_1_2010.jpg/640px-Lady_Gaga_on_Nov_1_2010.jpg"
                        class="img-fluid rounded-3" alt="Lady Gaga em 2010" loading="lazy">
                    <p class="text-muted small">Imagem: aphrodite-in-nyc / CC BY 2.0</p>
                </div>
                <div class="col-md-4">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3f/Lady_Gaga_Born_This_Way_Ball_2012.jpg/640px-Lady_Gaga_Born_This_Way_Ball_2012.jpg"
                        class="img-fluid rounded-3" alt="Lady Gaga Born This Way Tour" loading="lazy">
                    <p class="text-muted small">Imagem: karina3094 / CC BY 2.0</p>
                </div>
            </div>
        </section>

        <!-- CONTATO -->
        <section id="contato" class="my-5">
            <div class="bg-light p-5 rounded-4">
                <h2 class="text-center mb-4">Entre em contato</h2>
                <form>
                    <div class="mb-3">
                        <label for="nome" class="form-label">Nome</label>
                        <input type="text" class="form-control" id="nome" placeholder="Seu nome completo">
                    </div>
                    <div class="mb-3">
                        <label for="email" class="form-label">E-mail</label>
                        <input type="email" class="form-control" id="email" placeholder="seu@email.com">
                    </div>
                    <div class="mb-3">
                        <label for="mensagem" class="form-label">Mensagem</label>
                        <textarea class="form-control" id="mensagem" rows="4" placeholder="Sua mensagem"></textarea>
                    </div>
                    <button type="submit" class="btn btn-primary">Enviar</button>
                </form>
            </div>
        </section>
    </main>

    <footer class="text-center p-3 bg-dark text-white mt-5">
        <p>Siga nas redes sociais:</p>
        <i class="bi bi-instagram mx-2"></i>
        <i class="bi bi-twitter-x mx-2"></i>
        <i class="bi bi-youtube mx-2"></i>
        <p class="mt-3 small">Site educativo e sem fins comerciais. Imagens usadas com licença Creative Commons.</p>
    </footer>

</body>

</html>
