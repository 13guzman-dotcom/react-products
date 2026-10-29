# Laboratorio: Desarrollo Web 2 - Practicando con Framework de JavaScript

## Datos del Estudiante
- **Nombre Completo:** José Daniel Guzmán Avilés
- **Carrera / Técnico:** TSU Desarrollo de Software en Código Abierto
- **Asignatura:** Desarrollo Web 2
- **Tutor:** Vladimir Mate
- **Periodo:** 26 de Octubre al 01 de Noviembre

---

## Descripción del Proyecto
Aplicación desarrollada en **React** construida con **Vite** para consumir y gestionar los recursos REST de **DummyJSON** (`https://dummyjson.com/products`).

### Funcionalidades Implementadas
1. **Navegación y Rutas**: Uso de `react-router-dom` con rutas para Inicio (`/`), Listado de Productos (`/products`) y Detalle individual (`/products/:id`).
2. **Servicio Centralizado de Productos**: Módulo `productService.js` con funciones asíncronas para GET, POST, PUT y DELETE.
3. **Listado y Tarjetas Reutilizables**: Componentes `ProductList` y `ProductCard`.
4. **Búsqueda**: Filtro dinámico con `searchProducts(query)`.
5. **Filtrado por Categorías**: Menú desplegable con categorías obtenidas de la API y filtrado mediante `getProductsByCategory(category)`.
6. **Paginación**: Navegación por páginas con control de límites y cálculo de total de páginas.
7. **Creación (POST)**: Formulario interactivo que agrega productos a la interfaz.
8. **Actualización (PUT)**: Edición de campos existentes con recarga de datos en el formulario.
9. **Eliminación (DELETE)**: Eliminación simulada con actualización del estado local.
10. **Manejo de Estados y Estilos**: Estados de carga (`loading`), control de errores (`error`) y diseño adaptado en `src/styles/main.css`.

---

## Instrucciones de Ejecución

1. **Instalar dependencias:**
   ```bash
   npm install
   ```

2. **Ejecutar servidor de desarrollo:**
   ```bash
   npm run dev
   ```

3. **Compilar para producción:**
   ```bash
   npm run build
   ```
