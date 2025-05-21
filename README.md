
<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Green Point СТО</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --green: #00ff88;
      --black: #111;
      --gray: #222;
      --white: #fff;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Roboto', sans-serif;
      background: var(--black);
      color: var(--white);
      line-height: 1.6;
    }

    header {
      background: var(--gray);
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-size: 24px;
      color: var(--green);
      font-weight: bold;
    }

    nav a {
      color: var(--white);
      text-decoration: none;
      margin-left: 20px;
      font-weight: 300;
    }

    nav a:hover {
      color: var(--green);
    }

    .hero {
      background: linear-gradient(to right, #00ff88 0%, #007a4d 100%);
      color: var(--black);
      text-align: center;
      padding: 100px 20px;
    }

    .hero h1 {
      font-size: 48px;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 20px;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .services {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
    }

    .service {
      background: var(--gray);
      padding: 20px;
      margin: 10px;
      flex: 1 1 calc(33% - 40px);
      border-left: 5px solid var(--green);
    }

    footer {
      text-align: center;
      padding: 30px 20px;
      background: var(--gray);
      color: #ccc;
    }

    @media (max-width: 768px) {
      .services {
        flex-direction: column;
      }
      .service {
        flex: 1 1 100%;
      }
    }
  </style>
</head>
<body>

<header>
  <div class="logo">Green Point</div>
  <nav>
    <a href="#about">Про нас</a>
    <a href="#services">Послуги</a>
    <a href="#contact">Контакти</a>
  </nav>
</header>

<div class="hero">
  <h1>Ваше авто — наша турбота</h1>
  <p>Сучасний автосервіс Green Point з інноваційним підходом</p>
</div>

<section id="about">
  <h2>Про нас</h2>
  <p>Green Point — це високотехнологічне СТО з акцентом на якість обслуговування, швидкість виконання робіт та екологічні стандарти. Ми працюємо з усіма типами авто.</p>
</section>

<section id="services">
  <h2>Наші послуги</h2>
  <div class="services">
    <div class="service">
      <h3>Діагностика</h3>
      <p>Комп'ютерна діагностика автомобіля будь-якої складності.</p>
    </div>
  <div class="service">
      <h3>Ремонт гібридних батарей</h3>
      <p>Діагностика та обслуговування гібридних акумуляторів усіх типів.</p>
    </div>
    <div class="service">
      <h3>Ремонт електропроводки</h3>
      <p>Виявлення та усунення несправностей в електросистемах автомобіля.</p>
    </div>
    <div class="service">
      <h3>Кодування автомобіля</h3>
      <p>Налаштування електронних блоків керування для персоналізації функцій авто.</p>
    </div>

    <div class="service">
      <h3>Ремонт двигуна</h3>
      <p>Кваліфікований ремонт бензинових та дизельних двигунів.</p>
    </div>
    <div class="service">
      <h3>Заміна мастила</h3>
      <p>Швидка та якісна заміна мастила і технічних рідин.</p>
     </div>
</section>

<section id="contact">
  <h2>Контакти</h2>
  <p>📍 вул.Поморска 142, м. Щецин</p>
  <p>📞 +48 575 778 886 Артем- </p>
  <p>📞 +48 668 796 944 Сергій- </p>
  <p>📧 info@greenpoint.com.ua</p>
</section>

<footer>
  <p>&copy; 2025 Green Point. Всі права захищено.</p>
</footer>

</body>
</html>
