# Hello world javascript action

Esta acción imprime por pantalla "Hola munda" u "Hola" + el nombre de la persona a la que quiero saludar.

## Inputs

### `who-to-greet`

**Required** El nombre de la persona a la que quieres saludar. Por defecto `"World"`.

## Outputs

### `time`

La hora a la que te saludó.

## Ejemplo de uso

uses: actions/hello-js-action@v1
with:
  who-to-greet: 'Mona the Octocat'