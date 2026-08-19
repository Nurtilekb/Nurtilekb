<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <link rel="icon" type="image/svg+xml" href="/nurtilek-logo.svg" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css">
    <link rel="stylesheet" href="styles.css">
    <title>NURTILEK - Flutter Developer</title>
</head>

<body>
    <nav class="navbar">
        <div class="navbar-logo">
            <img src="images/nurtilek-logo.png" class="logo-image">
            <span>NURTILEK</span>
        </div>

        <div class="burger" id="burger">
            <i class="fas fa-bars"></i>
        </div>

        <div class="nav-links" id="navLinks">
            <a href="#home">HOME</a>
            <a href="#projects">PROJECTS</a>
            <a href="#about">ABOUT</a>
            <a href="#contact">CONTACT</a>
        </div>
    </nav>

    <div class="hero hero-bg">
        <div class="hero-content">
            <h1>NURTILEK</h1>
            <p style="color: #00FFD1; font-size: 24px; margin-top: -10px;">✦ Flutter Developer ✦</p>
            <div class="search-container">
                <input type="text" class="search-bar" placeholder="Search projects...">
                <i class="fas fa-search search-icon"></i>
            </div>
        </div>
    </div>

    <div class="club-grid">
        <a href='#project1' class="club-card">
            <img src="images/flutter-app.jpg" class="club-image">
            <div class="club-content">
                <h3 class="club-title">Flutter Mobile App</h3>
                <p class="club-description">Современное мобильное приложение на Flutter с использованием Firebase, Clean Architecture и BLoC паттерна.</p>
            </div>
        </a>

        <a href='#project2' class="club-card">
            <img src="images/firebase-project.jpg" class="club-image">
            <div class="club-content">
                <h3 class="club-title">Firebase Backend</h3>
                <p class="club-description">Полноценный бэкенд с Firebase Authentication, Cloud Firestore, Cloud Functions и Realtime Database.</p>
            </div>
        </a>

        <a href='#project3' class="club-card">
            <img src="images/kotlin-project.jpg" class="club-image">
            <div class="club-content">
                <h3 class="club-title">Kotlin Multiplatform</h3>
                <p class="club-description">Изучение Kotlin Multiplatform для создания кроссплатформенных приложений с общим кодом для Android и iOS.</p>
            </div>
        </a>

        <a href='#project4' class="club-card">
            <img src="images/dart-package.jpg" class="club-image">
            <div class="club-content">
                <h3 class="club-title">Dart Packages</h3>
                <p class="club-description">Разработка собственных Dart и Flutter пакетов для упрощения разработки и повторного использования кода.</p>
            </div>
        </a>

        <a href='#project5' class="club-card">
            <img src="images/architecture.jpg" class="club-image">
            <div class="club-content">
                <h3 class="club-title">Clean Architecture</h3>
                <p class="club-description">Реализация Clean Architecture в Flutter проектах с разделением на domain, data и presentation слои.</p>
            </div>
        </a>
    </div>

    <script src="script.js"></script>
</body>

</html>
