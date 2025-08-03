

## ✅ Historias de Usuario **Centro Restobar**


### 🔹 1. Historia de Usuario – Explorar la carta general

**Como** comensal nuevo,
**quiero** ver una carta digital clara y organizada por categorías,
**para** decidir fácilmente lo que quiero pedir antes de llegar al restaurante.

#### Criterios de Aceptación

* Debe haber una **página principal (Home)** con acceso a las tres categorías: *Entradas*, *Platos de fondo* y *Bebidas*.
* El diseño debe adaptarse correctamente a celulares y pantallas grandes.
* El **menú de navegación** debe ser visible y usable en todas las páginas.

---

### 🔹 2. Historia de Usuario – Ver Entradas

**Como** usuario con poco tiempo,
**quiero** ver solo las entradas disponibles con imágenes y precios,
**para** decidir rápidamente si quiero pedir alguna.

#### Criterios de Aceptación

* La página `/entradas.html` debe mostrar al menos 4 entradas en tarjetas.
* Cada tarjeta debe tener **imagen, nombre y precio**.
* Las tarjetas deben estar organizadas en grilla responsiva.
* Efecto hover en tarjetas para mejor experiencia visual.

---

### 🔹 3. Historia de Usuario – Ver Platos de fondo

**Como** comensal con hambre 😋,
**quiero** ver los platos de fondo disponibles con fotos y precios,
**para** elegir lo que más me provoque.

#### Criterios de Aceptación

* La página `/platos.html` debe contener mínimo 4 platos de fondo.
* Cada tarjeta debe incluir imagen, nombre y precio.
* Deben aplicarse clases utilitarias de Tailwind para espaciado, sombra, bordes, etc.

---

### 🔹 4. Historia de Usuario – Ver Bebidas (con restricción de edad)

**Como** cliente,
**quiero** ver la lista de bebidas,
**pero** que se valide si soy mayor de edad,
**para** saber si puedo pedir bebidas alcohólicas.

#### Criterios de Aceptación

* Al ingresar a `/bebidas.html`, debe aparecer un `prompt` con el año de nacimiento.
* Según el cálculo de edad:

  * Si es **18 o más**, alerta: “Puedes escoger también las bebidas con alcohol.”
  * Si es **menos de 18**, alerta: “No puedes escoger bebidas con alcohol.”
* El contenido de bebidas debe mostrarse igual para ambos, pero el mensaje marca la diferencia.

---

### 🔹 5. Historia de Usuario – Acceder desde el celular

**Como** usuario móvil,
**quiero** ver la carta sin tener que hacer zoom o desplazarme lateralmente,
**para** navegar fácilmente desde mi teléfono.

#### Criterios de Aceptación

* Todas las páginas deben ser 100% responsivas.
* El menú debe convertirse en un menú adaptable (hamburguesa opcional si se desea).
* Las tarjetas deben reorganizarse verticalmente en pantallas pequeñas.

---

### 🔹 6. Historia de Usuario – Contacto y redes

**Como** visitante curioso,
**quiero** ver los datos de contacto y redes sociales del restobar,
**para** seguirlos o hacer una reserva.

#### Criterios de Aceptación

* El `footer` debe contener:

  * Dirección o forma de contacto (correo, teléfono).
  * Enlaces a redes sociales (ej: Facebook, Instagram).
  * Texto de copyright como “© Centro Restobar 2025”.



Con eso claro, arrancamos con el diseño estructural y el código 🧠💻
