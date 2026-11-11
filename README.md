# Documentos legales de FeliSanto

> **BORRADOR privado.** Pendiente de la revisión del agente `legal` y de la
> aprobación de Javier. No se publica hasta que Javier lo apruebe.

Política de privacidad y licencias de la aplicación **FeliSanto**, un santoral
con onomásticas y avisos para felicitar a tiempo, para Android.

Esta carpeta existe para servir esos documentos por HTTPS con una URL pública y
estable, que es requisito de Google Play y del mensaje de consentimiento de
AdMob. Será el repositorio `felisanto-legal`, que **no contiene el código de la
aplicación** (en el repositorio de la app, `legal/` está en el `.gitignore`).

| Documento | |
|---|---|
| Índice | [index.html](index.html) |
| Política de privacidad (castellano) | [privacidad-es.html](privacidad-es.html) |
| Política de privadesa (català) | [privadesa-ca.html](privadesa-ca.html) |
| Licencias de código abierto y datos del santoral | [licencias.html](licencias.html) |

La versión de referencia es la castellana; la catalana es su traducción, de la
misma versión y con su misma fecha. Cuando cambie la castellana, hay que cambiar
las dos a la vez: la app abre `privacidad-es.html` o `privadesa-ca.html` según
su idioma (`AppConfig.privacyDocument`, en `app/lib/core/config.dart` del
repositorio de la app). Ese código ya prevé `privacy-it.html` para el italiano
de la v1.1: hay que crearla antes de publicar esa versión.

Las dos políticas llevan la marca de borrador (`<p class="borrador">`, debajo de
la fecha, y su regla en el `<style>`). Se quita de las dos al publicarlas.

Cuando Javier lo apruebe, se publicará con GitHub Pages desde la rama `main` en
`https://demual.github.io/felisanto-legal/` (el `PRIVACY_URL` de la build de
Google Play: si acaba en `/`, la app le añade el fichero de su idioma). El
historial de commits servirá además como registro de qué decía la política en
cada momento.

---

FeliSanto · JR Soft, nombre comercial de Javier Román Sáez · `com.jrsoft.felisanto`
