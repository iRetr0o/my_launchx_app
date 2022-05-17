# my_launchx_app (práctica 1 Semana 3)

En esta práctica realice:

- Cómo crear un nuevo proyecto de js:
    - En nuestro directorio donde vamos a trabajar debemos utilizar el comando `npm init` para crear nuestro archivo `package.json`(el directorio debe estar vacio)
- Cómo agregar dependencias nuevas a tu proyecto, dónde se guardan y cómo versionarlo correctamente:
    - Para agregar dependencias dentro de nuestro proyecto utilizamos el comando `npm install --save-dev jest` (indica que vamos a instalar la dependencia `jest` y que la agregue a nuestro ambiente de desarrollo `--save-dev`).
- Cómo exportar una clase y cómo importarla en otro archivo para usarla.
    - Existen muchas formas de exportar clases pero la utilizada en este repositorio es la de CommonJS.
- Cómo habilidar nuevos comandos con NPM en tu proyecto:
    - Para esto necesitamos ir al archivo `package.json` y debajo de la linea de `scripts` agregamos el comando que queremos habilitar.
- Cómo agregar una prueba de unidad básica con [jest](https://jestjs.io/).
```javascript
describe("Esto es una suite de pruebas", () => {
  test('Caso de prueba 1', () => {
    const result = 1 + 2 
    expect(result).toBe(10);
  });
})
```
> Prueba basica de jest

## ¿Como instalar las dependencias?
```
npm install
```

## Comandos habilitados
* `npm test`
* `npm start`

## Dependencias
| Nombre  | Versión | Documentación | 
| :------------: | :------------: | :------------: |
| Jest | 27.5.1  | <a href="https://jestjs.io/docs/27.x/getting-started" target="_blank"><img src="https://img.shields.io/badge/Jest-Documentation-brightgreen?style=for-the-badge&logo=jest"></a> |

Versión de Node: <a href="https://nodejs.org/docs/latest-v16.x/api/index.html" target="_blank">16.14.2</a>
