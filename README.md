INDEX.HTML



<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CineFlex</title>
    <style>
        /* Reset básico */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: #f4f4f4;
            line-height: 1.10;
        }

        /* Cabeçalho e Menu */
        header {
            background-color: #1c1c1c;
            padding: 1.5rem 0;
            text-align: center;
        }

        header h1 {
            color: #b91414;
            font-size: 2rem;
        }

        nav {
            margin-top: 10px;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 17px;
        }

        nav ul li a {
            color: #f4f4f4;
            text-decoration: none;
            font-weight: bold;
            padding: 8px 15px;
            transition: background 0.3s;
        }

        nav ul li a:hover {
            background-color: #960c0c;
            border-radius: 10px;
        }

        /* Estilos das Seções */
        main {
            padding: 2rem;
        }

        section {
            margin-bottom: 3rem;
            text-align: center;
        }

        section h2 {
            color: #ba1a1a;
            font-size: 1.8rem;
            margin-bottom: 19px;
        }

        section p {
            color: #ccc;
            font-size: 1rem;
            margin-bottom: 20px;
        }

        /* Card de Filmes e Séries */
        .card-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 30px;
        }

        .card {
            background-color: #333;
            padding: 15px;
            border-radius: 8px;
            text-align:left;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .card:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 16px rgba(250, 2, 2, 0.5);
        }

        .card img {
            max-width: 100%;
            border-radius: 5px;
            margin-bottom: 10px;
        }

        .card h3 {
            font-size: 1.2rem;
            color: #f4f4f4;
            margin-bottom: 8px;
        }

        .card p {
            font-size: 0.9rem;
            color: #ccc;
        }

        /* Botão para ver mais detalhes */
        .card a {
            display: inline-block;
            margin-top: 10px;
            padding: 8px 12px;
            background-color: #a50808;
            color: #fff;
            text-decoration: none;
            border-radius: 4px;
            transition: background 0.10s;
        }

        .card a:hover {
            background-color: #ae1b1b;
        }

        /* Rodapé */
        footer {
            background-color: #1c1c1c;
            color: #f4f4f4;
            text-align: center;
            padding: 1rem 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        
    </style>
</head>
<body>
    <!-- Cabeçalho e Menu -->
    <header>
        <h1>Filmes e Séries</h1>
        <nav>
            <ul>
                <li><a href="#inicio">Início</a></li>
                <li><a href="#filmes">Filmes</a></li>
                <li><a href="#Serie">Serie</a></li>
                <li><a href="#Contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <!-- Conteúdo Principal -->
    <main>
        <section id="inicio">
            <h2>Bem-vindo ao CineFlex</h2>
            <p>Descubra os melhores lançamentos e clássicos do cinema e da TV!</p>
        </section>
        
        <section id="filmes">
            <h2>Filmes</h2>
        </div>

        <section id="Filmes infantis">
            <h2>Filmes infantis</h2>
            <p>Confira nossos filmes infantis em destaque!</p>
            <div class="card-container">
                <div class="card">
                    <img src="Image/Dois irmaos.jpeg" alt="Dois Irmãos: Uma Jornada Fantástica">
                    <h3>“Dois Irmãos E Uma Jornada Fantástica”</h3>
                    <p>Ambientado em um subúrbio de um mundo de fantasia, “Dois Irmãos E Uma Jornada Fantástica”, da Disney•Pixar, apresenta dois irmãos elfos adolescentes que embarcam em uma missão extraordinária para descobrir se ainda há um pouco de mágica por aí..</p>
                    <a href="#">Ver mais</a>
                </div>

                <div class="card">
                    <img src="Image/Wish.jpeg" alt="Wish e o Poder dos Desejos">
                    <h3>Wish e o Poder dos Desejos</h3>
                    <p>"Wish: O Poder dos Desejos", dos estúdios Walt Disney, é uma comédia musical animada que leva o público para o reino mágico de Rosas. Lá, Asha, uma moça perspicaz, faz um desejo tão poderoso que é atendido por uma força cósmica: uma pequena esfera de energia ilimitada chamada Star.</p>
                    <a href="#">Ver mais</a>
                </div>

                <div class="card">
                    <img src="Image/Soul.jpeg" alt="Soul">
                    <h3>Soul</h3>
                    <p>Professor de música em uma escola local, seu grande sonho é se tornar músico profissional como o falecido pai. Ao cair em um bueiro Joe acaba indo parar em um lugar chamado Escola da Vida (pré vida), onde as almas aprendem diversas coisas e criam suas personalidades como animadas, zangadas, entre outras.</p>
                    <a href="#">Ver mais</a>
                </div>
            </div>
        </section>
        
        <section id="comedia">
            <h2>Comedia</h2>
            <p>Descubra as comedia mais populares!</p>
            <div class="card-container">
                <div class="card">
                    <img src="Image/branquelas.jpeg" alt="As Branquelas">
                    <h3>As Branquelas</h3>
                    <p>As Branquelas é uma comédia sobre duas agentes do FBI, que se disfarçam de irmãs gêmeas brancas para investigar um crime.  Elas se envolvem em situações hilárias e inesperadas durante a investigação.  É um filme cheio de comédia e confusão.</p>
                    <a href="#">Ver mais</a>
                </div>
                <div class="card">
                    <img src="Image/minha vida em parte.jpeg" alt="Minha Vida Em Marte">
                    <h3>Minha Vida Em Marte</h3>
                    <p>Em turnê pelo país, a atriz e autora Mônica Martelli volta a Belo Horizonte com um dos maiores sucessos do teatro nacional, o espetáculo Minha vida em Marte, monólogo bem-humorado e emocionante que apresenta os dilemas da vida a dois.A comédia conta a história de Fernanda, casada há oito anos que enfrenta uma crise no casamento.</p>
                    <a href="#">Ver mais</a>
                </div>

                <div class="card">
                    <img src="Image/mnhmae3.jpeg" alt="Minha Mãe É Uma Peça 3">
                    <h3>Minha Mãe É Uma Peça 3</h3>
                    <p> "Minha Mãe e uma Peça 3" continua a saga da hilária Dona Hermínia, interpretada por Paulo Gustavo.  Neste filme, ela enfrenta novos desafios e situações cômicas em meio à família e seus amigos.  A trama geralmente gira em torno de mais confusões, mal-entendidos e momentos de muita risada, mantendo o estilo de comédia familiar dos filmes anteriores.  Sem dar muitos spoilers, posso dizer que é uma continuação divertida e emocionante, com momentos de reflexão sobre família e relacionamentos, tudo temperado com o humor característico da personagem.</p>
                    <a href="#">Ver mais</a>
                </div>
            </div>
        </section>
       
        <section id="Terror">
            <h2>Terror</h2>
            <p>Descubra os filmes mais populares!</p>
            <div class="card-container">
                <div class="card">
                    <img src="Image/itacoisa.jpeg" alt="It a Coisa">
                    <h3>It a Coisa</h3>
                    <p>It A Coisa é um livro de terror escrito por Stephen King, publicado pela primeira vez em 1986. Que foi transformado em um filme que 
                    a história é ambientada na cidade fictícia de Derry, no Maine, e acompanha um grupo de sete crianças (que se autodenominam “O Clube dos Perdedores”) que enfrentam uma entidade maléfica que assume a forma de um palhaço chamado Pennywise.</p>
                    <a href="#">Ver mais</a>
                </div>

                <div class="card">
                    <img src="Image/boneco do mal.jpeg" alt="Boneco Do Mal">
                    <h3>Boneco Do Mal</h3>
                    <p>Boneco do Mal é um filme de terror de 2016 que conta a história de Greta,
                     uma jovem americana que aceita trabalhar como babá em uma pequena vila inglesa. O garoto de 8 anos de quem Greta tem que cuidar é na verdade um boneco que o casal trata como se fosse um menino de verdade.</p>
                    <a href="#">Ver mais</a>
                </div>

               <div class="card">
                    <img src="Image/invocaçaodo mal.jpeg" alt="Invocação Do Mal">
                    <h3>Invocação Do Mal</h3>
                    <p>Estrelado por Vera Farmiga e Patrick Wilson, a produção centra-se em dois investigadores paranormais mundialmente conhecidos,
                     que foram contratados para investigar fenômenos sobrenaturais que assombram à família Perron, moradores da pequena e isolada cidade de Harrisville.</p>
                    <a href="#">Ver mais</a>
                </div>

                <div class="card">
                    <img src="Image/luzdo demonio.jpeg" alt="Luz Do Demonio">
                    <h3>Luz Do Demonio</h3>
                    <p>Em A Luz do Demônio, as ocorrências de possessão demoníaca aumentaram nesses últimos anos, de acordo com o Vaticano. Para ajudar a combater o crescente números de casos, 
                    a Igreja decidiu abrir uma escola voltada a treinar padres aptos para praticar exorcismos.</p>
                    <a href="#">Ver mais</a>
                </div>
            
            <div class="card">
                <img src="Image/annabelle.jpeg" alt="Annabelle">
                <h3>Annabelle</h3>
                <p>Annabelle é um filme de terror que gira em torno de uma boneca possuída por um espírito maligno.  A história se concentra nos eventos que levam à possessão da boneca e as consequências terríveis para aqueles que entram em contato com ela. 
                 É um filme cheio de sustos e suspense, explorando temas de possessão demoníaca e o mal sobrenatural.  </p>
                <a href="#">Ver mais</a>
            </div>
        </div>

             <section id="series">
            <h2>Séries</h2>
            <p>Descubra as séries mais populares!</p>
            <div class="card-container">
                <div class="card">
                    <img src="Image/riverdele novo.jpeg" alt="Riverdele">
                    <h3>Riverdele</h3>
                    <p>Riverdale acompanha um grupo de adolescentes formado por Archie (KJ Apa), Betty (Lili Reinhart), Veronica (Camila Mendes), Jughead Jones (Cole Sprouse) e Josie (Ashleigh Murray), todos alunos do ensino médio. Depois de uma trágica perda, Archie embarca em uma jornada para realizar o seu sonho de se tornar um grande músico.</p>
                    <a href="#">Ver mais</a>
                </div>

                <div class="card">
                    <img src="Image/images.jpeg" alt="Stranger Things">
                    <h3>Stranger Things</h3>
                    <p>A série se passa 97 anos após uma guerra nuclear devastadora que dizimou quase toda a vida na Terra. Os sobreviventes conhecidos são os moradores de doze estações espaciais em órbita da Terra, que já viviam nesta antes do fim da guerra.</p>
                    <a href="#">Ver mais</a>
                </div>

               <div class="card">
                    <img src="Image/download.jpeg" alt="ControlZ">
                    <h3>ControlZ</h3>
                    <p>Quando um garoto desaparece, a cidade toda participa nas buscas. Mas o que encontram são segredos, forças sobrenaturais e uma menina. Este tributo aos clássicos de ficção científica e terror dos anos 1980 recebeu várias indicações ao Emmy.</p>
                </div>

                <div class="card">
                    <img src="Image/you.jpeg" alt="You">
                    <h3>You</h3>
                    <p>You (estilizada como YOU - sendo nomeada no Brasil como Você; em Portugal como Tu) é uma série de televisão americana de suspense psicológico desenvolvida por Greg Berlanti e Sera Gamble</p>
                    <a href="#">Ver mais</a>
                </div>
            
            <div class="card">
                <img src="Image/Wandinha.jpeg" alt="Wandinha">
                <h3>Wandinha</h3>
                <p>Wandinha é um mistério investigativo e sobrenatural que acompanha os anos de Wandinha Addams como estudante na Escola Nunca Mais, onde ela tenta dominar sua habilidade psíquica emergente, investigar uma monstruosa matança que aterroriza a cidade local e resolver o mistério do assassinato que envolveu seus pais há 25 anos.</p>
                <a href="#">Ver mais</a>
            </div>
        </div>

        </section>
        </main>

    <section id="contato">
        <h2>Contato</h2>
        <p>Entre em contato para mais informações!</p>
        <p>Email: contato@cineflex.com</p>
        <p>Telefone: (14) 99139-4018</p>
    </section>

    <!-- Rodapé -->
    <footer>
        <p>&copy; 2024 Site de Filmes e Séries CineFlex. Todos os direitos reservados.</p>
    </footer>
</body>
</html>

----------------------------------------------------------------------------------------------

STYLE.CSS

/* Reset básico */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    background-color: #1c1c1c;
    color: #f4f4f4;
    line-height: 1.6;
}

/* Cabeçalho e Menu */
header {
    background-color: hsl(0, 79%, 22%);
    padding: 1rem 0;
    text-align: center;
}

header h1 {
    color: #f4f4f4;
    font-size: 1.8rem;
}

nav {
    margin-top: 10px;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: #f4f4f4;
    text-decoration: none;
    font-weight: bold;
    padding: 8px 15px;
    transition: background 0.10s;
}

nav ul li a:hover {
    background-color: #555;
    border-radius: 5px;
}

/* Estilos das Seções */
main {
    padding: 2rem;
}

section {
    margin-bottom: 3rem;
    text-align: center;
}

section h2 {
    color: hsl(0, 0%, 0%);
    font-size: 1.5rem;
    margin-bottom: 10px;
}

section p {
    color: #ddd;
    font-size: 1rem;
    margin-bottom: 20px;
}

/* Card de Filmes e Séries */
.card-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
}

.card {
    background-color: #444;
    padding: 15px;
    border-radius: 8px;
    text-align: center;
    transition: transform 0.3s;
}

.card:hover {
    transform: scale(1.05);
}

.card img {
    max-width: 100%;
    border-radius: 5px;
    margin-bottom: 10px;
}

.card h3 {
    font-size: 1.2rem;
    margin-bottom: 8px;
    color: #f4f4f4;
}

.card p {
    font-size: 0.9rem;
    color: #ccc;
}

/* Rodapé */
footer {
    background-color: #333;
    color: #f4f4f4;
    text-align: center;
    padding: 1rem 0;
}
