# Lego: SuperHero

Esta es una pagina de [Lego](https://luisariza.github.io/lego_superhero/) hecha con <ins>HTML</ins> y <ins>CSS</ins> puro, manipulé el DOM con <ins>JavaScript</ins> para poder agregarle un **modal** de los juguetes de Lego, le agregué **animaciones** para hacerlo llamativo a la vista y apliqué **Responsive Design** para los diferentes tamaños de pantalla.

Se integró la herramienta de [**Parcel**](https://parceljs.org/) para automatizar y optimizar el codigo.

## Runnning

Para iniciar el proyecto primero ejecuta:

```sh
npm install
```

Una vez instaladas las dependencias, inicia el proyecto:

```sh
npm start
```

Ahora ingresa en tu navegador http://localhost:2664/. Ya puedes hacer cambios al proyecto y verlos en tiempo real.

## Building

Si quieres enviar tu proyecto a producción ejecuta:

```sh
npm run build
```

Se creará automaticamaente una carpeta llamada "dist" donde estará el codigo **minificado** (_para que pese menos_).

## Deploy

Para subir el codigo a <ins>GitHub Pages</ins> solo ejecuta:

```sh
npm run deploy
```

Con esto, se creará una rama en tu repositorio (_gh-pages_) donde solo vivirá el codigo de la capreta "dist".

> Importante hacer **build** antes de desplegar, para tener el codigo optimizado.
