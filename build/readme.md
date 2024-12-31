# :bookmark_tabs: Sumário

- [:cloud: Heroku WEB](#-heroku)
- [:package: Build APK](#-build-apk)

---

## :cloud: Heroku

No projeto de **reserva de cardápio**, utilizamos o Heroku para hospedar o sistema web. Aqui está um passo a passo para fazer o **build**:

### :hammer_and_wrench: Passo a passo para build web

1. **Rodar o comando** para gerar o build:
   ```sh
   flutter build web
   ```
2. Navegar para a pasta `/build/web` e verificar se existe um repositório GIT:

```sh
   git init
```

3. Fazer login no Heroku e apontar para o repositório:

```sh
    heroku login
    heroku git:remote -a meal-reservation
```

4. Executar o processo de push:

```sh
    git add .
    git commit -m "update"
    git push heroku master

    # Caso precise forçar:
    git push heroku master --force

```

## :package: Build APK

Para fazer o build do APK, execute o seguinte comando:

```sh
flutter build apk
```
