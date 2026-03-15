# 🌑 Sombras Inteligentes con CSS

Pequeño experimento en **CSS** que demuestra cómo crear **sombras dinámicas basadas en el fondo del elemento** utilizando pseudo-elementos.

En lugar de usar `box-shadow`, el efecto se logra **duplicando el background del elemento** y aplicando **filtros CSS** para generar una sombra difusa que se integra con la imagen.

---

## ✨ Idea

La técnica consiste en **heredar el fondo del elemento (`background: inherit`)** en pseudo-elementos y aplicar filtros para crear un efecto visual más interesante que una sombra tradicional.

Esto permite:

- 🌊 Generar una **sombra basada en la imagen**
- 🌫️ Aplicar **blur para difuminar la sombra**
- 🎨 Intensificar colores con **saturate**
- ⚡ Lograr el efecto **solo con CSS**

---

## 🛠 Tecnologías

- 🌐 HTML5  
- 🎨 CSS3  

No se utiliza JavaScript.

---

## ⚙️ Cómo funciona

El elemento principal contiene una imagen de fondo:

```css
article {
    background-image: url(img/sea.jpg);
    background-position: center;
    background-repeat: no-repeat;
    z-index: 1;
}
