# laiglesia.cc

Sitio de La Iglesia Comunidad Cristiana — Mundelein, IL.
HTML y CSS estaticos, sin build.

## Archivos

    index.html      la pagina completa
    styles.css      los estilos (la paleta esta arriba del archivo)
    paletas.css     paletas alternativas, para cambiar el bloque :root
    .nojekyll       desactiva el procesado Jekyll
    img/            logo, iconos y fotos

## Paleta

Tomada del material grafico de los ministerios:
verde azulado #4A837D, terracota #CD7B56, ladrillo #AC554C, olivo #9BA103.
Para probar otra, reemplaza el bloque :root de styles.css por uno de paletas.css.

## Imagenes

    logo.png              logo completo, para fondos claros
    logo-blanco.png       igual pero con el texto en blanco (encabezado oscuro)
    favicon.png           solo el icono, 512x512
    apple-touch-icon.png  180x180
    congregacion.jpg      foto del hero, 2000x1125
    entrada.jpg           la entrada del edificio, 760x1013
    pastores.jpg          Homero y Claudia, 1500x2000
    og.jpg                1200x630, vista previa al compartir

## Publicar en GitHub Pages

1. Subir estos archivos a la rama `main`.
2. Settings -> Pages -> Source: *Deploy from a branch*, `main` / `/ (root)`.

Para el dominio propio, cuando este listo: agregar un archivo `CNAME` con
`laiglesia.cc`, ponerlo en Settings -> Pages -> Custom domain, marcar
**Enforce HTTPS**, y en el registrador reemplazar los registros de Wix por:

    A      @      185.199.108.153
    A      @      185.199.109.153
    A      @      185.199.110.153
    A      @      185.199.111.153
    CNAME  www    joseltrejo.github.io

Verificar los registros A contra la documentacion de GitHub al momento del
cambio; han cambiado antes.

## Pendientes

- [ ] Confirmar la direccion postal para cheques (Grayslake o Mundelein)
- [ ] Poner un correo de la iglesia; `info@laiglesia.cc` es marcador
- [ ] Reemplazar el enlace de Tithe.ly por el de la cuenta de la iglesia
- [ ] Crear las paginas internas; los enlaces del menu apuntan a anclas
