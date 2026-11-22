# Rivera-contactos

Página de contactos de servicios públicos de Rivera (Uruguay) para mujeres en situación de violencia, apoyo social y trabajo.

Sitio: https://drenaldin.github.io/Rivera-contactos/

## Uso con el llavero QR

Los llaveros impresos con código QR apuntan a la dirección de arriba. El QR no se puede cambiar después de impreso; lo que se actualiza es esta página.

Para que los llaveros sigan funcionando:

- No renombrar ni borrar el repositorio (respetar mayúsculas: `Rivera-contactos`).
- No pasar el repositorio a privado ni desactivar GitHub Pages.
- Mantener `index.html` en la raíz de la rama `main`.
- No cambiar el usuario de GitHub `drenaldin`.

## Cómo actualizar un dato

1. Editar `index.html` (cada servicio es un bloque `<article class="card">`).
2. Cambiar el texto visible y también el enlace del botón (`tel:`, `https://wa.me/598...`, `mailto:`).
3. Hacer commit y push a `main`. GitHub Pages publica el cambio en uno o dos minutos.
4. Actualizar la tabla de fuentes de este archivo con la fecha de revisión.

Formato de enlaces: teléfonos fijos `tel:46236387`; WhatsApp `https://wa.me/598` + número de celular sin el 0 inicial (099 629 391 → `59899629391`).

## Logos

Cada tarjeta muestra una sigla. Si se agrega un archivo en `logos/` con estos nombres, se muestra el logo en lugar de la sigla:

| Archivo | Entidad |
|---|---|
| `logos/inmujeres.png` | Inmujeres (MIDES) |
| `logos/mides.png` | MIDES |
| `logos/inefop.png` | INEFOP |
| `logos/intendencia-rivera.png` | Intendencia de Rivera |

Usar solo logos descargados de los manuales de marca oficiales y respetar sus condiciones de uso. Imagen cuadrada o con fondo transparente, de unos 200 x 200 px.

## Fuentes de los datos

Última revisión: 22/11/2026.

| Servicio | Fuente |
|---|---|
| 0800 4141 / *4141 y horario | gub.uy, trámite "Servicio de atención a mujeres en situación de violencia basada en género" |
| Inmujeres Rivera (Servicio VBG) | Guía de recursos del MIDES (guiaderecursos.mides.gub.uy). Horario sin confirmar en otra fuente actual. |
| MIDES Oficina Territorial Rivera | gub.uy, MIDES, "Oficina Territorial Rivera" |
| INEFOP Rivera | inefop.uy, "Dónde estamos" |
| Oficina de Equidad y Género (Intendencia de Rivera) | gub.uy, MIDES, ficha del programa |

## Características de la página

- Un solo archivo HTML, sin dependencias salvo la fuente Poppins de Google Fonts (si no carga, usa la fuente del sistema).
- `noindex`: no aparece en buscadores; se llega por el QR.
- Botón "Salir rápido": reemplaza la página por Google sin dejarla en el historial de "atrás".
