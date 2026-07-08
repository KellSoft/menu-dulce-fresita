# 🍓 Dulce Fresita - Menú Digital

Menú interactivo desarrollado para el emprendimiento **Dulce Fresita**, diseñado para facilitar el proceso de compra de los clientes. Permite explorar el menú, agregar productos al carrito, seleccionar tamaños y enviar el pedido directamente por **WhatsApp** de forma rápida, organizada y sencilla.

---

# ✨ Características

- 🍓 Menú completo organizado por categorías (frutas, waffles, crepas, malteadas, bebidas, etc.).
- 🛒 Selección de productos con diferentes tamaños y precios.
- 📦 Carrito de compras flotante con actualización en tiempo real.
- 💬 Envío automático del pedido mediante WhatsApp.
- 📝 Campo de observaciones opcional (ej.: *sin crema, sin maní*).
- 📍 Campo de dirección opcional para pedidos a domicilio.
- 📱 Información del negocio:
  - Nequi
  - Horarios
  - Ubicación en Google Maps
  - Redes sociales
- 📲 Diseño responsive optimizado para dispositivos móviles.

---

# 🛠️ Tecnologías utilizadas

- HTML5
- CSS3
  - Variables CSS
  - Flexbox
  - Animaciones
- JavaScript (ES6)
  - Manipulación del DOM
  - Eventos
  - Renderizado dinámico
- Google Fonts
  - Yellowtail
  - Baloo 2
  - Nunito Sans
- WhatsApp API (`wa.me`)

---

# 📂 Estructura del proyecto

```text
├── index.html          # Página principal del menú
├── README.md           # Documentación del proyecto
```

---

# ⚙️ Funcionalidades principales

## 🛒 Agregar productos al carrito

- Selecciona un producto para añadirlo al carrito.
- Los botones muestran una animación indicando que el producto fue agregado correctamente.
- El carrito se actualiza automáticamente.

---

## 📦 Carrito de compras

El carrito permite:

- Ver todos los productos agregados.
- Modificar cantidades (+ / -).
- Visualizar el precio unitario.
- Calcular el total automáticamente.
- Abrir o cerrar el carrito mediante la barra flotante inferior.

---

## 💬 Envío del pedido por WhatsApp

Al finalizar el pedido se genera automáticamente un mensaje con:

- Lista de productos.
- Cantidades.
- Precio total.
- Observaciones (opcional).
- Dirección de entrega (opcional).

Posteriormente se abre el chat del negocio en WhatsApp listo para enviar.

---

# 📱 Diseño Responsive

La interfaz está optimizada principalmente para dispositivos móviles.

Características:

- Menú horizontal con desplazamiento.
- Tarjetas adaptables.
- Carrito flotante responsive.
- Botones optimizados para pantallas táctiles.

---

# 🍫 Toppings y adicionales

Los toppings se encuentran definidos en el arreglo:

```javascript
const TOPPINGS = [
    "Oreo $2.000",
    "Queso $2.000",
    "Mini chips $2.500",
    // ...
];
```

Esta sección aparece automáticamente al final del menú.

---

# 🚀 Cómo utilizar

1. Abrir el archivo **index.html**.
2. Navegar entre las categorías.
3. Agregar productos al carrito.
4. Abrir el carrito mediante la barra inferior.
5. Ajustar cantidades.
6. Escribir observaciones (opcional).
7. Escribir la dirección de entrega (opcional).
8. Presionar **Enviar por WhatsApp**.

---

# 💡 Mejoras futuras

Algunas funcionalidades que podrían añadirse:

- Guardar el carrito utilizando **localStorage**.
- Modo oscuro.
- Traducción al inglés.
- Panel administrativo.
- Integración con un backend.
- Historial de pedidos.
- Notificaciones para el negocio.
- Pasarela de pagos.
- Cupones y promociones.

---

# 📄 Licencia

Este proyecto es de uso para el local Dulce Fresita.

---

# ❤️ Créditos

Desarrollado por:

- **Kellyn Andrea Aramburo Valencia**
- **Juan Camilo Posada**

Hecho con ❤️ para apoyar a los emprendedores que endulzan el día a día.