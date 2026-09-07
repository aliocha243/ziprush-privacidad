# Política de privacidad de Zip Rush

Este repositorio existe por un solo motivo: **Google Play exige una URL pública** con la
política de privacidad de la aplicación, y AdMob la pide también para el mensaje de
consentimiento de la UE.

La página publicada es `index.md`, servida por GitHub Pages.

## Cómo actualizarla

La fuente de verdad es el proyecto del juego (`docs/privacidad.md`). Acá vive una copia
idéntica. Para actualizar:

```sh
cp <proyecto>/docs/privacidad.md index.md
git commit -am "Actualizar la política"
git push
```

Y cambiar la fecha de "Última actualización" dentro del archivo — la política misma dice que
se cambia cuando cambia lo que la aplicación hace con los datos.

## Qué NO va acá

El código del juego. Este repositorio es público **solo** para que la URL sea pública; no
lleva ni el código, ni las claves de firma, ni ningún token.
