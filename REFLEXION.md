# Reflexión Aplicada - Laboratorio 4

### 1. Fragmento CSS de la animación del logo del CURZA
```css
.logo-curza {
    width: 40px;
    height: 40px;
    transition: transform 1s ease-in-out;
}

.logo-curza:hover {
    transform: rotateY(360deg);
}