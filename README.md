<!DOCTYPE html>
<html lang="es">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <meta
        name="description"
        content="Import Global - Productos importados desde China hacia Ecuador."
    >

    <meta
        name="keywords"
        content="importaciones, China, Ecuador, productos, , ropa, belleza, tecnología"
    >

    <meta
        name="author"
        content="Import Global"
    >

    <title>
        Import Global | Importaciones China - Ecuador
    </title>


    <!-- FUENTES -->

    <link
        rel="preconnect"
        href="https://fonts.googleapis.com"
    >

    <link
        rel="preconnect"
        href="https://fonts.gstatic.com"
        crossorigin
    >

    <link
        href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Montserrat:wght@600;700;800&display=swap"
        rel="stylesheet"
    >


    <style>

        /* =====================================================
           CONFIGURACIÓN GENERAL
        ===================================================== */

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }


        :root {

            --primary: #0b1f3a;

            --primary-light: #173b68;

            --accent: #d6a84f;

            --accent-dark: #b78a35;

            --white: #ffffff;

            --light: #f5f7fa;

            --gray: #6b7280;

            --dark: #111827;

            --border: #e5e7eb;

            --success: #16834f;

        }


        html {
            scroll-behavior: smooth;
        }


        body {

            font-family: "Inter", sans-serif;

            color: var(--dark);

            background: #ffffff;

            line-height: 1.6;

        }


        img {
            max-width: 100%;
        }


        button,
        input {
            font-family: inherit;
        }


        button {
            cursor: pointer;
        }


        a {
            text-decoration: none;
            color: inherit;
        }


        .container {

            width: min(1180px, 92%);

            margin: auto;

        }



        /* =====================================================
           HEADER
        ===================================================== */

        header {

            position: sticky;

            top: 0;

            z-index: 1000;

            background: rgba(255, 255, 255, 0.97);

            backdrop-filter: blur(12px);

            border-bottom: 1px solid var(--border);

        }


        .navbar {

            min-height: 82px;

            display: flex;

            align-items: center;

            justify-content: space-between;

            gap: 25px;

        }


        .logo {

            display: flex;

            align-items: center;

            gap: 10px;

            flex-shrink: 0;

        }


        .logo-image {

            width: 60px;

            height: 60px;

            object-fit: contain;

            display: block;

        }


        .logo-text {

            font-family: "Montserrat", sans-serif;

            font-size: 18px;

            font-weight: 800;

            color: var(--primary);

            white-space: nowrap;

            letter-spacing: -0.5px;

        }


        .logo-text span {

            color: var(--accent-dark);

        }


        nav {

            display: flex;

            align-items: center;

            gap: 24px;

        }


        nav a {

            color: #374151;

            font-size: 13px;

            font-weight: 600;

            transition: 0.25s;

        }


        nav a:hover {

            color: var(--accent-dark);

        }


        .cart-button {

            position: relative;

            min-height: 44px;

            padding: 0 18px;

            border-radius: 7px;

            border: 1px solid var(--border);

            background: white;

            color: var(--primary);

            font-weight: 700;

            transition: 0.25s;

        }


        .cart-button:hover {

            border-color: var(--accent);

            box-shadow: 0 5px 15px rgba(0,0,0,.06);

        }


        .cart-count {

            position: absolute;

            top: -8px;

            right: -8px;

            width: 22px;

            height: 22px;

            border-radius: 50%;

            background: var(--accent);

            color: #ffffff;

            display: grid;

            place-items: center;

            font-size: 11px;

            font-weight: 800;

        }



        /* =====================================================
           HERO
        ===================================================== */

        .hero {

            min-height: 620px;

            display: flex;

            align-items: center;

            background:

                linear-gradient(
                    90deg,
                    rgba(5, 19, 39, .97),
                    rgba(8, 29, 55, .88),
                    rgba(8, 29, 55, .38)
                ),

                url("https://images.unsplash.com/photo-1494412574643-ff11b0a5c1c3?auto=format&fit=crop&w=1800&q=85")

                center / cover no-repeat;

        }


        .hero-content {

            max-width: 720px;

            padding: 90px 0;

            color: white;

        }


        .hero-label {

            display: inline-block;

            padding: 7px 14px;

            border: 1px solid rgba(214,168,79,.6);

            border-radius: 30px;

            color: #e8ca82;

            font-size: 10px;

            font-weight: 800;

            letter-spacing: 1.8px;

            text-transform: uppercase;

            margin-bottom: 22px;

        }


        .hero h1 {

            font-family: "Montserrat", sans-serif;

            font-size: clamp(42px, 6vw, 68px);

            line-height: 1.05;

            letter-spacing: -2.5px;

            margin-bottom: 24px;

        }


        .hero h1 span {

            color: var(--accent);

        }


        .hero p {

            max-width: 620px;

            color: #d3dce8;

            font-size: 16px;

            margin-bottom: 32px;

        }


        .hero-buttons {

            display: flex;

            flex-wrap: wrap;

            gap: 12px;

        }


        .btn {

            min-height: 51px;

            padding: 0 26px;

            border-radius: 7px;

            display: inline-flex;

            align-items: center;

            justify-content: center;

            font-size: 13px;

            font-weight: 700;

            transition: .25s;

        }


        .btn-primary {

            background: var(--accent);

            color: #111827;

        }


        .btn-primary:hover {

            background: #e4ba68;

            transform: translateY(-2px);

        }


        .btn-outline {

            border: 1px solid rgba(255,255,255,.4);

            color: white;

        }


        .btn-outline:hover {

            background: white;

            color: var(--primary);

        }



        /* =====================================================
           ESTADÍSTICAS
        ===================================================== */

        .stats {

            margin-top: -55px;

            position: relative;

            z-index: 5;

        }


        .stats-grid {

            background: white;

            border-radius: 12px;

            box-shadow: 0 18px 50px rgba(15,23,42,.12);

            display: grid;

            grid-template-columns: repeat(4, 1fr);

            overflow: hidden;

        }


        .stat {

            padding: 28px 15px;

            text-align: center;

            border-right: 1px solid var(--border);

        }


        .stat:last-child {

            border-right: none;

        }


        .stat strong {

            display: block;

            font-family: "Montserrat", sans-serif;

            color: var(--primary);

            font-size: 21px;

        }


        .stat span {

            color: var(--gray);

            font-size: 11px;

        }



        /* =====================================================
           SECCIONES
        ===================================================== */

        section {

            padding: 90px 0;

        }


        .section-header {

            max-width: 720px;

            margin: 0 auto 45px;

            text-align: center;

        }


        .section-header small {

            color: var(--accent-dark);

            font-size: 10px;

            font-weight: 800;

            letter-spacing: 2px;

            text-transform: uppercase;

        }


        .section-header h2 {

            font-family: "Montserrat", sans-serif;

            color: var(--primary);

            font-size: clamp(30px,4vw,42px);

            line-height: 1.15;

            margin: 9px 0 14px;

        }


        .section-header p {

            color: var(--gray);

            font-size: 14px;

        }



        /* =====================================================
           CATEGORÍAS
        ===================================================== */

        .categories {

            background: #f7f8fa;

        }


        .category-grid {

            display: grid;

            grid-template-columns: repeat(4, 1fr);

            gap: 20px;

        }


        .category-card {

            position: relative;

            padding: 0;

            border: 1px solid #e2e6ec;

            border-radius: 12px;

            background: #ffffff;

            overflow: hidden;

            cursor: pointer;

            text-align: left;

            transition:

                transform .3s ease,

                box-shadow .3s ease,

                border-color .3s ease;

        }


        .category-card:hover {

            transform: translateY(-6px);

            border-color: var(--accent);

            box-shadow: 0 18px 40px rgba(11,31,58,.12);

        }


        .category-card.active {

            border: 2px solid var(--accent);

            box-shadow: 0 15px 35px rgba(11,31,58,.10);

        }


        .category-image {

            width: 100%;

            height: 165px;

            overflow: hidden;

            background: #eef1f5;

        }


        .category-image img {

            width: 100%;

            height: 100%;

            object-fit: cover;

            display: block;

            transition: transform .5s ease;

        }


        .category-card:hover .category-image img {

            transform: scale(1.07);

        }


        .category-info {

            position: relative;

            padding: 17px 18px 19px;

            background: white;

        }


        .category-info h3 {

            margin: 0 0 4px;

            color: var(--primary);

            font-family: "Montserrat", sans-serif;

            font-size: 16px;

            font-weight: 800;

        }


        .category-info span {

            color: #7a8494;

            font-size: 11px;

            font-weight: 500;

        }


        .category-card.active .category-info::after {

            content: "";

            position: absolute;

            right: 18px;

            top: 50%;

            transform: translateY(-50%);

            width: 8px;

            height: 8px;

            border-radius: 50%;

            background: var(--accent);

        }



        /* =====================================================
           PRODUCTOS
        ===================================================== */

        .products-section {

            background: white;

        }


        .catalog-toolbar {

            display: flex;

            align-items: center;

            justify-content: space-between;

            gap: 20px;

            margin-bottom: 30px;

        }


        .catalog-result {

            color: var(--primary);

            font-size: 14px;

            font-weight: 700;

        }


        .search-box {

            width: 340px;

        }


        .search-box input {

            width: 100%;

            height: 46px;

            padding: 0 15px;

            border: 1px solid var(--border);

            border-radius: 7px;

            outline: none;

            color: var(--dark);

            background: white;

        }


        .search-box input:focus {

            border-color: var(--accent);

        }


        .product-grid {

            display: grid;

            grid-template-columns: repeat(4, 1fr);

            gap: 22px;

        }


        .product-card {

            border: 1px solid var(--border);

            border-radius: 10px;

            background: white;

            overflow: hidden;

            transition: .3s;

        }


        .product-card:hover {

            transform: translateY(-5px);

            box-shadow: 0 15px 35px rgba(15,23,42,.10);

        }


        .product-image {

            height: 230px;

            background: #f5f6f8;

            overflow: hidden;

        }


        .product-image img {

            width: 100%;

            height: 100%;

            object-fit: cover;

            transition: .4s;

        }


        .product-card:hover .product-image img {

            transform: scale(1.05);

        }


        .product-info {

            padding: 19px;

        }


        .product-category {

            color: var(--accent-dark);

            font-size: 10px;

            font-weight: 800;

            letter-spacing: 1px;

            text-transform: uppercase;

        }


        .product-info h3 {

            color: var(--primary);

            font-size: 16px;

            margin: 7px 0;

        }


        .product-description {

            min-height: 38px;

            color: var(--gray);

            font-size: 12px;

            margin-bottom: 15px;

        }


        .product-bottom {

            display: flex;

            align-items: center;

            justify-content: space-between;

            gap: 10px;

        }


        .price {

            color: var(--primary);

            font-family: "Montserrat", sans-serif;

            font-size: 18px;

            font-weight: 800;

        }


        .add-button {

            border: none;

            border-radius: 6px;

            padding: 10px 14px;

            background: var(--primary);

            color: white;

            font-size: 11px;

            font-weight: 700;

            transition: .25s;

        }


        .add-button:hover {

            background: var(--accent-dark);

        }



        /* =====================================================
           PROCESO
        ===================================================== */

        .process {

            background: var(--light);

        }


        .process-grid {

            display: grid;

            grid-template-columns: repeat(4,1fr);

            gap: 20px;

        }


        .process-card {

            background: white;

            border: 1px solid var(--border);

            border-radius: 10px;

            padding: 30px 24px;

            transition: .25s;

        }


        .process-card:hover {

            transform: translateY(-4px);

            box-shadow: 0 12px 30px rgba(0,0,0,.06);

        }


        .process-number {

            color: var(--accent-dark);

            font-family: "Montserrat", sans-serif;

            font-weight: 800;

            font-size: 13px;

            margin-bottom: 17px;

        }


        .process-card h3 {

            color: var(--primary);

            font-size: 16px;

            margin-bottom: 8px;

        }


        .process-card p {

            color: var(--gray);

            font-size: 12px;

        }



        /* =====================================================
           NOSOTROS
        ===================================================== */

        .about {

            background: white;

        }


        .about-grid {

            display: grid;

            grid-template-columns: 1fr 1fr;

            gap: 60px;

            align-items: center;

        }


        .about-image {

            height: 470px;

            border-radius: 12px;

            overflow: hidden;

        }


        .about-image img {

            width: 100%;

            height: 100%;

            object-fit: cover;

        }


        .about-content small {

            color: var(--accent-dark);

            font-size: 10px;

            font-weight: 800;

            letter-spacing: 2px;

            text-transform: uppercase;

        }


        .about-content h2 {

            color: var(--primary);

            font-family: "Montserrat", sans-serif;

            font-size: 39px;

            line-height: 1.15;

            margin: 10px 0 20px;

        }


        .about-content p {

            color: var(--gray);

            font-size: 14px;

            margin-bottom: 18px;

        }


        .check-list {

            list-style: none;

            margin-top: 22px;

        }


        .check-list li {

            display: flex;

            align-items: center;

            gap: 9px;

            margin-bottom: 11px;

            color: #374151;

            font-size: 13px;

            font-weight: 600;

        }


        .check {

            width: 20px;

            height: 20px;

            border-radius: 50%;

            background: #e9f5ef;

            color: var(--success);

            display: grid;

            place-items: center;

            font-size: 11px;

        }



        /* =====================================================
           CTA
        ===================================================== */

        .cta {

            background: var(--primary);

            padding: 80px 0;

        }


        .cta-content {

            max-width: 720px;

            margin: auto;

            text-align: center;

            color: white;

        }


        .cta h2 {

            font-family: "Montserrat", sans-serif;

            font-size: 40px;

            line-height: 1.15;

            margin-bottom: 14px;

        }


        .cta p {

            color: #cbd5e1;

            font-size: 14px;

            margin-bottom: 28px;

        }



        /* =====================================================
           FOOTER
        ===================================================== */

        footer {

            background: #071426;

            color: white;

            padding: 60px 0 25px;

        }


        .footer-grid {

            display: grid;

            grid-template-columns: 1.5fr 1fr 1fr 1fr;

            gap: 40px;

            padding-bottom: 40px;

            border-bottom: 1px solid rgba(255,255,255,.1);

        }


        .footer-brand p {

            max-width: 320px;

            color: #94a3b8;

            font-size: 12px;

            margin-top: 14px;

        }


        footer h4 {

            font-size: 13px;

            margin-bottom: 16px;

        }


        footer a {

            display: block;

            color: #94a3b8;

            font-size: 12px;

            margin-bottom: 9px;

            transition: .2s;

        }


        footer a:hover {

            color: white;

        }


        .footer-logo-text {

            color: white;

        }


        .footer-logo-text span {

            color: var(--accent);

        }


        .copyright {

            text-align: center;

            color: #64748b;

            font-size: 11px;

            padding-top: 20px;

        }



        /* =====================================================
           CARRITO
        ===================================================== */

        .cart-overlay {

            position: fixed;

            inset: 0;

            background: rgba(0,0,0,.45);

            z-index: 1999;

            opacity: 0;

            visibility: hidden;

            transition: .3s;

        }


        .cart-overlay.active {

            opacity: 1;

            visibility: visible;

        }


        .cart-sidebar {

            position: fixed;

            top: 0;

            right: -450px;

            width: min(450px, 94%);

            height: 100vh;

            background: white;

            z-index: 2000;

            display: flex;

            flex-direction: column;

            transition: .35s;

            box-shadow: -10px 0 40px rgba(0,0,0,.15);

        }


        .cart-sidebar.active {

            right: 0;

        }


        .cart-header {

            height: 76px;

            padding: 0 23px;

            display: flex;

            align-items: center;

            justify-content: space-between;

            border-bottom: 1px solid var(--border);

        }


        .cart-header h3 {

            color: var(--primary);

            font-family: "Montserrat", sans-serif;

        }


        .close-cart {

            border: 0;

            background: transparent;

            color: var(--gray);

            font-size: 28px;

            cursor: pointer;

        }


        .cart-items {

            flex: 1;

            overflow-y: auto;

            padding: 20px;

        }


        .empty-cart {

            padding: 60px 20px;

            text-align: center;

            color: var(--gray);

            font-size: 13px;

        }


        .cart-item {

            display: grid;

            grid-template-columns: 65px 1fr auto;

            gap: 12px;

            padding: 14px 0;

            border-bottom: 1px solid var(--border);

        }


        .cart-item img {

            width: 65px;

            height: 65px;

            object-fit: cover;

            border-radius: 7px;

        }


        .cart-item h4 {

            color: var(--primary);

            font-size: 12px;

        }


        .cart-item-price {

            color: var(--accent-dark);

            font-size: 12px;

            font-weight: 800;

        }


        .quantity-controls {

            display: flex;

            align-items: center;

            gap: 7px;

            margin-top: 7px;

        }


        .quantity-controls button {

            width: 25px;

            height: 25px;

            border: 1px solid var(--border);

            border-radius: 4px;

            background: white;

        }


        .remove-item {

            border: 0;

            background: transparent;

            color: #9b2c2c;

            font-size: 10px;

            cursor: pointer;

            margin-top: 6px;

        }


        .cart-footer {

            padding: 20px;

            border-top: 1px solid var(--border);

        }


        .cart-total {

            display: flex;

            justify-content: space-between;

            color: var(--primary);

            font-size: 18px;

            font-weight: 800;

            margin-bottom: 15px;

        }


        .whatsapp-order {

            width: 100%;

            height: 51px;

            border: none;

            border-radius: 7px;

            background: var(--success);

            color: white;

            font-weight: 800;

            cursor: pointer;

            transition: .25s;

        }


        .whatsapp-order:hover {

            background: #126b42;

        }



        /* =====================================================
           RESPONSIVE
        ===================================================== */

        @media(max-width: 1050px) {

            .product-grid {

                grid-template-columns: repeat(3,1fr);

            }


            .category-grid {

                grid-template-columns: repeat(3,1fr);

            }


            .process-grid {

                grid-template-columns: repeat(2,1fr);

            }


            nav {

                gap: 15px;

            }

        }



        @media(max-width: 800px) {

            nav {

                display: none;

            }


            .navbar {

                min-height: 72px;

            }


            .hero {

                min-height: 560px;

            }


            .stats-grid {

                grid-template-columns: repeat(2,1fr);

            }


            .stat:nth-child(2) {

                border-right: none;

            }


            .product-grid {

                grid-template-columns: repeat(2,1fr);

            }


            .catalog-toolbar {

                flex-direction: column;

                align-items: stretch;

            }


            .search-box {

                width: 100%;

            }


            .about-grid {

                grid-template-columns: 1fr;

                gap: 35px;

            }


            .about-image {

                height: 340px;

            }


            .footer-grid {

                grid-template-columns: repeat(2,1fr);

            }

        }



        @media(max-width: 560px) {

            section {

                padding: 70px 0;

            }


            .hero {

                min-height: 560px;

            }


            .hero h1 {

                font-size: 40px;

                letter-spacing: -1.5px;

            }


            .hero-buttons {

                flex-direction: column;

            }


            .hero-buttons .btn {

                width: 100%;

            }


            .product-grid {

                grid-template-columns: 1fr;

            }


            .category-grid {

                grid-template-columns: repeat(2,1fr);

                gap: 12px;

            }


            .category-image {

                height: 125px;

            }


            .category-info {

                padding: 13px;

            }


            .category-info h3 {

                font-size: 14px;

            }


            .category-info span {

                font-size: 9px;

            }


            .process-grid {

                grid-template-columns: 1fr;

            }


            .footer-grid {

                grid-template-columns: 1fr;

            }


            .logo-image {

                width: 50px;

                height: 50px;

            }


            .logo-text {

                font-size: 15px;

            }

        }

    </style>

</head>



<body>


    <!-- =====================================================
         HEADER
    ===================================================== -->

    <header>

        <div class="container navbar">


            <!-- LOGO -->

            <a
                href="#inicio"
                class="logo"
            >

                                

                <div class="logo-text">

                    IMPORT
                    <span>GLOBAL</span>

                </div>

            </a>


            <!-- MENÚ -->

            <nav>

                <a href="#inicio">
                    Inicio
                </a>

                <a href="#categorias">
                    Categorías
                </a>

                <a href="#productos">
                    Productos
                </a>

                <a href="#nosotros">
                    Nosotros
                </a>

                <a href="#proceso">
                    Cómo funciona
                </a>

                <a href="#contacto">
                    Contacto
                </a>

            </nav>


            <!-- CARRITO -->

            <button
                class="cart-button"
                onclick="openCart()"
            >

                Carrito

                <span
                    class="cart-count"
                    id="cartCount"
                >
                    0
                </span>

            </button>

        </div>

    </header>



    <!-- =====================================================
         HERO
    ===================================================== -->

    <section
        class="hero"
        id="inicio"
    >

        <div class="container">

            <div class="hero-content">


                <div class="hero-label">

                    IMPORTACIONES
                    CHINA - ECUADOR

                </div>


                <h1>

                    Productos de calidad
                    directamente para

                    <span>
                        Ecuador
                    </span>

                </h1>


                <p>

                    Descubre productos seleccionados de diferentes
                    categorías y realiza tus pedidos de forma rápida,
                    sencilla y personalizada.

                </p>


                <div class="hero-buttons">


                    <a
                        href="#categorias"
                        class="btn btn-primary"
                    >

                        Explorar categorías

                    </a>


                    <a
                        href="#productos"
                        class="btn btn-outline"
                    >

                        Ver productos

                    </a>


                </div>

            </div>

        </div>

    </section>



    <!-- =====================================================
         ESTADÍSTICAS
    ===================================================== -->

    <div class="stats">

        <div class="container">

            <div class="stats-grid">


                <div class="stat">

                    <strong>
                        China
                    </strong>

                    <span>
                        Origen de productos
                    </span>

                </div>


                <div class="stat">

                    <strong>
                        Ecuador
                    </strong>

                    <span>
                        Destino de importación
                    </span>

                </div>


                <div class="stat">

                    <strong>
                        Directo
                    </strong>

                    <span>
                        Atención personalizada
                    </span>

                </div>


                <div class="stat">

                    <strong>
                        WhatsApp
                    </strong>

                    <span>
                        Pedidos y consultas
                    </span>

                </div>


            </div>

        </div>

    </div>



    <!-- =====================================================
         CATEGORÍAS
    ===================================================== -->

    <section
        class="categories"
        id="categorias"
    >

        <div class="container">


            <div class="section-header">

                <small>
                    Categorías
                </small>

                <h2>
                    Explora nuestras categorías
                </h2>

                <p>

                    Encuentra productos seleccionados para tu ,
                    vehículo, negocio y uso personal.

                </p>

            </div>



            <div class="category-grid">


                <!-- TODOS -->

                <button
                    class="category-card active"
                    onclick="filterCategory('Todos', this)"
                >

                    <div class="category-image">

                        <img
                            src="https://images.unsplash.com/photo-1607082348824-0a96f2a4b9da?auto=format&fit=crop&w=600&q=85"
                            alt="Todos los productos"
                         loading="lazy" decoding="async">

                    </div>

                    <div class="category-info">

                        <h3>
                            Todos
                        </h3>

                        <span>
                            Ver catálogo
                        </span>

                    </div>

                </button>



                <!-- HOGAR -->

                <button
                    class="category-card"
                    onclick="filterCategory('Hogar', this)"
                >

                    <div class="category-image">

                        <img
                            src="https://images.unsplash.com/photo-1583947215259-38e31be8751f?auto=format&fit=crop&w=600&q=85"
                            alt="Hogar"
                         loading="lazy" decoding="async">

                    </div>

                    <div class="category-info">

                        <h3>
                            Hogar
                        </h3>

                        <span>
                            Productos para tu hogar
                        </span>

                    </div>

                </button>



                <!-- VEHÍCULOS -->

                <button
                    class="category-card"
                    onclick="filterCategory('Vehículos', this)"
                >

                    <div class="category-image">

                        <img
                            src="https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=600&q=85"
                            alt="Vehículos"
                         loading="lazy" decoding="async">

                    </div>

                    <div class="category-info">

                        <h3>
                            Vehículos
                        </h3>

                        <span>
                            Accesorios y más
                        </span>

                    </div>

                </button>



                <!-- ROPA -->

                <button
                    class="category-card"
                    onclick="filterCategory('Ropa', this)"
                >

                    <div class="category-image">

                        <img
                            src="https://images.unsplash.com/photo-1445205170230-053b83016050?auto=format&fit=crop&w=600&q=85"
                            alt="Ropa"
                         loading="lazy" decoding="async">

                    </div>

                    <div class="category-info">

                        <h3>
                            Ropa
                        </h3>

                        <span>
                            Moda y accesorios
                        </span>

                    </div>

                </button>



                <!-- BELLEZA -->

                <button
                    class="category-card"
                    onclick="filterCategory('Belleza', this)"
                >

                    <div class="category-image">

                        <img
                            src="https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&w=600&q=85"
                            alt="Belleza"
                         loading="lazy" decoding="async">

                    </div>

                    <div class="category-info">

                        <h3>
                            Belleza
                        </h3>

                        <span>
                            Cuidado personal
                        </span>

                    </div>

                </button>



                <!-- COMEDOR -->

                <button
                    class="category-card"
                    onclick="filterCategory('Comedor', this)"
                >

                    <div class="category-image">

                        <img
                            src="https://images.unsplash.com/photo-1603199506016-b9a594b593c0?auto=format&fit=crop&w=600&q=85"
                            alt="Comedor"
                         loading="lazy" decoding="async">

                    </div>

                    <div class="category-info">

                        <h3>
                            Comedor
                        </h3>

                        <span>
                            Cocina y comedor
                        </span>

                    </div>

                </button>



                <!-- TECNOLOGÍA -->

                <button
                    class="category-card"
                    onclick="filterCategory('Tecnología', this)"
                >

                    <div class="category-image">

                        <img
                            src="https://images.unsplash.com/photo-1498049794561-7780e7231661?auto=format&fit=crop&w=600&q=85"
                            alt="Tecnología"
                         loading="lazy" decoding="async">

                    </div>

                    <div class="category-info">

                        <h3>
                            Tecnología
                        </h3>

                        <span>
                            Electrónica y accesorios
                        </span>

                    </div>

                </button>



                <!-- HERRAMIENTAS -->

                <button
                    class="category-card"
                    onclick="filterCategory('Herramientas', this)"
                >

                    <div class="category-image">

                        <img
                            src="https://images.unsplash.com/photo-1581147036324-c17ac41a2b83?auto=format&fit=crop&w=600&q=85"
                            alt="Herramientas"
                         loading="lazy" decoding="async">

                    </div>

                    <div class="category-info">

                        <h3>
                            Herramientas
                        </h3>

                        <span>
                            Equipos y herramientas
                        </span>

                    </div>

                </button>



                <!-- DEPORTES -->

                <button
                    class="category-card"
                    onclick="filterCategory('Deportes', this)"
                >

                    <div class="category-image">

                        <img
                            src="https://images.unsplash.com/photo-1461896836934-ffe607ba8211?auto=format&fit=crop&w=600&q=85"
                            alt="Deportes"
                         loading="lazy" decoding="async">

                    </div>

                    <div class="category-info">

                        <h3>
                            Deportes
                        </h3>

                        <span>
                            Fitness y deporte
                        </span>

                    </div>

                </button>



                <!-- BAÑO -->

                <button
                    class="category-card"
                    onclick="filterCategory('Baño', this)"
                >
                    <div class="category-image">
                        <img src="https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=600&q=85" alt="Baño" loading="lazy" decoding="async">
                    </div>
                    <div class="category-info">
                        <h3>Baño</h3>
                        <span>Accesorios y organización</span>
                    </div>
                </button>


                <!-- LIMPIEZA -->

                <button
                    class="category-card"
                    onclick="filterCategory('Limpieza', this)"
                >
                    <div class="category-image">
                        <img src="https://images.unsplash.com/photo-1583947215259-38e31be8751f?auto=format&fit=crop&w=600&q=85" alt="Limpieza" loading="lazy" decoding="async">
                    </div>
                    <div class="category-info">
                        <h3>Limpieza</h3>
                        <span>Productos para limpieza</span>
                    </div>
                </button>


                <!-- JUGUETERÍA -->

                <button
                    class="category-card"
                    onclick="filterCategory('Juguetería', this)"
                >
                    <div class="category-image">
                        <img src="https://images.unsplash.com/photo-1566576912321-d58ddd7a6088?auto=format&fit=crop&w=600&q=85" alt="Juguetería" loading="lazy" decoding="async">
                    </div>
                    <div class="category-info">
                        <h3>Juguetería</h3>
                        <span>Juegos y entretenimiento</span>
                    </div>
                </button>


                <!-- JARDÍN Y EXTERIOR -->

                <button
                    class="category-card"
                    onclick="filterCategory('Jardín y Exterior', this)"
                >
                    <div class="category-image">
                        <img src="https://images.unsplash.com/photo-1416879595882-3373a0480b5b?auto=format&fit=crop&w=600&q=85" alt="Jardín y Exterior" loading="lazy" decoding="async">
                    </div>
                    <div class="category-info">
                        <h3>Jardín y Exterior</h3>
                        <span>Jardín, patio y exterior</span>
                    </div>
                </button>


                <!-- OFICINA Y NEGOCIO -->

                <button
                    class="category-card"
                    onclick="filterCategory('Oficina y Negocio', this)"
                >
                    <div class="category-image">
                        <img src="https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=600&q=85" alt="Oficina y Negocio" loading="lazy" decoding="async">
                    </div>
                    <div class="category-info">
                        <h3>Oficina y Negocio</h3>
                        <span>Organización y trabajo</span>
                    </div>
                </button>


                <!-- ACCESORIOS Y OTROS -->

                <button
                    class="category-card"
                    onclick="filterCategory('Accesorios y Otros', this)"
                >
                    <div class="category-image">
                        <img src="https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?auto=format&fit=crop&w=600&q=85" alt="Accesorios y Otros" loading="lazy" decoding="async">
                    </div>
                    <div class="category-info">
                        <h3>Accesorios y Otros</h3>
                        <span>Accesorios de uso diario</span>
                    </div>
                </button>


            </div>

        </div>

    </section>



    <!-- =====================================================
         PRODUCTOS
    ===================================================== -->

    <section
        class="products-section"
        id="productos"
    >

        <div class="container">


            <div class="section-header">

                <small>
                    Catálogo
                </small>

                <h2>
                    Nuestros productos
                </h2>

                <p>

                    Selecciona los productos que deseas,
                    agrégalos al carrito y envía tu pedido
                    directamente por WhatsApp.

                </p>

            </div>



            <div class="catalog-toolbar">


                <div
                    class="catalog-result"
                    id="productResults"
                >

                    Todos los productos

                </div>


                <div class="search-box">

                    <input
                        type="text"
                        id="searchInput"
                        placeholder="Buscar productos..."
                        onkeyup="searchProducts()"
                    >

                </div>


            </div>



            <div
                class="product-grid"
                id="productGrid"
            >

                <!-- Los productos se generan automáticamente desde JavaScript. -->

            </div>

        </div>

    </section>



    <!-- =====================================================
         PROCESO
    ===================================================== -->

    <section
        class="process"
        id="proceso"
    >

        <div class="container">


            <div class="section-header">

                <small>
                    Nuestro proceso
                </small>

                <h2>
                    Compra de forma sencilla
                </h2>

                <p>

                    Selecciona tus productos y nosotros
                    nos encargamos de atender tu solicitud.

                </p>

            </div>


            <div class="process-grid">


                <div class="process-card">

                    <div class="process-number">
                        01
                    </div>

                    <h3>
                        Selecciona tus productos
                    </h3>

                    <p>

                        Explora nuestras categorías y agrega
                        al carrito los productos que deseas.

                    </p>

                </div>


                <div class="process-card">

                    <div class="process-number">
                        02
                    </div>

                    <h3>
                        Revisa tu pedido
                    </h3>

                    <p>

                        Comprueba las cantidades, productos
                        y valor total de tu pedido.

                    </p>

                </div>


                <div class="process-card">

                    <div class="process-number">
                        03
                    </div>

                    <h3>
                        Envía el pedido
                    </h3>

                    <p>

                        El sistema prepara automáticamente
                        tu pedido para enviarlo por WhatsApp.

                    </p>

                </div>


                <div class="process-card">

                    <div class="process-number">
                        04
                    </div>

                    <h3>
                        Coordinamos contigo
                    </h3>

                    <p>

                        Nuestro equipo se comunicará contigo
                        para confirmar disponibilidad y entrega.

                    </p>

                </div>


            </div>

        </div>

    </section>



    <!-- =====================================================
         NOSOTROS
    ===================================================== -->

    <section
        class="about"
        id="nosotros"
    >

        <div class="container about-grid">


            <div class="about-image">

                <img
                    src="https://images.unsplash.com/photo-1566576912321-d58ddd7a6088?auto=format&fit=crop&w=1200&q=85"
                    alt="Import Global"
                 loading="lazy" decoding="async">

            </div>


            <div class="about-content">

                <small>
                    Sobre Import Global
                </small>

                <h2>
                    Una conexión entre China y Ecuador
                </h2>


                <p>

                    En Import Global trabajamos para facilitar
                    el acceso a productos provenientes de China
                    para clientes, negocios y emprendimientos
                    en Ecuador.

                </p>


                <p>

                    Nuestro objetivo es ofrecer una experiencia
                    de compra sencilla, clara y personalizada.

                </p>


                <ul class="check-list">


                    <li>

                        <span class="check">
                            ✓
                        </span>

                        Atención personalizada

                    </li>


                    <li>

                        <span class="check">
                            ✓
                        </span>

                        Productos de diferentes categorías

                    </li>


                    <li>

                        <span class="check">
                            ✓
                        </span>

                        Pedidos directamente por WhatsApp

                    </li>


                    <li>

                        <span class="check">
                            ✓
                        </span>

                        Soluciones para negocios y emprendimientos

                    </li>


                </ul>

            </div>

        </div>

    </section>



    <!-- =====================================================
         CTA
    ===================================================== -->

    <section class="cta">

        <div class="container">


            <div class="cta-content">

                <h2>
                    ¿Buscas un producto específico?
                </h2>

                <p>

                    Escríbenos directamente por WhatsApp
                    y cuéntanos qué producto necesitas.

                </p>


                <a
                    href="https://wa.me/593959237131?text=Hola%20Import%20Global,%20quiero%20consultar%20sobre%20un%20producto."
                    target="_blank"
                    class="btn btn-primary"
                >

                    Contactar por WhatsApp

                </a>

            </div>

        </div>

    </section>



    <!-- =====================================================
         FOOTER
    ===================================================== -->

    <footer
        id="contacto"
    >

        <div class="container">


            <div class="footer-grid">


                <!-- MARCA -->

                <div class="footer-brand">


                    <div class="logo">

                        <div class="logo-text footer-logo-text">

                            IMPORT
                            <span>GLOBAL</span>

                        </div>

                    </div>


                    <p>

                        Importación de productos desde China
                        hacia Ecuador. Productos para hogares,
                        negocios y emprendimientos.

                    </p>

                </div>



                <!-- EMPRESA -->

                <div>

                    <h4>
                        Empresa
                    </h4>

                    <a href="#nosotros">
                        Nosotros
                    </a>

                    <a href="#proceso">
                        Cómo funciona
                    </a>

                    <a href="#productos">
                        Productos
                    </a>

                    <a href="#categorias">
                        Categorías
                    </a>

                </div>



                <!-- CATEGORÍAS -->

                <div>

                    <h4>
                        Categorías
                    </h4>

                    <a href="#categorias">
                        Hogar
                    </a>

                    <a href="#categorias">
                        Vehículos
                    </a>

                    <a href="#categorias">
                        Ropa
                    </a>

                    <a href="#categorias">
                        Belleza
                    </a>

                    <a href="#categorias">
                        Tecnología
                    </a>

                </div>



                <!-- CONTACTO -->

                <div>

                    <h4>
                        Contacto
                    </h4>


                    <a
                        href="https://wa.me/593959237131"
                        target="_blank"
                    >

                        WhatsApp:
                        0959237131

                    </a>


                    <a
                        href="mailto:ventas@importglobal.com"
                    >

                        ventas@importglobal.com

                    </a>


                    <a href="#">
                        Ecuador
                    </a>

                </div>


            </div>


            <div class="copyright">

                © 2026 Import Global.
                Todos los derechos reservados.

            </div>


        </div>

    </footer>



    <!-- =====================================================
         CARRITO
    ===================================================== -->

    <div
        class="cart-overlay"
        id="cartOverlay"
        onclick="closeCart()"
    ></div>


    <aside
        class="cart-sidebar"
        id="cartSidebar"
    >


        <div class="cart-header">

            <h3>
                Tu pedido
            </h3>


            <button
                class="close-cart"
                onclick="closeCart()"
            >

                ×

            </button>

        </div>



        <div
            class="cart-items"
            id="cartItems"
        ></div>



        <div class="cart-footer">


            <div class="cart-total">

                <span>
                    Total
                </span>

                <span id="cartTotal">
                    $0.00
                </span>

            </div>


            <button
                class="whatsapp-order"
                onclick="sendOrderToWhatsApp()"
            >

                Realizar pedido por WhatsApp

            </button>


        </div>


    </aside>



    <!-- =====================================================
         JAVASCRIPT
    ===================================================== -->

    <script>


        /* =====================================================
           WHATSAPP
        ===================================================== */

        const WHATSAPP_NUMBER =
            "593959237131";



        /* =====================================================
           PRODUCTOS
        ===================================================== */

        const products = [
            {
                id: 1,
                name: "Lámpara LED",
                category: "Hogar",
                price: 24.90,
                description: "Iluminación moderna para hogares y negocios.",
                image: "https://images.unsplash.com/photo-1507473885765-e6ed057f782c?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 2,
                name: "Organizador multifuncional",
                category: "Hogar",
                price: 18.50,
                description: "Organización práctica para diferentes espacios.",
                image: "https://images.unsplash.com/photo-1586023492125-27b2c045efd7?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 3,
                name: "Camiseta casual",
                category: "Ropa",
                price: 14.90,
                description: "Diseño moderno para uso diario.",
                image: "https://images.unsplash.com/photo-1521572163474-6864f9cf17ab?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 4,
                name: "Chaqueta urbana",
                category: "Ropa",
                price: 39.90,
                description: "Chaqueta moderna para diferentes ocasiones.",
                image: "https://images.unsplash.com/photo-1551028719-00167b16eac5?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 5,
                name: "Set de belleza",
                category: "Belleza",
                price: 22.90,
                description: "Accesorios seleccionados para cuidado .",
                image: "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 6,
                name: "Organizador de maquillaje",
                category: "Belleza",
                price: 19.90,
                description: "Organizador elegante para cosméticos y accesorios.",
                image: "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 7,
                name: "Vajilla blanca",
                category: "Comedor",
                price: 39.90,
                description: "Vajilla elegante para hogares y restaurantes.",
                image: "https://images.unsplash.com/photo-1610701596007-11502861dcfa?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 8,
                name: "Set de cocina",
                category: "Comedor",
                price: 32.00,
                description: "Accesorios prácticos para cocina y comedor.",
                image: "https://images.unsplash.com/photo-1556911220-e15b29be8c8f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 9,
                name: "Accesorios tecnológicos",
                category: "Tecnología",
                price: 15.90,
                description: "Accesorios para dispositivos electrónicos.",
                image: "https://images.unsplash.com/photo-1498049794561-7780e7231661?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 10,
                name: "Audífonos inalámbricos",
                category: "Tecnología",
                price: 29.90,
                description: "Diseño moderno y conectividad inalámbrica.",
                image: "https://images.unsplash.com/photo-1505740420928-5e560c06d30e?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 11,
                name: "Soporte para celular",
                category: "Vehículos",
                price: 12.90,
                description: "Accesorio práctico para vehículos.",
                image: "https://images.unsplash.com/photo-1549317661-bd32c8ce0db2?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 12,
                name: "Kit de herramientas",
                category: "Herramientas",
                price: 35.90,
                description: "Herramientas para trabajos domésticos.",
                image: "https://images.unsplash.com/photo-1581147036324-c17ac41a2b83?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 13,
                name: "Accesorios deportivos",
                category: "Deportes",
                price: 19.90,
                description: "Productos para entrenamiento y actividad física.",
                image: "https://images.unsplash.com/photo-1461896836934-ffe607ba8211?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 14,
                name: "Mancuernas",
                category: "Deportes",
                price: 28.90,
                description: "Equipamiento para entrenamiento en casa.",
                image: "https://images.unsplash.com/photo-1581009146145-b5ef050c2e1e?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 15,
                name: "Espejo decorativo",
                category: "Hogar",
                price: 29.90,
                description: "Espejo moderno para sala, dormitorio o recibidor.",
                image: "https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 16,
                name: "Reloj de pared",
                category: "Hogar",
                price: 18.90,
                description: "Reloj decorativo para diferentes espacios del hogar.",
                image: "https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 17,
                name: "Cojines decorativos",
                category: "Hogar",
                price: 12.50,
                description: "Cojines cómodos para renovar la decoración.",
                image: "https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 18,
                name: "Cortinas modernas",
                category: "Hogar",
                price: 24.90,
                description: "Cortinas elegantes para sala y dormitorio.",
                image: "https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 19,
                name: "Alfombra decorativa",
                category: "Hogar",
                price: 34.90,
                description: "Alfombra suave para complementar tus espacios.",
                image: "https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 20,
                name: "Lámpara de mesa",
                category: "Hogar",
                price: 21.90,
                description: "Iluminación práctica y elegante para interiores.",
                image: "https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 21,
                name: "Lámpara de noche",
                category: "Hogar",
                price: 17.90,
                description: "Lámpara compacta para dormitorio y lectura.",
                image: "https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 22,
                name: "Estante organizador",
                category: "Hogar",
                price: 31.90,
                description: "Estante funcional para libros y accesorios.",
                image: "https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 23,
                name: "Caja organizadora",
                category: "Hogar",
                price: 9.90,
                description: "Caja práctica para guardar objetos del hogar.",
                image: "https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 24,
                name: "Perchero multiuso",
                category: "Hogar",
                price: 16.90,
                description: "Perchero funcional para ropa y accesorios.",
                image: "https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 25,
                name: "Canasto de ropa",
                category: "Hogar",
                price: 22.90,
                description: "Canasto amplio para organizar prendas.",
                image: "https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 26,
                name: "Dispensador de jabón",
                category: "Hogar",
                price: 8.90,
                description: "Dispensador moderno para baño o cocina.",
                image: "https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 27,
                name: "Set de toallas",
                category: "Hogar",
                price: 26.90,
                description: "Set de toallas suaves para uso diario.",
                image: "https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 28,
                name: "Cesto de basura",
                category: "Hogar",
                price: 14.90,
                description: "Cesto práctico para diferentes ambientes.",
                image: "https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 29,
                name: "Humidificador",
                category: "Hogar",
                price: 32.90,
                description: "Humidificador compacto para ambientes interiores.",
                image: "https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 30,
                name: "Ventilador portátil",
                category: "Hogar",
                price: 27.90,
                description: "Ventilador compacto para uso doméstico.",
                image: "https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 31,
                name: "Aspiradora manual",
                category: "Hogar",
                price: 39.90,
                description: "Aspiradora práctica para limpieza rápida.",
                image: "https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 32,
                name: "Manta decorativa",
                category: "Hogar",
                price: 25.90,
                description: "Manta suave para sala o dormitorio.",
                image: "https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 33,
                name: "Organizador de zapatos",
                category: "Hogar",
                price: 28.90,
                description: "Organizador para mantener el calzado ordenado.",
                image: "https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 34,
                name: "Mesa auxiliar",
                category: "Hogar",
                price: 44.90,
                description: "Mesa compacta para sala, dormitorio u oficina.",
                image: "https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 35,
                name: "Cargador USB para auto",
                category: "Vehículos",
                price: 14.90,
                description: "Cargador compacto para dispositivos móviles.",
                image: "https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 36,
                name: "Aspiradora para auto",
                category: "Vehículos",
                price: 34.90,
                description: "Aspiradora portátil para limpieza interior.",
                image: "https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 37,
                name: "Compresor portátil",
                category: "Vehículos",
                price: 49.90,
                description: "Compresor compacto para inflar neumáticos.",
                image: "https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 38,
                name: "Inflador digital",
                category: "Vehículos",
                price: 39.90,
                description: "Inflador con control de presión para neumáticos.",
                image: "https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 39,
                name: "Cámara de reversa",
                category: "Vehículos",
                price: 45.90,
                description: "Accesorio para mejorar la visibilidad al estacionar.",
                image: "https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 40,
                name: "Luces LED para auto",
                category: "Vehículos",
                price: 29.90,
                description: "Iluminación LED para diferentes aplicaciones vehiculares.",
                image: "https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 41,
                name: "Kit de limpieza automotriz",
                category: "Vehículos",
                price: 24.90,
                description: "Accesorios para limpieza exterior e interior.",
                image: "https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 42,
                name: "Paños de microfibra",
                category: "Vehículos",
                price: 11.90,
                description: "Paños absorbentes para cuidado del vehículo.",
                image: "https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 43,
                name: "Organizador para asiento",
                category: "Vehículos",
                price: 21.90,
                description: "Organizador para mantener accesorios ordenados.",
                image: "https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 44,
                name: "Funda para volante",
                category: "Vehículos",
                price: 15.90,
                description: "Funda cómoda para proteger el volante.",
                image: "https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 45,
                name: "Funda para asiento",
                category: "Vehículos",
                price: 32.90,
                description: "Protección práctica para asientos del vehículo.",
                image: "https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 46,
                name: "Parasol para parabrisas",
                category: "Vehículos",
                price: 18.90,
                description: "Protector contra el sol para el interior del auto.",
                image: "https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 47,
                name: "Aromatizante automotriz",
                category: "Vehículos",
                price: 7.90,
                description: "Aromatizante para mantener un ambiente agradable.",
                image: "https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 48,
                name: "Kit de emergencia vehicular",
                category: "Vehículos",
                price: 42.90,
                description: "Accesorios básicos para situaciones imprevistas.",
                image: "https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 49,
                name: "Cable de batería",
                category: "Vehículos",
                price: 27.90,
                description: "Cable para asistencia de arranque vehicular.",
                image: "https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 50,
                name: "Soporte magnético para celular",
                category: "Vehículos",
                price: 16.90,
                description: "Soporte práctico para navegación y llamadas.",
                image: "https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 51,
                name: "Limpiador de tablero",
                category: "Vehículos",
                price: 9.90,
                description: "Producto para mantener el tablero limpio.",
                image: "https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 52,
                name: "Cepillo para llantas",
                category: "Vehículos",
                price: 12.90,
                description: "Cepillo resistente para limpieza de ruedas.",
                image: "https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 53,
                name: "Medidor de presión",
                category: "Vehículos",
                price: 13.90,
                description: "Medidor portátil para revisar neumáticos.",
                image: "https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 54,
                name: "Kit de herramientas para auto",
                category: "Vehículos",
                price: 54.90,
                description: "Herramientas básicas para mantenimiento vehicular.",
                image: "https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 55,
                name: "Polo básico",
                category: "Ropa",
                price: 16.90,
                description: "Prenda versátil para uso diario.",
                image: "https://images.unsplash.com/photo-1445205170230-053b83016050?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 56,
                name: "Blusa casual",
                category: "Ropa",
                price: 22.90,
                description: "Diseño moderno para diferentes ocasiones.",
                image: "https://images.unsplash.com/photo-1445205170230-053b83016050?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 57,
                name: "Pantalón casual",
                category: "Ropa",
                price: 29.90,
                description: "Pantalón cómodo para uso diario.",
                image: "https://images.unsplash.com/photo-1445205170230-053b83016050?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 58,
                name: "Jean clásico",
                category: "Ropa",
                price: 34.90,
                description: "Jean versátil de estilo atemporal.",
                image: "https://images.unsplash.com/photo-1445205170230-053b83016050?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 59,
                name: "Vestido casual",
                category: "Ropa",
                price: 32.90,
                description: "Vestido cómodo para salidas y eventos.",
                image: "https://images.unsplash.com/photo-1445205170230-053b83016050?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 60,
                name: "Sudadera unisex",
                category: "Ropa",
                price: 31.90,
                description: "Prenda cálida y cómoda para uso diario.",
                image: "https://images.unsplash.com/photo-1445205170230-053b83016050?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 61,
                name: "Hoodie moderno",
                category: "Ropa",
                price: 36.90,
                description: "Sudadera con capucha de estilo urbano.",
                image: "https://images.unsplash.com/photo-1445205170230-053b83016050?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 62,
                name: "Short deportivo",
                category: "Ropa",
                price: 18.90,
                description: "Short ligero para actividad física.",
                image: "https://images.unsplash.com/photo-1445205170230-053b83016050?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 63,
                name: "Pantalón deportivo",
                category: "Ropa",
                price: 25.90,
                description: "Pantalón cómodo para entrenamiento y descanso.",
                image: "https://images.unsplash.com/photo-1445205170230-053b83016050?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 64,
                name: "Leggings deportivos",
                category: "Ropa",
                price: 21.90,
                description: "Leggings elásticos para ejercicio y uso casual.",
                image: "https://images.unsplash.com/photo-1445205170230-053b83016050?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 65,
                name: "Camisa formal",
                category: "Ropa",
                price: 29.90,
                description: "Camisa elegante para ocasiones especiales.",
                image: "https://images.unsplash.com/photo-1445205170230-053b83016050?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 66,
                name: "Polo deportivo",
                category: "Ropa",
                price: 19.90,
                description: "Polo ligero para actividades y uso diario.",
                image: "https://images.unsplash.com/photo-1445205170230-053b83016050?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 67,
                name: "Chaleco casual",
                category: "Ropa",
                price: 33.90,
                description: "Chaleco moderno para combinar diferentes looks.",
                image: "https://images.unsplash.com/photo-1445205170230-053b83016050?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 68,
                name: "Abrigo ligero",
                category: "Ropa",
                price: 49.90,
                description: "Abrigo práctico para clima fresco.",
                image: "https://images.unsplash.com/photo-1445205170230-053b83016050?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 69,
                name: "Falda casual",
                category: "Ropa",
                price: 24.90,
                description: "Falda versátil para diferentes ocasiones.",
                image: "https://images.unsplash.com/photo-1445205170230-053b83016050?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 70,
                name: "Pijama",
                category: "Ropa",
                price: 27.90,
                description: "Conjunto cómodo para descansar.",
                image: "https://images.unsplash.com/photo-1445205170230-053b83016050?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 71,
                name: "Ropa interior básica",
                category: "Ropa",
                price: 15.90,
                description: "Prendas cómodas para uso diario.",
                image: "https://images.unsplash.com/photo-1445205170230-053b83016050?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 72,
                name: "Medias deportivas",
                category: "Ropa",
                price: 9.90,
                description: "Medias cómodas para entrenamiento.",
                image: "https://images.unsplash.com/photo-1445205170230-053b83016050?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 73,
                name: "Gorra urbana",
                category: "Ropa",
                price: 12.90,
                description: "Accesorio moderno para complementar tu estilo.",
                image: "https://images.unsplash.com/photo-1445205170230-053b83016050?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 74,
                name: "Bufanda",
                category: "Ropa",
                price: 14.90,
                description: "Accesorio suave para clima fresco.",
                image: "https://images.unsplash.com/photo-1445205170230-053b83016050?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 75,
                name: "Cepillo facial eléctrico",
                category: "Belleza",
                price: 29.90,
                description: "Limpieza facial práctica para el cuidado diario.",
                image: "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 76,
                name: "Rodillo facial",
                category: "Belleza",
                price: 16.90,
                description: "Accesorio para rutina de cuidado facial.",
                image: "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 77,
                name: "Esponjas de maquillaje",
                category: "Belleza",
                price: 11.90,
                description: "Set de esponjas para aplicación uniforme.",
                image: "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 78,
                name: "Brochas de maquillaje",
                category: "Belleza",
                price: 24.90,
                description: "Set de brochas para diferentes productos cosméticos.",
                image: "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 79,
                name: "Espejo con luz LED",
                category: "Belleza",
                price: 34.90,
                description: "Espejo compacto con iluminación para maquillaje.",
                image: "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 80,
                name: "Organizador acrílico",
                category: "Belleza",
                price: 27.90,
                description: "Organizador transparente para cosméticos.",
                image: "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 81,
                name: "Neceser de viaje",
                category: "Belleza",
                price: 18.90,
                description: "Estuche práctico para productos personales.",
                image: "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 82,
                name: "Secador de cabello",
                category: "Belleza",
                price: 39.90,
                description: "Secador compacto para uso doméstico.",
                image: "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 83,
                name: "Cepillo alisador",
                category: "Belleza",
                price: 44.90,
                description: "Cepillo eléctrico para peinar y alisar.",
                image: "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 84,
                name: "Rizador de cabello",
                category: "Belleza",
                price: 42.90,
                description: "Herramienta para crear ondas y rizos.",
                image: "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 85,
                name: "Plancha para cabello",
                category: "Belleza",
                price: 45.90,
                description: "Plancha práctica para estilizar el cabello.",
                image: "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 86,
                name: "Masajeador facial",
                category: "Belleza",
                price: 19.90,
                description: "Accesorio para complementar la rutina facial.",
                image: "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 87,
                name: "Set de manicure",
                category: "Belleza",
                price: 21.90,
                description: "Kit de herramientas para cuidado de uñas.",
                image: "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 88,
                name: "Lima eléctrica",
                category: "Belleza",
                price: 28.90,
                description: "Herramienta para cuidado y pulido de uñas.",
                image: "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 89,
                name: "Cortauñas profesional",
                category: "Belleza",
                price: 8.90,
                description: "Accesorio resistente para cuidado personal.",
                image: "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 90,
                name: "Estuche para cosméticos",
                category: "Belleza",
                price: 23.90,
                description: "Estuche amplio para maquillaje y accesorios.",
                image: "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 91,
                name: "Atomizador de perfume",
                category: "Belleza",
                price: 7.90,
                description: "Frasco recargable para llevar perfume.",
                image: "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 92,
                name: "Diadema para skincare",
                category: "Belleza",
                price: 6.90,
                description: "Diadema cómoda para rutinas faciales.",
                image: "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 93,
                name: "Rodillo quitapelusas",
                category: "Belleza",
                price: 8.90,
                description: "Accesorio para mantener prendas limpias.",
                image: "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 94,
                name: "Set de cuidado personal",
                category: "Belleza",
                price: 31.90,
                description: "Conjunto de accesorios para rutina diaria.",
                image: "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 95,
                name: "Set de vasos",
                category: "Comedor",
                price: 24.90,
                description: "Vasos para bebidas de uso diario.",
                image: "https://images.unsplash.com/photo-1603199506016-b9a594b593c0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 96,
                name: "Set de tazas",
                category: "Comedor",
                price: 22.90,
                description: "Tazas prácticas para café, té y bebidas.",
                image: "https://images.unsplash.com/photo-1603199506016-b9a594b593c0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 97,
                name: "Platos llanos",
                category: "Comedor",
                price: 28.90,
                description: "Set de platos para mesa diaria.",
                image: "https://images.unsplash.com/photo-1603199506016-b9a594b593c0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 98,
                name: "Platos soperos",
                category: "Comedor",
                price: 29.90,
                description: "Set de platos profundos para sopas y comidas.",
                image: "https://images.unsplash.com/photo-1603199506016-b9a594b593c0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 99,
                name: "Cubiertos de acero",
                category: "Comedor",
                price: 34.90,
                description: "Set de cubiertos para comedor.",
                image: "https://images.unsplash.com/photo-1603199506016-b9a594b593c0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 100,
                name: "Cuchillos de cocina",
                category: "Comedor",
                price: 39.90,
                description: "Set de cuchillos para preparación de alimentos.",
                image: "https://images.unsplash.com/photo-1603199506016-b9a594b593c0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 101,
                name: "Tabla de cortar",
                category: "Comedor",
                price: 17.90,
                description: "Tabla resistente para preparar alimentos.",
                image: "https://images.unsplash.com/photo-1603199506016-b9a594b593c0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 102,
                name: "Bandeja de servicio",
                category: "Comedor",
                price: 19.90,
                description: "Bandeja práctica para servir alimentos y bebidas.",
                image: "https://images.unsplash.com/photo-1603199506016-b9a594b593c0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 103,
                name: "Jarra de vidrio",
                category: "Comedor",
                price: 21.90,
                description: "Jarra elegante para bebidas frías.",
                image: "https://images.unsplash.com/photo-1603199506016-b9a594b593c0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 104,
                name: "Recipientes herméticos",
                category: "Comedor",
                price: 32.90,
                description: "Set de recipientes para conservar alimentos.",
                image: "https://images.unsplash.com/photo-1603199506016-b9a594b593c0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 105,
                name: "Salero y pimentero",
                category: "Comedor",
                price: 12.90,
                description: "Set práctico para condimentar la mesa.",
                image: "https://images.unsplash.com/photo-1603199506016-b9a594b593c0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 106,
                name: "Azucarera",
                category: "Comedor",
                price: 10.90,
                description: "Recipiente elegante para azúcar.",
                image: "https://images.unsplash.com/photo-1603199506016-b9a594b593c0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 107,
                name: "Servilletero",
                category: "Comedor",
                price: 9.90,
                description: "Accesorio funcional para mesa.",
                image: "https://images.unsplash.com/photo-1603199506016-b9a594b593c0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 108,
                name: "Mantel moderno",
                category: "Comedor",
                price: 26.90,
                description: "Mantel decorativo para comedor.",
                image: "https://images.unsplash.com/photo-1603199506016-b9a594b593c0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 109,
                name: "Individuales de mesa",
                category: "Comedor",
                price: 18.90,
                description: "Set de individuales para proteger la mesa.",
                image: "https://images.unsplash.com/photo-1603199506016-b9a594b593c0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 110,
                name: "Fuente para servir",
                category: "Comedor",
                price: 23.90,
                description: "Fuente amplia para presentar alimentos.",
                image: "https://images.unsplash.com/photo-1603199506016-b9a594b593c0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 111,
                name: "Ensaladera",
                category: "Comedor",
                price: 20.90,
                description: "Recipiente amplio para ensaladas y acompañamientos.",
                image: "https://images.unsplash.com/photo-1603199506016-b9a594b593c0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 112,
                name: "Bowl multiuso",
                category: "Comedor",
                price: 14.90,
                description: "Bowl práctico para diferentes preparaciones.",
                image: "https://images.unsplash.com/photo-1603199506016-b9a594b593c0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 113,
                name: "Tetera",
                category: "Comedor",
                price: 29.90,
                description: "Tetera para preparar y servir bebidas calientes.",
                image: "https://images.unsplash.com/photo-1603199506016-b9a594b593c0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 114,
                name: "Set de utensilios de cocina",
                category: "Comedor",
                price: 36.90,
                description: "Utensilios esenciales para cocinar.",
                image: "https://images.unsplash.com/photo-1603199506016-b9a594b593c0?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 115,
                name: "Smartwatch",
                category: "Tecnología",
                price: 49.90,
                description: "Reloj inteligente para actividades y notificaciones.",
                image: "https://images.unsplash.com/photo-1498049794561-7780e7231661?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 116,
                name: "Parlante Bluetooth",
                category: "Tecnología",
                price: 39.90,
                description: "Parlante portátil con conexión inalámbrica.",
                image: "https://images.unsplash.com/photo-1498049794561-7780e7231661?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 117,
                name: "Power bank",
                category: "Tecnología",
                price: 24.90,
                description: "Batería portátil para cargar dispositivos.",
                image: "https://images.unsplash.com/photo-1498049794561-7780e7231661?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 118,
                name: "Cargador rápido USB-C",
                category: "Tecnología",
                price: 18.90,
                description: "Cargador compacto para dispositivos compatibles.",
                image: "https://images.unsplash.com/photo-1498049794561-7780e7231661?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 119,
                name: "Cable USB-C",
                category: "Tecnología",
                price: 8.90,
                description: "Cable para carga y transferencia de datos.",
                image: "https://images.unsplash.com/photo-1498049794561-7780e7231661?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 120,
                name: "Cable Lightning",
                category: "Tecnología",
                price: 9.90,
                description: "Cable para carga y sincronización de dispositivos.",
                image: "https://images.unsplash.com/photo-1498049794561-7780e7231661?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 121,
                name: "Teclado inalámbrico",
                category: "Tecnología",
                price: 27.90,
                description: "Teclado compacto para computadora y tablet.",
                image: "https://images.unsplash.com/photo-1498049794561-7780e7231661?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 122,
                name: "Mouse inalámbrico",
                category: "Tecnología",
                price: 19.90,
                description: "Mouse cómodo para trabajo y estudio.",
                image: "https://images.unsplash.com/photo-1498049794561-7780e7231661?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 123,
                name: "Hub USB",
                category: "Tecnología",
                price: 21.90,
                description: "Adaptador para ampliar conexiones USB.",
                image: "https://images.unsplash.com/photo-1498049794561-7780e7231661?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 124,
                name: "Memoria USB 64GB",
                category: "Tecnología",
                price: 12.90,
                description: "Almacenamiento portátil para archivos.",
                image: "https://images.unsplash.com/photo-1498049794561-7780e7231661?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 125,
                name: "Lámpara LED USB",
                category: "Tecnología",
                price: 14.90,
                description: "Lámpara flexible para escritorio y lectura.",
                image: "https://images.unsplash.com/photo-1498049794561-7780e7231661?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 126,
                name: "Soporte para laptop",
                category: "Tecnología",
                price: 29.90,
                description: "Soporte para mejorar la posición de la computadora.",
                image: "https://images.unsplash.com/photo-1498049794561-7780e7231661?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 127,
                name: "Webcam HD",
                category: "Tecnología",
                price: 34.90,
                description: "Cámara para videollamadas y clases virtuales.",
                image: "https://images.unsplash.com/photo-1498049794561-7780e7231661?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 128,
                name: "Micrófono USB",
                category: "Tecnología",
                price: 44.90,
                description: "Micrófono para reuniones, streaming y grabaciones.",
                image: "https://images.unsplash.com/photo-1498049794561-7780e7231661?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 129,
                name: "Control inalámbrico",
                category: "Tecnología",
                price: 32.90,
                description: "Control para videojuegos y entretenimiento.",
                image: "https://images.unsplash.com/photo-1498049794561-7780e7231661?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 130,
                name: "Base de carga",
                category: "Tecnología",
                price: 26.90,
                description: "Base práctica para cargar dispositivos compatibles.",
                image: "https://images.unsplash.com/photo-1498049794561-7780e7231661?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 131,
                name: "Audífonos deportivos",
                category: "Tecnología",
                price: 25.90,
                description: "Audífonos ligeros para actividad física.",
                image: "https://images.unsplash.com/photo-1498049794561-7780e7231661?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 132,
                name: "Mini proyector",
                category: "Tecnología",
                price: 89.90,
                description: "Proyector compacto para entretenimiento en casa.",
                image: "https://images.unsplash.com/photo-1498049794561-7780e7231661?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 133,
                name: "Lector de tarjetas",
                category: "Tecnología",
                price: 15.90,
                description: "Accesorio para leer diferentes tarjetas de memoria.",
                image: "https://images.unsplash.com/photo-1498049794561-7780e7231661?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 134,
                name: "Adaptador Bluetooth",
                category: "Tecnología",
                price: 13.90,
                description: "Adaptador para añadir conectividad Bluetooth.",
                image: "https://images.unsplash.com/photo-1498049794561-7780e7231661?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 135,
                name: "Taladro inalámbrico",
                category: "Herramientas",
                price: 59.90,
                description: "Herramienta portátil para trabajos de perforación.",
                image: "https://images.unsplash.com/photo-1581147036324-c17ac41a2b83?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 136,
                name: "Atornillador eléctrico",
                category: "Herramientas",
                price: 49.90,
                description: "Herramienta práctica para montaje y reparación.",
                image: "https://images.unsplash.com/photo-1581147036324-c17ac41a2b83?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 137,
                name: "Juego de destornilladores",
                category: "Herramientas",
                price: 24.90,
                description: "Set de destornilladores para diferentes trabajos.",
                image: "https://images.unsplash.com/photo-1581147036324-c17ac41a2b83?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 138,
                name: "Juego de llaves",
                category: "Herramientas",
                price: 32.90,
                description: "Set de llaves para mantenimiento general.",
                image: "https://images.unsplash.com/photo-1581147036324-c17ac41a2b83?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 139,
                name: "Alicates multiuso",
                category: "Herramientas",
                price: 18.90,
                description: "Herramienta resistente para diferentes tareas.",
                image: "https://images.unsplash.com/photo-1581147036324-c17ac41a2b83?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 140,
                name: "Martillo profesional",
                category: "Herramientas",
                price: 22.90,
                description: "Martillo para trabajos domésticos y profesionales.",
                image: "https://images.unsplash.com/photo-1581147036324-c17ac41a2b83?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 141,
                name: "Cinta métrica",
                category: "Herramientas",
                price: 9.90,
                description: "Cinta resistente para mediciones precisas.",
                image: "https://images.unsplash.com/photo-1581147036324-c17ac41a2b83?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 142,
                name: "Nivel de burbuja",
                category: "Herramientas",
                price: 12.90,
                description: "Herramienta para verificar superficies niveladas.",
                image: "https://images.unsplash.com/photo-1581147036324-c17ac41a2b83?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 143,
                name: "Caja de herramientas",
                category: "Herramientas",
                price: 39.90,
                description: "Caja organizadora para herramientas y accesorios.",
                image: "https://images.unsplash.com/photo-1581147036324-c17ac41a2b83?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 144,
                name: "Llave ajustable",
                category: "Herramientas",
                price: 15.90,
                description: "Llave regulable para diferentes medidas.",
                image: "https://images.unsplash.com/photo-1581147036324-c17ac41a2b83?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 145,
                name: "Sierra manual",
                category: "Herramientas",
                price: 19.90,
                description: "Herramienta para cortes de madera y materiales.",
                image: "https://images.unsplash.com/photo-1581147036324-c17ac41a2b83?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 146,
                name: "Cúter profesional",
                category: "Herramientas",
                price: 8.90,
                description: "Cortador resistente para trabajos manuales.",
                image: "https://images.unsplash.com/photo-1581147036324-c17ac41a2b83?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 147,
                name: "Linterna recargable",
                category: "Herramientas",
                price: 24.90,
                description: "Linterna potente para hogar, taller y vehículo.",
                image: "https://images.unsplash.com/photo-1581147036324-c17ac41a2b83?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 148,
                name: "Pistola de silicona",
                category: "Herramientas",
                price: 14.90,
                description: "Herramienta para manualidades y reparaciones.",
                image: "https://images.unsplash.com/photo-1581147036324-c17ac41a2b83?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 149,
                name: "Multímetro digital",
                category: "Herramientas",
                price: 29.90,
                description: "Instrumento para mediciones eléctricas básicas.",
                image: "https://images.unsplash.com/photo-1581147036324-c17ac41a2b83?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 150,
                name: "Guantes de trabajo",
                category: "Herramientas",
                price: 13.90,
                description: "Guantes resistentes para protección durante labores.",
                image: "https://images.unsplash.com/photo-1581147036324-c17ac41a2b83?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 151,
                name: "Gafas de seguridad",
                category: "Herramientas",
                price: 9.90,
                description: "Protección ocular para trabajos y reparaciones.",
                image: "https://images.unsplash.com/photo-1581147036324-c17ac41a2b83?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 152,
                name: "Organizador de herramientas",
                category: "Herramientas",
                price: 27.90,
                description: "Organizador para mantener accesorios ordenados.",
                image: "https://images.unsplash.com/photo-1581147036324-c17ac41a2b83?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 153,
                name: "Brocas para taladro",
                category: "Herramientas",
                price: 26.90,
                description: "Set de brocas para diferentes superficies.",
                image: "https://images.unsplash.com/photo-1581147036324-c17ac41a2b83?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 154,
                name: "Kit de reparación",
                category: "Herramientas",
                price: 45.90,
                description: "Kit compacto para reparaciones domésticas.",
                image: "https://images.unsplash.com/photo-1581147036324-c17ac41a2b83?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 155,
                name: "Balón de fútbol",
                category: "Deportes",
                price: 24.90,
                description: "Balón para entrenamiento y recreación.",
                image: "https://images.unsplash.com/photo-1461896836934-ffe607ba8211?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 156,
                name: "Balón de básquet",
                category: "Deportes",
                price: 27.90,
                description: "Balón para entrenamiento y juegos.",
                image: "https://images.unsplash.com/photo-1461896836934-ffe607ba8211?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 157,
                name: "Balón de voleibol",
                category: "Deportes",
                price: 25.90,
                description: "Balón ligero para práctica y competencia.",
                image: "https://images.unsplash.com/photo-1461896836934-ffe607ba8211?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 158,
                name: "Cuerda para saltar",
                category: "Deportes",
                price: 12.90,
                description: "Accesorio para cardio y entrenamiento.",
                image: "https://images.unsplash.com/photo-1461896836934-ffe607ba8211?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 159,
                name: "Bandas de resistencia",
                category: "Deportes",
                price: 18.90,
                description: "Set de bandas para entrenamiento funcional.",
                image: "https://images.unsplash.com/photo-1461896836934-ffe607ba8211?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 160,
                name: "Colchoneta de ejercicio",
                category: "Deportes",
                price: 29.90,
                description: "Superficie cómoda para yoga y entrenamiento.",
                image: "https://images.unsplash.com/photo-1461896836934-ffe607ba8211?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 161,
                name: "Rodillo abdominal",
                category: "Deportes",
                price: 16.90,
                description: "Accesorio para ejercicios de core.",
                image: "https://images.unsplash.com/photo-1461896836934-ffe607ba8211?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 162,
                name: "Guantes de gimnasio",
                category: "Deportes",
                price: 15.90,
                description: "Guantes para mejorar agarre durante entrenamiento.",
                image: "https://images.unsplash.com/photo-1461896836934-ffe607ba8211?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 163,
                name: "Botella deportiva",
                category: "Deportes",
                price: 13.90,
                description: "Botella reutilizable para hidratación.",
                image: "https://images.unsplash.com/photo-1461896836934-ffe607ba8211?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 164,
                name: "Shaker deportivo",
                category: "Deportes",
                price: 12.90,
                description: "Vaso mezclador para bebidas y suplementos.",
                image: "https://images.unsplash.com/photo-1461896836934-ffe607ba8211?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 165,
                name: "Pesas rusas",
                category: "Deportes",
                price: 39.90,
                description: "Equipamiento para entrenamiento de fuerza.",
                image: "https://images.unsplash.com/photo-1461896836934-ffe607ba8211?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 166,
                name: "Disco de equilibrio",
                category: "Deportes",
                price: 22.90,
                description: "Accesorio para ejercicios de estabilidad.",
                image: "https://images.unsplash.com/photo-1461896836934-ffe607ba8211?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 167,
                name: "Rodillo de masaje",
                category: "Deportes",
                price: 24.90,
                description: "Accesorio para recuperación muscular.",
                image: "https://images.unsplash.com/photo-1461896836934-ffe607ba8211?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 168,
                name: "Cinturón deportivo",
                category: "Deportes",
                price: 19.90,
                description: "Accesorio para entrenamiento y soporte.",
                image: "https://images.unsplash.com/photo-1461896836934-ffe607ba8211?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 169,
                name: "Mochila deportiva",
                category: "Deportes",
                price: 32.90,
                description: "Mochila práctica para gimnasio y actividades.",
                image: "https://images.unsplash.com/photo-1461896836934-ffe607ba8211?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 170,
                name: "Toalla deportiva",
                category: "Deportes",
                price: 10.90,
                description: "Toalla ligera para entrenamiento.",
                image: "https://images.unsplash.com/photo-1461896836934-ffe607ba8211?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 171,
                name: "Gafas de natación",
                category: "Deportes",
                price: 17.90,
                description: "Gafas para piscina y entrenamiento acuático.",
                image: "https://images.unsplash.com/photo-1461896836934-ffe607ba8211?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 172,
                name: "Gorra deportiva",
                category: "Deportes",
                price: 14.90,
                description: "Gorra ligera para actividades al aire libre.",
                image: "https://images.unsplash.com/photo-1461896836934-ffe607ba8211?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 173,
                name: "Conos de entrenamiento",
                category: "Deportes",
                price: 16.90,
                description: "Set para ejercicios de coordinación y velocidad.",
                image: "https://images.unsplash.com/photo-1461896836934-ffe607ba8211?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 174,
                name: "Escalera de agilidad",
                category: "Deportes",
                price: 28.90,
                description: "Accesorio para entrenamiento de coordinación.",
                image: "https://images.unsplash.com/photo-1461896836934-ffe607ba8211?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 175,
                name: "Organizador de ducha",
                category: "Baño",
                price: 36.65,
                description: "Accesorio práctico para organizar y mejorar el baño.",
                image: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 176,
                name: "Dispensador de jabón",
                category: "Baño",
                price: 38.38,
                description: "Accesorio práctico para organizar y mejorar el baño.",
                image: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 177,
                name: "Vaso para cepillos",
                category: "Baño",
                price: 6.11,
                description: "Accesorio práctico para organizar y mejorar el baño.",
                image: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 178,
                name: "Alfombra de baño",
                category: "Baño",
                price: 7.84,
                description: "Accesorio práctico para organizar y mejorar el baño.",
                image: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 179,
                name: "Cortina de baño",
                category: "Baño",
                price: 9.57,
                description: "Accesorio práctico para organizar y mejorar el baño.",
                image: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 180,
                name: "Gancho adhesivo para baño",
                category: "Baño",
                price: 11.30,
                description: "Accesorio práctico para organizar y mejorar el baño.",
                image: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 181,
                name: "Estante de baño",
                category: "Baño",
                price: 13.03,
                description: "Accesorio práctico para organizar y mejorar el baño.",
                image: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 182,
                name: "Portarrollos de papel",
                category: "Baño",
                price: 14.76,
                description: "Accesorio práctico para organizar y mejorar el baño.",
                image: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 183,
                name: "Escobilla sanitaria",
                category: "Baño",
                price: 16.49,
                description: "Accesorio práctico para organizar y mejorar el baño.",
                image: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 184,
                name: "Jabonera de baño",
                category: "Baño",
                price: 18.22,
                description: "Accesorio práctico para organizar y mejorar el baño.",
                image: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 185,
                name: "Espejo adhesivo",
                category: "Baño",
                price: 19.95,
                description: "Accesorio práctico para organizar y mejorar el baño.",
                image: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 186,
                name: "Toallero de pared",
                category: "Baño",
                price: 21.68,
                description: "Accesorio práctico para organizar y mejorar el baño.",
                image: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 187,
                name: "Organizador bajo lavamanos",
                category: "Baño",
                price: 23.41,
                description: "Accesorio práctico para organizar y mejorar el baño.",
                image: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 188,
                name: "Canasto para ropa",
                category: "Baño",
                price: 25.14,
                description: "Accesorio práctico para organizar y mejorar el baño.",
                image: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 189,
                name: "Tapete antideslizante",
                category: "Baño",
                price: 26.87,
                description: "Accesorio práctico para organizar y mejorar el baño.",
                image: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 190,
                name: "Dispensador doble",
                category: "Baño",
                price: 28.60,
                description: "Accesorio práctico para organizar y mejorar el baño.",
                image: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 191,
                name: "Soporte para secadora",
                category: "Baño",
                price: 30.33,
                description: "Accesorio práctico para organizar y mejorar el baño.",
                image: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 192,
                name: "Organizador de cosméticos de baño",
                category: "Baño",
                price: 32.06,
                description: "Accesorio práctico para organizar y mejorar el baño.",
                image: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 193,
                name: "Cesta multiuso",
                category: "Baño",
                price: 33.79,
                description: "Accesorio práctico para organizar y mejorar el baño.",
                image: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 194,
                name: "Set de accesorios para baño",
                category: "Baño",
                price: 35.52,
                description: "Accesorio práctico para organizar y mejorar el baño.",
                image: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 195,
                name: "Trapeador giratorio",
                category: "Limpieza",
                price: 37.25,
                description: "Producto práctico para facilitar la limpieza del hogar.",
                image: "https://images.unsplash.com/photo-1583947215259-38e31be8751f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 196,
                name: "Escoba multiuso",
                category: "Limpieza",
                price: 38.98,
                description: "Producto práctico para facilitar la limpieza del hogar.",
                image: "https://images.unsplash.com/photo-1583947215259-38e31be8751f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 197,
                name: "Recogedor con mango",
                category: "Limpieza",
                price: 6.71,
                description: "Producto práctico para facilitar la limpieza del hogar.",
                image: "https://images.unsplash.com/photo-1583947215259-38e31be8751f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 198,
                name: "Cepillo para pisos",
                category: "Limpieza",
                price: 8.44,
                description: "Producto práctico para facilitar la limpieza del hogar.",
                image: "https://images.unsplash.com/photo-1583947215259-38e31be8751f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 199,
                name: "Cepillo para lavar ropa",
                category: "Limpieza",
                price: 10.17,
                description: "Producto práctico para facilitar la limpieza del hogar.",
                image: "https://images.unsplash.com/photo-1583947215259-38e31be8751f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 200,
                name: "Esponjas de cocina",
                category: "Limpieza",
                price: 11.90,
                description: "Producto práctico para facilitar la limpieza del hogar.",
                image: "https://images.unsplash.com/photo-1583947215259-38e31be8751f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 201,
                name: "Paños de microfibra",
                category: "Limpieza",
                price: 13.63,
                description: "Producto práctico para facilitar la limpieza del hogar.",
                image: "https://images.unsplash.com/photo-1583947215259-38e31be8751f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 202,
                name: "Guantes de limpieza",
                category: "Limpieza",
                price: 15.36,
                description: "Producto práctico para facilitar la limpieza del hogar.",
                image: "https://images.unsplash.com/photo-1583947215259-38e31be8751f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 203,
                name: "Plumero extensible",
                category: "Limpieza",
                price: 17.09,
                description: "Producto práctico para facilitar la limpieza del hogar.",
                image: "https://images.unsplash.com/photo-1583947215259-38e31be8751f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 204,
                name: "Limpiavidrios",
                category: "Limpieza",
                price: 18.82,
                description: "Producto práctico para facilitar la limpieza del hogar.",
                image: "https://images.unsplash.com/photo-1583947215259-38e31be8751f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 205,
                name: "Rociador multiuso",
                category: "Limpieza",
                price: 20.55,
                description: "Producto práctico para facilitar la limpieza del hogar.",
                image: "https://images.unsplash.com/photo-1583947215259-38e31be8751f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 206,
                name: "Cubeta plegable",
                category: "Limpieza",
                price: 22.28,
                description: "Producto práctico para facilitar la limpieza del hogar.",
                image: "https://images.unsplash.com/photo-1583947215259-38e31be8751f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 207,
                name: "Organizador de productos de limpieza",
                category: "Limpieza",
                price: 24.01,
                description: "Producto práctico para facilitar la limpieza del hogar.",
                image: "https://images.unsplash.com/photo-1583947215259-38e31be8751f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 208,
                name: "Cepillo para baño",
                category: "Limpieza",
                price: 25.74,
                description: "Producto práctico para facilitar la limpieza del hogar.",
                image: "https://images.unsplash.com/photo-1583947215259-38e31be8751f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 209,
                name: "Rodillo quitapelusas",
                category: "Limpieza",
                price: 27.47,
                description: "Producto práctico para facilitar la limpieza del hogar.",
                image: "https://images.unsplash.com/photo-1583947215259-38e31be8751f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 210,
                name: "Cepillo para muebles",
                category: "Limpieza",
                price: 29.20,
                description: "Producto práctico para facilitar la limpieza del hogar.",
                image: "https://images.unsplash.com/photo-1583947215259-38e31be8751f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 211,
                name: "Mopa plana",
                category: "Limpieza",
                price: 30.93,
                description: "Producto práctico para facilitar la limpieza del hogar.",
                image: "https://images.unsplash.com/photo-1583947215259-38e31be8751f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 212,
                name: "Escobilla multiuso",
                category: "Limpieza",
                price: 32.66,
                description: "Producto práctico para facilitar la limpieza del hogar.",
                image: "https://images.unsplash.com/photo-1583947215259-38e31be8751f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 213,
                name: "Balde con escurridor",
                category: "Limpieza",
                price: 34.39,
                description: "Producto práctico para facilitar la limpieza del hogar.",
                image: "https://images.unsplash.com/photo-1583947215259-38e31be8751f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 214,
                name: "Set de limpieza para cocina",
                category: "Limpieza",
                price: 36.12,
                description: "Producto práctico para facilitar la limpieza del hogar.",
                image: "https://images.unsplash.com/photo-1583947215259-38e31be8751f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 215,
                name: "Bloques de construcción",
                category: "Juguetería",
                price: 37.85,
                description: "Juego para entretenimiento y actividades recreativas.",
                image: "https://images.unsplash.com/photo-1566576912321-d58ddd7a6088?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 216,
                name: "Rompecabezas educativo",
                category: "Juguetería",
                price: 39.58,
                description: "Juego para entretenimiento y actividades recreativas.",
                image: "https://images.unsplash.com/photo-1566576912321-d58ddd7a6088?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 217,
                name: "Carro a control remoto",
                category: "Juguetería",
                price: 7.31,
                description: "Juego para entretenimiento y actividades recreativas.",
                image: "https://images.unsplash.com/photo-1566576912321-d58ddd7a6088?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 218,
                name: "Muñeca infantil",
                category: "Juguetería",
                price: 9.04,
                description: "Juego para entretenimiento y actividades recreativas.",
                image: "https://images.unsplash.com/photo-1566576912321-d58ddd7a6088?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 219,
                name: "Set de cocina de juguete",
                category: "Juguetería",
                price: 10.77,
                description: "Juego para entretenimiento y actividades recreativas.",
                image: "https://images.unsplash.com/photo-1566576912321-d58ddd7a6088?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 220,
                name: "Juego de herramientas de juguete",
                category: "Juguetería",
                price: 12.50,
                description: "Juego para entretenimiento y actividades recreativas.",
                image: "https://images.unsplash.com/photo-1566576912321-d58ddd7a6088?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 221,
                name: "Pelota infantil",
                category: "Juguetería",
                price: 14.23,
                description: "Juego para entretenimiento y actividades recreativas.",
                image: "https://images.unsplash.com/photo-1566576912321-d58ddd7a6088?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 222,
                name: "Pizarra magnética",
                category: "Juguetería",
                price: 15.96,
                description: "Juego para entretenimiento y actividades recreativas.",
                image: "https://images.unsplash.com/photo-1566576912321-d58ddd7a6088?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 223,
                name: "Juego de memoria",
                category: "Juguetería",
                price: 17.69,
                description: "Juego para entretenimiento y actividades recreativas.",
                image: "https://images.unsplash.com/photo-1566576912321-d58ddd7a6088?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 224,
                name: "Jenga de madera",
                category: "Juguetería",
                price: 19.42,
                description: "Juego para entretenimiento y actividades recreativas.",
                image: "https://images.unsplash.com/photo-1566576912321-d58ddd7a6088?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 225,
                name: "Set de arte infantil",
                category: "Juguetería",
                price: 21.15,
                description: "Juego para entretenimiento y actividades recreativas.",
                image: "https://images.unsplash.com/photo-1566576912321-d58ddd7a6088?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 226,
                name: "Avión de juguete",
                category: "Juguetería",
                price: 22.88,
                description: "Juego para entretenimiento y actividades recreativas.",
                image: "https://images.unsplash.com/photo-1566576912321-d58ddd7a6088?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 227,
                name: "Pista de carros",
                category: "Juguetería",
                price: 24.61,
                description: "Juego para entretenimiento y actividades recreativas.",
                image: "https://images.unsplash.com/photo-1566576912321-d58ddd7a6088?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 228,
                name: "Animalitos de juguete",
                category: "Juguetería",
                price: 26.34,
                description: "Juego para entretenimiento y actividades recreativas.",
                image: "https://images.unsplash.com/photo-1566576912321-d58ddd7a6088?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 229,
                name: "Juego de encaje",
                category: "Juguetería",
                price: 28.07,
                description: "Juego para entretenimiento y actividades recreativas.",
                image: "https://images.unsplash.com/photo-1566576912321-d58ddd7a6088?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 230,
                name: "Cubo didáctico",
                category: "Juguetería",
                price: 29.80,
                description: "Juego para entretenimiento y actividades recreativas.",
                image: "https://images.unsplash.com/photo-1566576912321-d58ddd7a6088?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 231,
                name: "Juego de pesca",
                category: "Juguetería",
                price: 31.53,
                description: "Juego para entretenimiento y actividades recreativas.",
                image: "https://images.unsplash.com/photo-1566576912321-d58ddd7a6088?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 232,
                name: "Set de doctor",
                category: "Juguetería",
                price: 33.26,
                description: "Juego para entretenimiento y actividades recreativas.",
                image: "https://images.unsplash.com/photo-1566576912321-d58ddd7a6088?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 233,
                name: "Juego de cartas infantil",
                category: "Juguetería",
                price: 34.99,
                description: "Juego para entretenimiento y actividades recreativas.",
                image: "https://images.unsplash.com/photo-1566576912321-d58ddd7a6088?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 234,
                name: "Juguete musical",
                category: "Juguetería",
                price: 36.72,
                description: "Juego para entretenimiento y actividades recreativas.",
                image: "https://images.unsplash.com/photo-1566576912321-d58ddd7a6088?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 235,
                name: "Manguera para jardín",
                category: "Jardín y Exterior",
                price: 38.45,
                description: "Producto práctico para jardín, patio y espacios exteriores.",
                image: "https://images.unsplash.com/photo-1416879595882-3373a0480b5b?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 236,
                name: "Pistola de riego",
                category: "Jardín y Exterior",
                price: 6.18,
                description: "Producto práctico para jardín, patio y espacios exteriores.",
                image: "https://images.unsplash.com/photo-1416879595882-3373a0480b5b?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 237,
                name: "Aspersor de jardín",
                category: "Jardín y Exterior",
                price: 7.91,
                description: "Producto práctico para jardín, patio y espacios exteriores.",
                image: "https://images.unsplash.com/photo-1416879595882-3373a0480b5b?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 238,
                name: "Tijera para podar",
                category: "Jardín y Exterior",
                price: 9.64,
                description: "Producto práctico para jardín, patio y espacios exteriores.",
                image: "https://images.unsplash.com/photo-1416879595882-3373a0480b5b?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 239,
                name: "Guantes de jardinería",
                category: "Jardín y Exterior",
                price: 11.37,
                description: "Producto práctico para jardín, patio y espacios exteriores.",
                image: "https://images.unsplash.com/photo-1416879595882-3373a0480b5b?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 240,
                name: "Pala de mano",
                category: "Jardín y Exterior",
                price: 13.10,
                description: "Producto práctico para jardín, patio y espacios exteriores.",
                image: "https://images.unsplash.com/photo-1416879595882-3373a0480b5b?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 241,
                name: "Rastrillo de jardín",
                category: "Jardín y Exterior",
                price: 14.83,
                description: "Producto práctico para jardín, patio y espacios exteriores.",
                image: "https://images.unsplash.com/photo-1416879595882-3373a0480b5b?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 242,
                name: "Maceta decorativa",
                category: "Jardín y Exterior",
                price: 16.56,
                description: "Producto práctico para jardín, patio y espacios exteriores.",
                image: "https://images.unsplash.com/photo-1416879595882-3373a0480b5b?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 243,
                name: "Maceta colgante",
                category: "Jardín y Exterior",
                price: 18.29,
                description: "Producto práctico para jardín, patio y espacios exteriores.",
                image: "https://images.unsplash.com/photo-1416879595882-3373a0480b5b?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 244,
                name: "Regadera",
                category: "Jardín y Exterior",
                price: 20.02,
                description: "Producto práctico para jardín, patio y espacios exteriores.",
                image: "https://images.unsplash.com/photo-1416879595882-3373a0480b5b?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 245,
                name: "Atomizador para plantas",
                category: "Jardín y Exterior",
                price: 21.75,
                description: "Producto práctico para jardín, patio y espacios exteriores.",
                image: "https://images.unsplash.com/photo-1416879595882-3373a0480b5b?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 246,
                name: "Organizador de herramientas de jardín",
                category: "Jardín y Exterior",
                price: 23.48,
                description: "Producto práctico para jardín, patio y espacios exteriores.",
                image: "https://images.unsplash.com/photo-1416879595882-3373a0480b5b?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 247,
                name: "Silla plegable exterior",
                category: "Jardín y Exterior",
                price: 25.21,
                description: "Producto práctico para jardín, patio y espacios exteriores.",
                image: "https://images.unsplash.com/photo-1416879595882-3373a0480b5b?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 248,
                name: "Mesa plegable exterior",
                category: "Jardín y Exterior",
                price: 26.94,
                description: "Producto práctico para jardín, patio y espacios exteriores.",
                image: "https://images.unsplash.com/photo-1416879595882-3373a0480b5b?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 249,
                name: "Linterna solar de jardín",
                category: "Jardín y Exterior",
                price: 28.67,
                description: "Producto práctico para jardín, patio y espacios exteriores.",
                image: "https://images.unsplash.com/photo-1416879595882-3373a0480b5b?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 250,
                name: "Luz solar decorativa",
                category: "Jardín y Exterior",
                price: 30.40,
                description: "Producto práctico para jardín, patio y espacios exteriores.",
                image: "https://images.unsplash.com/photo-1416879595882-3373a0480b5b?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 251,
                name: "Escoba para exterior",
                category: "Jardín y Exterior",
                price: 32.13,
                description: "Producto práctico para jardín, patio y espacios exteriores.",
                image: "https://images.unsplash.com/photo-1416879595882-3373a0480b5b?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 252,
                name: "Cepillo para patio",
                category: "Jardín y Exterior",
                price: 33.86,
                description: "Producto práctico para jardín, patio y espacios exteriores.",
                image: "https://images.unsplash.com/photo-1416879595882-3373a0480b5b?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 253,
                name: "Bordeadora manual",
                category: "Jardín y Exterior",
                price: 35.59,
                description: "Producto práctico para jardín, patio y espacios exteriores.",
                image: "https://images.unsplash.com/photo-1416879595882-3373a0480b5b?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 254,
                name: "Set de jardinería",
                category: "Jardín y Exterior",
                price: 37.32,
                description: "Producto práctico para jardín, patio y espacios exteriores.",
                image: "https://images.unsplash.com/photo-1416879595882-3373a0480b5b?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 255,
                name: "Organizador de escritorio",
                category: "Oficina y Negocio",
                price: 39.05,
                description: "Accesorio útil para organización y trabajo diario.",
                image: "https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 256,
                name: "Portalápices",
                category: "Oficina y Negocio",
                price: 6.78,
                description: "Accesorio útil para organización y trabajo diario.",
                image: "https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 257,
                name: "Archivador de documentos",
                category: "Oficina y Negocio",
                price: 8.51,
                description: "Accesorio útil para organización y trabajo diario.",
                image: "https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 258,
                name: "Carpeta multiuso",
                category: "Oficina y Negocio",
                price: 10.24,
                description: "Accesorio útil para organización y trabajo diario.",
                image: "https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 259,
                name: "Libreta ejecutiva",
                category: "Oficina y Negocio",
                price: 11.97,
                description: "Accesorio útil para organización y trabajo diario.",
                image: "https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 260,
                name: "Cuaderno de notas",
                category: "Oficina y Negocio",
                price: 13.70,
                description: "Accesorio útil para organización y trabajo diario.",
                image: "https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 261,
                name: "Agenda organizadora",
                category: "Oficina y Negocio",
                price: 15.43,
                description: "Accesorio útil para organización y trabajo diario.",
                image: "https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 262,
                name: "Grapadora de escritorio",
                category: "Oficina y Negocio",
                price: 17.16,
                description: "Accesorio útil para organización y trabajo diario.",
                image: "https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 263,
                name: "Perforadora de papel",
                category: "Oficina y Negocio",
                price: 18.89,
                description: "Accesorio útil para organización y trabajo diario.",
                image: "https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 264,
                name: "Dispensador de cinta",
                category: "Oficina y Negocio",
                price: 20.62,
                description: "Accesorio útil para organización y trabajo diario.",
                image: "https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 265,
                name: "Calculadora de escritorio",
                category: "Oficina y Negocio",
                price: 22.35,
                description: "Accesorio útil para organización y trabajo diario.",
                image: "https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 266,
                name: "Soporte para celular de escritorio",
                category: "Oficina y Negocio",
                price: 24.08,
                description: "Accesorio útil para organización y trabajo diario.",
                image: "https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 267,
                name: "Soporte para laptop",
                category: "Oficina y Negocio",
                price: 25.81,
                description: "Accesorio útil para organización y trabajo diario.",
                image: "https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 268,
                name: "Lámpara de escritorio",
                category: "Oficina y Negocio",
                price: 27.54,
                description: "Accesorio útil para organización y trabajo diario.",
                image: "https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 269,
                name: "Pizarra blanca",
                category: "Oficina y Negocio",
                price: 29.27,
                description: "Accesorio útil para organización y trabajo diario.",
                image: "https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 270,
                name: "Marcadores para pizarra",
                category: "Oficina y Negocio",
                price: 31.00,
                description: "Accesorio útil para organización y trabajo diario.",
                image: "https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 271,
                name: "Etiquetadora manual",
                category: "Oficina y Negocio",
                price: 32.73,
                description: "Accesorio útil para organización y trabajo diario.",
                image: "https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 272,
                name: "Caja organizadora",
                category: "Oficina y Negocio",
                price: 34.46,
                description: "Accesorio útil para organización y trabajo diario.",
                image: "https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 273,
                name: "Bandeja para documentos",
                category: "Oficina y Negocio",
                price: 36.19,
                description: "Accesorio útil para organización y trabajo diario.",
                image: "https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 274,
                name: "Set de útiles de oficina",
                category: "Oficina y Negocio",
                price: 37.92,
                description: "Accesorio útil para organización y trabajo diario.",
                image: "https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 275,
                name: "Botella deportiva",
                category: "Accesorios y Otros",
                price: 39.65,
                description: "Accesorio práctico para uso diario, hogar o viaje.",
                image: "https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 276,
                name: "Termo portátil",
                category: "Accesorios y Otros",
                price: 7.38,
                description: "Accesorio práctico para uso diario, hogar o viaje.",
                image: "https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 277,
                name: "Paraguas plegable",
                category: "Accesorios y Otros",
                price: 9.11,
                description: "Accesorio práctico para uso diario, hogar o viaje.",
                image: "https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 278,
                name: "Llavero multiuso",
                category: "Accesorios y Otros",
                price: 10.84,
                description: "Accesorio práctico para uso diario, hogar o viaje.",
                image: "https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 279,
                name: "Organizador de cables",
                category: "Accesorios y Otros",
                price: 12.57,
                description: "Accesorio práctico para uso diario, hogar o viaje.",
                image: "https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 280,
                name: "Soporte para celular",
                category: "Accesorios y Otros",
                price: 14.30,
                description: "Accesorio práctico para uso diario, hogar o viaje.",
                image: "https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 281,
                name: "Bolso multiuso",
                category: "Accesorios y Otros",
                price: 16.03,
                description: "Accesorio práctico para uso diario, hogar o viaje.",
                image: "https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 282,
                name: "Neceser de viaje",
                category: "Accesorios y Otros",
                price: 17.76,
                description: "Accesorio práctico para uso diario, hogar o viaje.",
                image: "https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 283,
                name: "Organizador de viaje",
                category: "Accesorios y Otros",
                price: 19.49,
                description: "Accesorio práctico para uso diario, hogar o viaje.",
                image: "https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 284,
                name: "Billetera",
                category: "Accesorios y Otros",
                price: 21.22,
                description: "Accesorio práctico para uso diario, hogar o viaje.",
                image: "https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 285,
                name: "Gorra casual",
                category: "Accesorios y Otros",
                price: 22.95,
                description: "Accesorio práctico para uso diario, hogar o viaje.",
                image: "https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 286,
                name: "Gafas de sol",
                category: "Accesorios y Otros",
                price: 24.68,
                description: "Accesorio práctico para uso diario, hogar o viaje.",
                image: "https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 287,
                name: "Reloj digital",
                category: "Accesorios y Otros",
                price: 26.41,
                description: "Accesorio práctico para uso diario, hogar o viaje.",
                image: "https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 288,
                name: "Linterna portátil",
                category: "Accesorios y Otros",
                price: 28.14,
                description: "Accesorio práctico para uso diario, hogar o viaje.",
                image: "https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 289,
                name: "Cargador universal",
                category: "Accesorios y Otros",
                price: 29.87,
                description: "Accesorio práctico para uso diario, hogar o viaje.",
                image: "https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 290,
                name: "Cable multiuso",
                category: "Accesorios y Otros",
                price: 31.60,
                description: "Accesorio práctico para uso diario, hogar o viaje.",
                image: "https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 291,
                name: "Soporte para tablet",
                category: "Accesorios y Otros",
                price: 33.33,
                description: "Accesorio práctico para uso diario, hogar o viaje.",
                image: "https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 292,
                name: "Cinta métrica",
                category: "Accesorios y Otros",
                price: 35.06,
                description: "Accesorio práctico para uso diario, hogar o viaje.",
                image: "https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 293,
                name: "Candado de seguridad",
                category: "Accesorios y Otros",
                price: 36.79,
                description: "Accesorio práctico para uso diario, hogar o viaje.",
                image: "https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?auto=format&fit=crop&w=800&q=85"
            },

            {
                id: 294,
                name: "Kit de viaje",
                category: "Accesorios y Otros",
                price: 38.52,
                description: "Accesorio práctico para uso diario, hogar o viaje.",
                image: "https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?auto=format&fit=crop&w=800&q=85"
            },
        ];

        /* =====================================================
           VARIABLES
        ===================================================== */

        let cart = [];
        let currentCategory = "Todos";

        try {
            const savedCart = localStorage.getItem("importGlobalCart");
            if (savedCart) cart = JSON.parse(savedCart) || [];
        } catch (e) {
            cart = [];
        }

        function saveCart() {
            try {
                localStorage.setItem("importGlobalCart", JSON.stringify(cart));
            } catch (e) {}
        }



        /* =====================================================
           GENERAR PRODUCTOS
        ===================================================== */


        /* ============================================================
           IMÁGENES — SIMPLE Y COMPATIBLE
           Usa directamente la ruta de la imagen que coloques en product.image.
           Funciona en Chrome, Safari, iPhone, Android y PC.
        ============================================================ */

        const IMAGE_ERROR =
            "data:image/svg+xml;charset=UTF-8," +
            encodeURIComponent(
                '<svg xmlns="http://www.w3.org/2000/svg" width="800" height="800">' +
                '<rect width="800" height="800" fill="#f5f5f5"/>' +
                '<rect x="25" y="25" width="750" height="750" rx="20" fill="#fff" stroke="#ddd"/>' +
                '<text x="400" y="390" text-anchor="middle" font-family="Arial,sans-serif" font-size="30" fill="#777">Imagen no disponible</text>' +
                '</svg>'
            );

        function safeImageUrl(url) {
            if (!url) return IMAGE_ERROR;
            return String(url).trim();
        }

        function imageError(img) {
            if (!img || img.dataset.error === "1") return;
            img.dataset.error = "1";
            img.src = IMAGE_ERROR;
        }

        function renderProducts() {
            const grid = document.getElementById("productGrid");
            if (!grid) return;

            grid.innerHTML = "";

            const fragment = document.createDocumentFragment();

            products.forEach(function(product) {
                const card = document.createElement("article");
                card.className = "product-card";
                card.dataset.name = product.name;
                card.dataset.category = product.category;

                card.innerHTML = `
                    <div class="product-image">
                        <img
                            src="${safeImageUrl(product.image)}"
                            alt="${product.name}"
                            width="800"
                            height="800"
                            loading="lazy"
                            decoding="async"
                            onerror="imageError(this)"
                            style="display:block;width:100%;height:100%;object-fit:cover;"
                        >
                    </div>
                    <div class="product-info">
                        <div class="product-category">${product.category}</div>
                        <h3>${product.name}</h3>
                        <p class="product-description">${product.description}</p>
                        <div class="product-bottom">
                            <div class="price">$${Number(product.price).toFixed(2)}</div>
                            <button class="add-button" onclick="addToCart(${product.id})">Agregar</button>
                        </div>
                    </div>
                `;

                fragment.appendChild(card);
            });

            grid.appendChild(fragment);
            applyProductFilter();
        }

        function applyProductFilter() {
            const searchInput = document.getElementById("searchInput");
            const search = searchInput ? searchInput.value.toLowerCase().trim() : "";
            const cards = document.querySelectorAll(".product-card");
            let visible = 0;

            cards.forEach(function(card) {
                const name = (card.dataset.name || "").toLowerCase();
                const category = (card.dataset.category || "").toLowerCase();
                const categoryOk = currentCategory === "Todos" || card.dataset.category === currentCategory;
                const searchOk = !search || name.includes(search) || category.includes(search);
                const show = categoryOk && searchOk;

                card.style.display = show ? "" : "none";
                if (show) visible++;
            });

            const result = document.getElementById("productResults");
            if (result) {
                if (search) {
                    result.textContent = visible + " producto" + (visible === 1 ? "" : "s") + " encontrado" + (visible === 1 ? "" : "s");
                } else if (currentCategory === "Todos") {
                    result.textContent = "Todos los productos";
                } else {
                    result.textContent = currentCategory + " — " + visible + " productos";
                }
            }
        }

        /* =====================================================
           AGREGAR AL CARRITO
        ===================================================== */

        function addToCart(productId) {


            const product =
                products.find(
                    item => item.id === productId
                );


            if (!product) {
                return;
            }


            const existing =
                cart.find(
                    item => item.id === productId
                );


            if (existing) {

                existing.quantity++;

            }

            else {

                cart.push({

                    ...product,

                    quantity: 1

                });

            }


            updateCart();

            openCart();

        }



        /* =====================================================
           ACTUALIZAR CARRITO
        ===================================================== */

        function updateCart() {

            saveCart();

            const cartItems =
                document.getElementById(
                    "cartItems"
                );


            const cartCount =
                document.getElementById(
                    "cartCount"
                );


            const cartTotal =
                document.getElementById(
                    "cartTotal"
                );


            cartItems.innerHTML = "";


            if (cart.length === 0) {


                cartItems.innerHTML = `

                    <div class="empty-cart">

                        Tu carrito está vacío.

                    </div>

                `;


                cartCount.textContent = "0";

                cartTotal.textContent = "$0.00";

                return;

            }


            let totalItems = 0;

            let totalPrice = 0;



            cart.forEach(item => {


                totalItems += item.quantity;


                totalPrice +=
                    item.price *
                    item.quantity;


                const cartItem =
                    document.createElement("div");


                cartItem.className =
                    "cart-item";


                cartItem.innerHTML = `


                    <img
                        src="${item.image}"
                        alt="${item.name}"
                     loading="lazy" decoding="async">


                    <div>


                        <h4>
                            ${item.name}
                        </h4>


                        <div class="cart-item-price">

                            $${item.price.toFixed(2)}

                        </div>


                        <div class="quantity-controls">


                            <button
                                onclick="changeQuantity(${item.id}, -1)"
                            >
                                −
                            </button>


                            <span>
                                ${item.quantity}
                            </span>


                            <button
                                onclick="changeQuantity(${item.id}, 1)"
                            >
                                +
                            </button>


                        </div>


                        <button
                            class="remove-item"
                            onclick="removeFromCart(${item.id})"
                        >

                            Eliminar

                        </button>


                    </div>


                    <div>

                        <strong>

                            $${(
                                item.price *
                                item.quantity
                            ).toFixed(2)}

                        </strong>

                    </div>


                `;


                cartItems.appendChild(cartItem);


            });


            cartCount.textContent =
                totalItems;


            cartTotal.textContent =
                "$" +
                totalPrice.toFixed(2);

        }



        /* =====================================================
           CAMBIAR CANTIDAD
        ===================================================== */

        function changeQuantity(
            productId,
            change
        ) {


            const item =
                cart.find(
                    product =>
                        product.id === productId
                );


            if (!item) {
                return;
            }


            item.quantity += change;


            if (item.quantity <= 0) {


                cart =
                    cart.filter(
                        product =>
                            product.id !== productId
                    );

            }


            updateCart();

        }



        /* =====================================================
           ELIMINAR PRODUCTO
        ===================================================== */

        function removeFromCart(
            productId
        ) {


            cart =
                cart.filter(
                    product =>
                        product.id !== productId
                );


            updateCart();

        }



        /* =====================================================
           ABRIR CARRITO
        ===================================================== */

        function openCart() {


            document
                .getElementById(
                    "cartSidebar"
                )
                .classList.add("active");


            document
                .getElementById(
                    "cartOverlay"
                )
                .classList.add("active");

        }



        /* =====================================================
           CERRAR CARRITO
        ===================================================== */

        function closeCart() {


            document
                .getElementById(
                    "cartSidebar"
                )
                .classList.remove("active");


            document
                .getElementById(
                    "cartOverlay"
                )
                .classList.remove("active");

        }



        /* =====================================================
           FILTRAR CATEGORÍA Y BUSCADOR
        ===================================================== */

        function filterCategory(category, element) {
            currentCategory = category || "Todos";

            document.querySelectorAll(".category-card").forEach(function(card) {
                card.classList.remove("active");
            });

            if (element) element.classList.add("active");

            const searchInput = document.getElementById("searchInput");
            if (searchInput) searchInput.value = "";

            applyProductFilter();

            const productsSection = document.getElementById("productos");
            if (productsSection) {
                setTimeout(function() {
                    productsSection.scrollIntoView({ behavior: "smooth", block: "start" });
                }, 50);
            }
        }

        function searchProducts() {
            applyProductFilter();
        }

        /* =====================================================
           ENVIAR PEDIDO A WHATSAPP
        ===================================================== */

        function sendOrderToWhatsApp() {


            if (cart.length === 0) {


                alert(
                    "Tu carrito está vacío."
                );


                return;

            }


            let message =
                "Hola, Import Global.%0A%0A" +

                "Deseo realizar el siguiente pedido:%0A%0A";


            let total = 0;


            cart.forEach(item => {


                const subtotal =
                    item.price *
                    item.quantity;


                total += subtotal;


                message +=

                    "Producto: " +
                    item.name +
                    "%0A" +

                    "Categoría: " +
                    item.category +
                    "%0A" +

                    "Cantidad: " +
                    item.quantity +
                    "%0A" +

                    "Precio unitario: $" +
                    item.price.toFixed(2) +
                    "%0A" +

                    "Subtotal: $" +
                    subtotal.toFixed(2) +
                    "%0A%0A";

            });


            message +=

                "Total estimado: $" +
                total.toFixed(2) +
                "%0A%0A" +

                "Quiero realizar este pedido. " +

                "Por favor, confirmen disponibilidad, " +

                "forma de pago y detalles de entrega.";


            const whatsappURL =

                "https://wa.me/" +

                WHATSAPP_NUMBER +

                "?text=" +

                message;


            window.open(
                whatsappURL,
                "_blank"
            );

        }



        /* =====================================================
           INICIALIZAR
        ===================================================== */

        renderProducts();
        updateCart();


    </script>


</body>

</html>
