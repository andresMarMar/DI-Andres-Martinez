# Ficha de mi aplicación · Hito 0

- **Alumno/a:** Andrés Martínez Martínez
- **Temática:** Gestión de catálogo y ventas de artículos de segunda mano (ResellFlow)
- **Qué gestiona:** Artículos

## Campos

| # | Campo | Tipo de dato | Componente | Ejemplo de valor / opciones |
|---|-------|--------------|------------|-----------------------------|
| 1 | Título del artículo | `texto` | `campo de texto` | Sudadera con cremallera negra |
| 2 | Marca | `texto` | `campo de texto` | Nike, Zara, Adidas |
| 3 | Stock / Unidades | `entero` | `selector numérico` | 1, 2, 5 |
| 4 | Precio de venta (€) | `decimal` | `campo de texto` | 24.50, 15.00 |
| 5 | Categoría | `lista` | `lista desplegable` | Ropa, Calzado, Electrónica, Accesorios |
| 6 | Estado del artículo | `opción` | `botones de opción` | Nuevo con etiqueta, Muy bueno, Usado |
| 7 | Disponible para envío | `sí/no` | `casilla` | Marcada (sí) / Desmarcada (no) |

## Pantallas

| Pantalla | Foto |
|----------|------|
| Inicio de sesión | `bocetos/1_inicio_sesion.png` |
| Ventana principal | `bocetos/2_ventana_principal.png` |
| Formulario de alta | `bocetos/3_formulario.png` |

### Ventana principal

- **Menús y sus opciones:**
  - Archivo: Salir
  - Inventario: Dashboard, Inventario, Añadir producto, Ventas
  - Ayuda: Acerca de
- **Columnas de la tabla:** ID, Artículo, Categoría, P. Venta, Estado

### Qué hace cada botón

- **Iniciar sesión:** Valida las credenciales introducidas y abre la ventana principal de la aplicación.
- **Registrarse:** Abre el flujo o ventana para crear una nueva cuenta de usuario.
- **Cerrar sesión:** Cierra la sesión actual y vuelve a la pantalla de inicio de sesión.
- **+ Nuevo artículo:** Abre el formulario para dar de alta un nuevo artículo en el catálogo.
- **Guardar artículo:** Comprueba que los campos obligatorios estén rellenos y guarda el artículo en la lista.
- **Cancelar:** Descarta los cambios del formulario y regresa a la vista anterior sin guardar.

### Mensajes

- Si el usuario o la contraseña están mal: «El usuario o la contraseña no son correctos. Revisa los datos e inténtalo de nuevo.»
- Si falta un campo obligatorio en el formulario: «Completa los campos obligatorios para guardar el artículo.»