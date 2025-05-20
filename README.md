Html:

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Portfólio de Mateus Ueno</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Mateus Ueno</h1>
        <p>Estudante | Apaixonado por histórias intensas | Explorador da lógica e da imaginação</p>
    </header>

    <section class="foto-principal">
        <img src="pexels-anthony-rahayel-125801377-32134450.jpg" alt="Sobremesa com morangos e pistache">
    </section>

    <section class="sobre">
        <h2>Sobre Mim</h2>
        <p>Sou Mateus, um estudante que mergulha tanto em equações quanto em narrativas provocantes. Quando não estou estudando ou escrevendo, gosto de explorar histórias, aprender algo novo e colocar minha criatividade à prova.</p>
    </section>

    <section class="meus-projetos">
        <h2>Meus Projetos</h2>

        <div class="cards-container">
            <div class="card">
                <img src="e-commerce.jpg" alt="Imagem de E-commerce Orgânico">
                <h3>E-commerce Orgânico</h3>
                <p>Plataforma de e-commerce para produtos orgânicos com sistema de pedidos e pagamento integrado.</p>
            </div>

            <div class="card">
                <img src="turismo.jpg" alt="Imagem de Aplicativo de Turismo">
                <h3>Aplicativo de Turismo</h3>
                <p>Aplicativo mobile para descobrir pontos turísticos com realidade aumentada e guia personalizado.</p>
            </div>

            <div class="card">
                <img src="blog.jpg" alt="Imagem do Blog de Tecnologia">
                <h3>Blog de Tecnologia</h3>
                <p>Blog moderno com sistema de categorias, busca avançada e integração com redes sociais.</p>
            </div>
        </div>
    </section>
</body>
</html>


Css:
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #fffaf5;
    color: #333;
    line-height: 1.6;
    text-align: center;
}

header {
    background-color: #2e2e2e;
    color: white;
    padding: 40px 20px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
}

header h1 {
    margin: 0;
    font-size: 2.5em;
}

header p {
    margin-top: 10px;
    font-size: 1.2em;
}

.foto-principal img {
    width: 100%;
    max-height: 500px;
    object-fit: cover;
    border-bottom: 4px solid #ff4567;
}

section {
    padding: 40px 20px;
    max-width: 1200px;
    margin: auto;
}

.sobre, .meus-projetos {
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    margin-top: 30px;
    padding: 30px;
}

.meus-projetos h2 {
    text-align: center;
    color: #1d3557;
    border-bottom: 3px solid #457b9d;
    display: inline-block;
    padding-bottom: 5px;
    margin-bottom: 30px;
}

.cards-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 30px;
}

.card {
    background-color: #f9f9f9;
    border-radius: 12px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    max-width: 320px;
    padding: 20px;
    text-align: center;
    transition: transform 0.3s ease;
}

.card:hover {
    transform: scale(1.03);
}

.card img {
    width: 100%;
    border-radius: 8px;
    margin-bottom: 15px;
}

.card h3 {
    color: #333;
    margin-bottom: 10px;
}

.card p {
    color: #555;
    font-size: 0.95rem;
}
