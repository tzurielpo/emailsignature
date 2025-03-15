# 📩 Firma de Correo Electrónico - Tzuriel Plata

Este repositorio contiene la firma de correo electrónico de **Tzuriel Plata**, diseñada para ser utilizada en clientes de correo como **Gmail, Outlook, Yahoo, AOL, entre otros**. 

## 📌 Características

✅ **Diseño moderno y profesional**  
✅ **Totalmente responsiva** en diferentes dispositivos  
✅ **Enlaces a redes sociales y medios de contacto**  
✅ **Código ligero y limpio**  
✅ **Colores y tipografías personalizadas**  
✅ **Modularidad** con `style.css` para fácil actualización  

---

## 🚀 **Cómo usar la firma**
### 📧 **1. Configurar en tu cliente de correo**
1. **Abre la configuración** de tu cliente de correo:
   - **Gmail**: Configuración > General > Firma  
   - **Outlook**: Opciones > Correo > Firma  
   - **Yahoo**: Configuración > Firma  
   - **AOL**: Preferencias > Firma  

2. **Abre el archivo `signature.html`** en tu navegador.

3. **Selecciona toda la firma** (`Ctrl + A`) y **cópiala** (`Ctrl + C`).

4. **Pega la firma** en la configuración de firma de tu correo.

5. **Guarda los cambios** y realiza una prueba enviándote un correo.

---

## 🎨 **Personalización**
Si deseas modificar la firma, edita los siguientes archivos:

### ✏ **Modificar texto e información de contacto**
- Edita el archivo **`signature.html`** y cambia los valores correspondientes (nombre, cargo, correo, teléfono, etc.).

### 🎨 **Modificar estilos (colores, tamaños, fuentes)**
Si deseas personalizar la apariencia de la firma, edita el archivo **`style.css`**.

#### 🔹 **Ejemplo de cambios en colores**
```css
.name {
    color: #FF5733; /* Cambiar color del nombre */
}
.contact a {
    color: #1D72B8; /* Cambiar color de los enlaces de contacto */
}
```

Después de hacer los cambios, **guarda el archivo y recarga la firma en tu cliente de correo**.

## 🖼 **Modificar la imagen de perfil**
Si deseas cambiar la imagen de perfil, sigue estos pasos:

1. **Reemplaza `photo.jpg`** con la nueva imagen de perfil en el repositorio.  
2. Asegúrate de que el nuevo archivo tenga el **mismo nombre (`photo.jpg`)** o actualiza la ruta en `signature.html`:  

```html
<img src="https://raw.githubusercontent.com/tzurielpo/emailsignature/signature/photo.jpg" alt="Tzuriel Plata">
```

Después de hacer esto, la nueva imagen aparecerá automáticamente en la firma.

---

## 🔗 **Recursos Utilizados**
- **Tipografía:** [Montserrat](https://fonts.google.com/specimen/Montserrat) y [Amsterdam One](https://www.creativefabrica.com/)  
- **Íconos:** [FontAwesome](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css)  
- **Alojamiento del CSS:** [GitHub + jsDelivr](https://cdn.jsdelivr.net/)  
- **Optimización de imágenes:** [TinyPNG](https://tinypng.com/)  

---

## 🛠 **Problemas y Solución de Errores**
### ❓ **1. No se carga la hoja de estilos**
✔ **Solución:** Asegúrate de que el enlace a `style.css` en el HTML es correcto:
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/tzurielpo/emailsignature@main/style.css">
```
Si la hoja de estilos sigue sin cargarse, prueba en **otro navegador o borra la caché**.

### ❓ **2. Los íconos de redes sociales no aparecen**
✔ **Solución:** Confirma que FontAwesome está cargando correctamente en el `<head>` del HTML:
```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
```

---
