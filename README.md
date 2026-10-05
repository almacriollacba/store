# Alma Criolla — Panel privado

Panel mobile-first para administrar el emprendimiento desde dos celulares.

## Qué incluye
- Login compartido mediante Supabase Auth.
- Dashboard con dinero, ganancia, por cobrar y pedidos pendientes.
- Pedidos: posibles, confirmados, en camino, entregados y cancelados.
- Stock: alta, edición, eliminación y botones +1 / -1.
- Alertas cuando un producto está por debajo del stock mínimo.
- Finanzas: ingresos, gastos y resultado.
- Metas.
- Compras y proveedores.

## Configuración
1. Crear un proyecto en Supabase.
2. Abrir SQL Editor y ejecutar `supabase.sql`.
3. Crear un usuario en Authentication > Users.
4. Abrir `app.js` y reemplazar:
   - `PEGÁ_ACÁ_TU_SUPABASE_URL`
   - `PEGÁ_ACÁ_TU_SUPABASE_ANON_KEY`
5. Subir los archivos a GitHub.
6. Activar GitHub Pages.

No pongas la contraseña en `app.js`. La contraseña se administra desde Supabase Auth.

## Importante
Esta versión usa una sola base de datos: cualquier cambio hecho por cualquiera de los dos aparece para ambos.
