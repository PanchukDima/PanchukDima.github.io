<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мои профили | Имя Фамилия</title>
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #3498db;
            --background-color: #f9f9f9;
            --text-color: #333;
            --light-color: #fff;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: var(--background-color);
            color: var(--text-color);
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 2rem;
        }
        
        header {
            text-align: center;
            margin-bottom: 2rem;
            padding-bottom: 1rem;
            border-bottom: 1px solid #eee;
        }
        
        h1 {
            color: var(--primary-color);
            margin-bottom: 0.5rem;
        }
        
        .subtitle {
            color: var(--secondary-color);
            font-weight: normal;
            margin-top: 0;
        }
        
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 5px solid var(--secondary-color);
            margin: 1rem auto;
        }
        
        .bio {
            text-align: center;
            margin-bottom: 2rem;
            font-size: 1.1rem;
        }
        
        .links-section {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
        }
        
        .link-card {
            background: var(--light-color);
            border-radius: 8px;
            padding: 1.5rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
            text-align: center;
        }
        
        .link-card:hover {
            transform: translateY(-5px);
        }
        
        .link-card h3 {
            color: var(--primary-color);
            margin-top: 0;
        }
        
        .link-card a {
            display: inline-block;
            margin-top: 1rem;
            padding: 0.5rem 1rem;
            background-color: var(--secondary-color);
            color: var(--light-color);
            text-decoration: none;
            border-radius: 4px;
            transition: background-color 0.3s;
        }
        
        .link-card a:hover {
            background-color: var(--primary-color);
        }
        
        .icon {
            font-size: 2rem;
            margin-bottom: 1rem;
            color: var(--secondary-color);
        }
        
        footer {
            text-align: center;
            margin-top: 3rem;
            padding-top: 1rem;
            border-top: 1px solid #eee;
            color: #777;
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <div class="container">
        <header>
            <!-- Замените src на путь к вашему фото -->
            <img src="profile.jpg" alt="Мое фото" class="profile-img">
            <h1>Имя Фамилия</h1>
            <h2 class="subtitle">Должность/Специальность</h2>
        </header>
        
        <section class="bio">
            <p>Краткое описание о себе, своих навыках и опыте. 2-3 предложения, которые заинтересуют работодателя.</p>
        </section>
        
        <section class="links-section">
            <div class="link-card">
                <div class="icon">
                    <i class="fab fa-github"></i>
                </div>
                <h3>GitHub</h3>
                <p>Мои проекты и вклад в open source</p>
                <a href="https://github.com/ваш_профиль" target="_blank">Посетить профиль</a>
            </div>
            
            <div class="link-card">
                <div class="icon">
                    <i class="fab fa-linkedin"></i>
                </div>
                <h3>LinkedIn</h3>
                <p>Мое профессиональное резюме</p>
                <a href="https://linkedin.com/in/ваш_профиль" target="_blank">Посетить профиль</a>
            </div>
            
            <div class="link-card">
                <div class="icon">
                    <i class="fas fa-file-alt"></i>
                </div>
                <h3>Резюме</h3>
                <p>Мое полное резюме в PDF</p>
                <a href="resume.pdf" target="_blank">Скачать резюме</a>
            </div>
            
            <div class="link-card">
                <div class="icon">
                    <i class="fab fa-codepen"></i>
                </div>
                <h3>CodePen</h3>
                <p>Мои эксперименты с кодом</p>
                <a href="https://codepen.io/ваш_профиль" target="_blank">Посетить профиль</a>
            </div>
            
            <div class="link-card">
                <div class="icon">
                    <i class="fab fa-stack-overflow"></i>
                </div>
                <h3>Stack Overflow</h3>
                <p>Мои вопросы и ответы</p>
                <a href="https://stackoverflow.com/users/ваш_профиль" target="_blank">Посетить профиль</a>
            </div>
            
            <div class="link-card">
                <div class="icon">
                    <i class="fas fa-envelope"></i>
                </div>
                <h3>Контакты</h3>
                <p>Свяжитесь со мной</p>
                <a href="mailto:ваш@email.com">Написать письмо</a>
            </div>
        </section>
        
        <footer>
            <p>&copy; 2023 Имя Фамилия. Все права защищены.</p>
        </footer>
    </div>
</body>
</html>
