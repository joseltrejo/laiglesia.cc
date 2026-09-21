# laiglesia.cc

Sitio de La Iglesia Comunidad Cristiana — Mundelein, IL.
HTML y CSS estaticos, sin build.

## Archivos

    index.html    la pagina completa
    styles.css    los estilos (paleta del logo arriba del archivo)
    CNAME         el dominio para GitHub Pages
    .nojekyll     desactiva el procesado Jekyll
    img/          las imagenes (ver img/LEEME.txt)

## Publicar en GitHub Pages

1. Subir estos archivos a la rama `main`.
2. Settings -> Pages -> Source: *Deploy from a branch*, `main` / `/ (root)`.
3. Settings -> Pages -> Custom domain: `laiglesia.cc`, y marcar **Enforce HTTPS**.

DNS en el registrador, reemplazando los registros de Wix:

    A      @      185.199.108.153
    A      @      185.199.109.153
    A      @      185.199.110.153
    A      @      185.199.111.153
    CNAME  www    <usuario>.github.io

Verificar los registros A contra la documentacion de GitHub al momento del
cambio; han cambiado antes.

## Pendientes antes de lanzar

- [ ] Agregar las imagenes de `img/LEEME.txt`
- [ ] Confirmar la direccion postal para cheques (Grayslake o Mundelein)
- [ ] Poner un correo de la iglesia; `info@laiglesia.cc` es marcador
- [ ] Reemplazar el enlace de Tithe.ly por el de la cuenta de la iglesia
- [ ] Crear las paginas internas; los enlaces del menu apuntan a anclas
