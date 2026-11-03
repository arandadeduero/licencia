# Licencia del software del Ayuntamiento de Aranda de Duero

**Todo el código del Ayuntamiento de Aranda de Duero se publica bajo la [Licencia Pública de la Unión Europea (EUPL) v1.2](LICENSE)**, salvo que un repositorio indique expresamente otra cosa.

Esto incluye el software que desarrolla el propio Ayuntamiento y el que se encarga con fondos municipales, publicado en [github.com/arandadeduero](https://github.com/arandadeduero). Si el Ayuntamiento paga por su desarrollo, la ciudadanía es su propietaria legítima.

## Qué permite la EUPL

Cualquier persona, empresa o administración puede **usar, estudiar, copiar, modificar y redistribuir** este código, también con fines comerciales. A cambio:

- Hay que **mantener el aviso de autoría** y la licencia.
- Si se **distribuye una versión modificada** (o se ofrece como servicio en red), hay que publicar su código con la misma licencia o con una de las [licencias compatibles](https://interoperable-europe.ec.europa.eu/collection/eupl/matrix-eupl-compatible-open-source-licences) (GPL, AGPL, LGPL, MPL, EPL…).
- El código se ofrece **tal cual**, sin garantía.

## Por qué la EUPL

- La creó la **Comisión Europea** para el software de las administraciones públicas.
- Tiene **validez legal en las 23 lenguas oficiales de la UE**, también en español: [texto oficial en español](https://interoperable-europe.ec.europa.eu/collection/eupl/eupl-text-eupl-12).
- Está pensada para el derecho europeo y es **compatible con las licencias libres más usadas**, así que el código se puede combinar con otros proyectos.
- Obliga a que las mejoras vuelvan a ser públicas: lo que se paga con dinero público sigue siendo público.
- Facilita que **otros ayuntamientos y administraciones reutilicen** las aplicaciones, como prevé el artículo 157 de la Ley 40/2015, de Régimen Jurídico del Sector Público.

## Datos y contenidos

La EUPL es una licencia de software. Los **datos abiertos** y los contenidos que publican estos proyectos (presupuestos, contratos, textos…) se publican bajo **[Creative Commons Reconocimiento 4.0 (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.es)**, la licencia habitual para la reutilización de la información del sector público (Ley 37/2007). Cada repositorio indica cómo citarlos.

## Excepciones

Algunos repositorios parten de proyectos de terceros y **mantienen la licencia del proyecto original**, porque el Ayuntamiento no puede cambiarla:

| Repositorio | Licencia | Motivo |
|---|---|---|
| [easyappointments](https://github.com/arandadeduero/easyappointments) | GPL-3.0 | Adaptación de [Easy!Appointments](https://github.com/alextselegidis/easyappointments) |
| [fiestas](https://github.com/arandadeduero/fiestas) | AGPL-3.0 (código) y CC BY-SA 4.0 (contenidos) | Adaptación del proyecto de [Aldea Pucela](https://github.com/aldeapucela/fiestas) |
| [bienestaranimal](https://github.com/arandadeduero/bienestaranimal) | CC BY-SA 4.0 | Adaptación del proyecto de [Aldea Pucela](https://github.com/aldeapucela/peluditos) |
| [wp-tema-arandadeduero](https://github.com/arandadeduero/wp-tema-arandadeduero) | GPL-2.0 o posterior | Un tema de WordPress es obra derivada de WordPress (GPL) y además parte de Underscores (GPL). El código EUPL del Ayuntamiento sí puede incorporarse al tema, porque la EUPL es compatible con la GPL |

Las librerías de terceros incluidas en cualquier repositorio, y los datos de OpenStreetMap (ODbL), conservan siempre su propia licencia.

## Cómo aplicarla en un repositorio nuevo

1. Copiar el fichero [`LICENSE`](LICENSE) de este repositorio en la raíz.
2. Añadir al README:

   ```markdown
   ## Licencia

   [Licencia Pública de la Unión Europea (EUPL) v1.2](LICENSE), © Ayuntamiento de Aranda de Duero. Es la licencia común de todo el software del Ayuntamiento: ver [arandadeduero/licencia](https://github.com/arandadeduero/licencia).
   ```

3. Si el proyecto tiene `package.json`, `composer.json` o similar, poner `"license": "EUPL-1.2"` (identificador SPDX).

## Contribuciones

Quien contribuya a un repositorio del Ayuntamiento acepta que su aportación se publique bajo la licencia de ese repositorio (EUPL-1.2, salvo las excepciones de arriba).

---

[arandadeduero.es](https://www.arandadeduero.es)
