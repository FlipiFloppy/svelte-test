<nav>
    <div calss="nav-container">
        <a href="/" class="nav-logo" title="Back to Homepage">Илья Максимов</a>
        <div calss="nav-links">
            <a href="/about" calss="link">Обо мне</a>
            <a href="/blog" calss="link">Блог</a>
            <a href="/projects" calss="link">Портфолио</a>
            <a href="/contact" calss="link">Контакты</a>
        </div>
    </div>
</nav>

<div class="container">
    <!-- Pages will be injected below -->
    <slot></slot>
    </div>
    <style>
    .container {
    max-width: 1400px;
    margin: 50px auto;
    }
    </style>