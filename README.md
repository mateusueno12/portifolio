  <!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Meu Portfólio</title>
</head>
<body>
    <div class="header_content">
        <img src="imagens/foto_perfil.jpg" alt="foto de perfil" class="profile-img">
        <h1>Mateus Ueno</h1>
    </div>
    
    <nav>
        <ul>
            <li><a href="#sobre">Sobre</a></li>
            <li><a href="#projetos">Projetos</a></li>
            <li><a href="#contato">Contato</a></li>
        </ul>
    </nav>
</body>
</html>

/* Reset e configurações gerais */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Roboto, Geneva, Verdana, sans-serif;
}

body {
    background-color: #f5f5f5;
    color: #333;
    line-height: 1.6;
}

a {
    text-decoration: none;
    color: #0077b6;
}

/* Header */
.header_content {
    background: linear-gradient(135deg, #0077b6, #00b4d8);
    color: white;
    text-align: center;
    padding: 2rem;
    position: relative;
}

.profile-img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    border: 3px solid white;
    margin-bottom: 1rem;
    object-fit: cover;
}

/* Navegação */
nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
    padding: 1rem 0;
    background-color: white;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

nav li {
    margin: 0 1rem;
}

nav a {
    color: #333;
    font-weight: 500;
    padding: 0.5rem 1rem;
    border-radius: 4px;
    transition: all 0.3s ease;
}

nav a:hover {
    background-color: #0077b6;
    color: white;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body {
    background-color: #f8f9fa;
    color: #333;
    line-height: 1.6;
}

.header {
    background: linear-gradient(135deg, #6e48aa, #9d50bb);
    color: white;
    text-align: center;
    padding: 2rem 1rem;
    position: relative;
}

.profile-img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
    border: 5px solid white;
    margin-bottom: 1rem;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

.header h1 {
    font-size: 2rem;
    margin-bottom: 0.5rem;
}

.header p {
    font-size: 1.1rem;
    opacity: 0.9;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
    padding: 1.5rem 0;
    background-color: white;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

nav li {
    margin: 0 1.5rem;
}

nav a {
    color: #555;
    font-weight: 600;
    padding: 0.5rem 1rem;
    border-radius: 20px;
    transition: all 0.3s ease;
}

nav a:hover {
    background-color: #6e48aa;
    color: white;
}
