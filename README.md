# Mercados de Abastos en Riesgo por Efectos del FEN 2026-2027

Dashboard interactivo (un solo archivo HTML, con todos los datos incluidos) para identificar
mercados de abastos en riesgo ante inundaciones y movimientos en masa asociados al Fenómeno
El Niño, a partir del CENAMA 2016 (INEI/PRODUCE) y el Estudio de Escenarios de Riesgo de
CENEPRED.

## Publicarlo en GitHub Pages (sin usar la terminal)

1. Entra a [github.com](https://github.com) e inicia sesión (o crea una cuenta gratuita).
2. Arriba a la derecha, haz clic en el **+** y elige **New repository**.
   - Ponle un nombre, por ejemplo `mercados-riesgo-fen`.
   - Puede ser público o privado (si es privado, GitHub Pages solo está disponible en
     algunos planes; si no estás segura, elígelo **público**).
   - Haz clic en **Create repository**.
3. En la página del repositorio recién creado, haz clic en **uploading an existing file**
   (o en **Add file → Upload files**).
4. Arrastra el archivo `index.html` de esta carpeta (y el `README.md` si quieres) a la
   ventana del navegador, y haz clic en **Commit changes**.
5. Ve a la pestaña **Settings** del repositorio → en el menú izquierdo, **Pages**.
6. En "Build and deployment" → "Source", elige **Deploy from a branch**.
7. En "Branch", elige `main` (o `master`) y la carpeta `/ (root)`, luego **Save**.
8. Espera 1-2 minutos. GitHub te mostrará la URL pública, algo como:
   `https://<tu-usuario>.github.io/mercados-riesgo-fen/`
9. Comparte esa URL — se abrirá en cualquier computador sin necesidad de descargar nada.

## Actualizar el dashboard más adelante

Cuando tengas una nueva versión del archivo (por ejemplo si te la vuelvo a generar con
datos actualizados), solo tienes que repetir el paso 3-4: **Add file → Upload files**,
subir el nuevo `index.html` reemplazando al anterior, y hacer **Commit changes**. GitHub
Pages se actualiza solo en 1-2 minutos.

## Alternativa con git (opcional, para quien prefiera la terminal)

```bash
cd mercados-riesgo-fen        # carpeta donde clonaste el repo vacío
cp /ruta/a/index.html .
git add index.html
git commit -m "Actualiza dashboard"
git push
```
