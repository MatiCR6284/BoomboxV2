Animaciones usadas:

Linea 215 en styles.css:

  .img-animada {
    width: 100%;
    filter: grayscale(100%);
    transition: filter 3s ease;
  }

  .img-animada:hover {
    filter: grayscale(0%);
  }

Linea 198 en styles.css:

  .product button:hover {
    background-color: #2ecc71;
    transform: scale(1.05);
  }

Linea 85 en styles.css:

 h1 {
    display: inline-block;
    transition: transform 0.6s ease;
    transform-origin: center;
  }

  h1:hover {
    transform: rotateX(360deg);
  }

Linea 71 en styles.css:

  nav ul li a {
    color: #fff;
    text-decoration: none;
    display: block;
    padding: 8px;
    text-align: center;
    background-color: #E07A5F;
    border-radius: 4px;
  }

  li:hover {
    transform: scale(1.05);
  }

=========================================

La estructura del sitio web se aplica Flex y Grid al igual que un Mediaquery donde cambia de aspecto en pantallas más pequeñas.
