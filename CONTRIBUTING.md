# Guía de colaboración

Puedes [crear una _pull request_](https://help.github.com/en/articles/creating-a-pull-request) con la documentación que incluimos a continuación o [crear un _issue_](https://github.com/comunidad-tecnologica/valencia/issues/new).

## Añadir una comunidad

Los datos de las comunidades están en `_data/communities.yaml`.

Para añadir una nueva comunidad siguiendo este formato:

```
- title: 
  web: 
  twitter-alias: 
  meetup-url:
```

No es necesario que incluyas todos los datos para cada comunidad: web, alias de Twitter o URL de Meetup. Tal vez sólo dispone de uno o dos de esos datos.

## Añadir un evento anual

El listado se encuentra en el fichero `index.md`.

## Añadir cualquier otro dato de interés

Adelante, las ideas son bienvenidas :wink:

## Probarlo en local

Construcción en local para verlo en http://localhost:4000 :

```
$> bundle exec jekyll serve
``` 
