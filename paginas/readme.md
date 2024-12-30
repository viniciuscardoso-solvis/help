## Sumário

- [Heroku WEB](#-heroku)

## Heroku

No projeto de reserva de cardápio, utilizamos o heroku para hospedar sistema web. Aqui tem um passo a passo a passo para fazer o build.

Para fazer o build web

```sh
flutter build web
```

depois de fazer o build temos que ir para a pasta ` /build/web`

Na pasta descrita anteriormente, verificar se existe um repositório GIT:

```sh
git init
```

Seria legal fazer login no heroku e apontar para o repositório:

```sh
heroku login

&

heroku git:remote -a meal-reservation
```

Agora so fazer o processo normal de push

```sh
    git add .
    git commit -m "update"

    git push heroku master

    ou

    git push heroku master --force
```

##

## Build APK

Para fazer o build do APK, temos que rodar o seguinte comando:

```sh
    flutter build apk
```
