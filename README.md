# 📩 Firma de Correo Electrónico

Este repositorio contiene una firma de correo electrónico, diseñada para ser utilizada en clientes de correo como **Gmail, Outlook, Yahoo, AOL, entre otros**. 

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
Si deseas **modificar la firma**, edita los siguientes archivos:

### ✏ **Modificar texto e información de contacto**
- Edita el archivo **`signature.html`** y cambia los valores correspondientes (nombre, cargo, correo, teléfono, etc.).

### 🎨 **Modificar estilos (colores, tamaños, fuentes)**
- Edita el archivo **`style.css`**.  
- El archivo está enlazado en el HTML, por lo que cualquier cambio en **`style.css`** se aplicará automáticamente a todas las firmas.

#### 🔹 **Ejemplo de cambios en colores**
En `style.css`, puedes cambiar el color del nombre y los enlaces:
```css
.name {
    color: #FF5733; /* Cambiar color del nombre */
}
.contact a {
    color: #1D72B8; /* Cambiar color de los enlaces de contacto */
}
