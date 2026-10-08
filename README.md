
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog Conexão Digital</title>
    <meta name="description" content="Blog sobre tecnologia, educação e inovação.">
</head>
<body>

    <header>
        <h1>Blog Conexão Digital</h1>

        <nav aria-label="Navegação principal">
            <a href="#inicio">Início</a>
            <a href="#artigos">Artigos</a>
            <a href="#inscricao">Inscreva-se</a>
        </nav>
    </header>

    <main id="inicio">
        <section id="artigos">
            <h2>Últimas publicações</h2>

            <article>
                <h2>A importância da tecnologia na educação</h2>

                <p>
                    A tecnologia transformou a maneira como aprendemos.
                    Plataformas digitais, videoaulas e ferramentas interativas
                    tornam o conhecimento mais acessível e dinâmico.
                </p>

                <img
                    src="https://images.unsplash.com/photo-1509062522246-3755977927d7?auto=format&amp;fit=crop&amp;w=800&amp;q=80"
                    alt="Estudantes participando de uma atividade educacional"
                    width="600"
                >
            </article>

            <article>
                <h2>Inteligência artificial no cotidiano</h2>

                <p>
                    A inteligência artificial está presente em diversas
                    atividades do dia a dia, desde assistentes virtuais
                    até ferramentas que auxiliam nos estudos e no trabalho.
                    Seu uso consciente pode trazer muitos benefícios.
                </p>

                <img
                    src="https://images.unsplash.com/photo-1677442136019-21780ecad995?auto=format&amp;fit=crop&amp;w=800&amp;q=80"
                    alt="Representação visual de inteligência artificial"
                    width="600"
                >
            </article>
        </section>
    </main>

    <aside id="inscricao">
        <h2>Inscreva-se no nosso blog</h2>

        <p>
            Preencha o formulário para receber novidades
            sobre os assuntos que mais interessam a você.
        </p>

        <form action="" method="get">
            <fieldset>
                <legend>Dados pessoais</legend>

                <p>
                    <label for="nome">Nome completo:</label><br>
                    <input
                        type="text"
                        id="nome"
                        name="nome"
                        minlength="3"
                        pattern="[A-Za-zÀ-ÿ][A-Za-zÀ-ÿ '\-]{2,}"
                        title="Digite pelo menos 3 letras."
                        autocomplete="name"
                        required
                    >
                </p>

                <p>
                    <label for="email">E-mail:</label><br>
                    <input
                        type="email"
                        id="email"
                        name="email"
                        autocomplete="email"
                        required
                    >
                </p>

                <p>
                    <label for="idade">Idade:</label><br>
                    <input
                        type="number"
                        id="idade"
                        name="idade"
                        min="18"
                        max="120"
                        required
                    >
                </p>
            </fieldset>

            <fieldset>
                <legend>Preferências</legend>

                <p>
                    <label for="assunto">Assunto de interesse:</label><br>
                    <select id="assunto" name="assunto" required>
                        <option value="">Selecione um assunto</option>
                        <option value="tecnologia">Tecnologia</option>
                        <option value="educacao">Educação</option>
                        <option value="inteligencia-artificial">
                            Inteligência Artificial
                        </option>
                    </select>
                </p>

                <p>
                    <input
                        type="checkbox"
                        id="termos"
                        name="termos"
                        value="aceito"
                        required
                    >
                    <label for="termos">
                        Aceito os termos e condições.
                    </label>
                </p>
            </fieldset>

            <button type="submit">Enviar inscrição</button>
        </form>
    </aside>

    <footer>
        <p>&copy; 2026 Blog Conexão Digital. Todos os direitos reservados.</p>
        <p>Conteúdo sobre tecnologia, educação e inovação.</p>
    </footer>

</body>
</html>
