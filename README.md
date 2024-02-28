<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perfil de GitHub</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #f0f0f0;
            padding: 20px;
        }

        .about,
        .languages,
        .code-example {
            margin: 20px;
        }

        .stats img {
            max-width: 100%;
        }

        .python {
            color: #3572A5;
        }
    </style>
</head>
<body>
    <header>
        <h1>¡Hola! Soy Emmanuel 👋</h1>
        <p>Bienvenido a mi perfil de GitHub. Soy estudiante de Ingeniería en Computación con pasión por la programación y el desarrollo de software.</p>
    </header>

    <section class="about">
        <h2>Acerca de mí</h2>
        <ul>
            <li>💻 Estudiante de Ingeniería en Computación.</li>
            <li>🌱 Siempre aprendiendo y explorando nuevas tecnologías.</li>
            <li>🔭 Aspirante a desarrollador backend.</li>
        </ul>
    </section>

    <section class="languages">
        <h2>Lenguajes y Tecnologías</h2>
        <p>No dudes en explorar mis proyectos y contribuciones:</p>
        <div class="stats">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=trexpapu&theme=algolia&hide=html,css&langs_count=4" alt="Top Lenguajes">
        </div>
    </section>

    <section class="code-example">
        <h2>Ejemplo de Código (Python)</h2>
        <pre><code class="python">
def greet(name):
    print(f"¡Hola, {name}!")

greet("Emmanuel")
        </code></pre>
    </section>
</body>
</html>
