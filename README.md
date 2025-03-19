# 🎨 Práctica de Maquetación en CSS

## 📌 Descripción
Este proyecto es una práctica de **maquetación con CSS**, donde se exploran conceptos clave como **flexbox, grid, posicionamiento, tipografías, colores y media queries** para crear diseños responsivos y visualmente atractivos.

---

## 📂 Estructura del Proyecto

- **index.html** → Archivo principal que contiene la estructura HTML de la página.
- **styles.css** → Archivo de estilos donde se aplican las reglas CSS.
- **assets/** → Carpeta que contiene imágenes, iconos y otros recursos.

---

## 🎨 Explicación de Archivos

### **index.html**
Contiene la estructura de la página con secciones como **header, main, sidebar y footer**. Se enlaza con `styles.css` para aplicar los estilos.

Ejemplo de enlace a CSS:
```html
<link rel="stylesheet" href="styles.css">
```

### **styles.css**
Define estilos para diferentes elementos de la página, incluyendo:
- **Uso de Flexbox y Grid** para la disposición de elementos.
- **Colores y tipografías** para mejorar la apariencia.
- **Media queries** para un diseño responsivo.

Ejemplo de Flexbox:
```css
.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
```

Ejemplo de Media Query:
```css
@media (max-width: 768px) {
    .container {
        flex-direction: column;
    }
}
```

---

## 🛠 Instalación y Uso
1. Clonar este repositorio:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   ```
2. Abrir `index.html` en un navegador.
3. Explorar la estructura y modificar `styles.css` para experimentar con los estilos.

---

## 📌 Conceptos Cubiertos
✅ Flexbox y Grid para el diseño de la página  
✅ Tipografías y colores personalizados  
✅ Posicionamiento con `absolute`, `relative`, `fixed`, `sticky`  
✅ Uso de `hover`, `focus`, `active` para efectos interactivos  
✅ Media queries para adaptabilidad en móviles y tabletas  

---

## 📜 Licencia
Este proyecto está bajo la licencia **MIT**, lo que significa que puedes usarlo, modificarlo y distribuirlo libremente.

🚀 **¡Feliz diseño y maquetación!** 🎨

