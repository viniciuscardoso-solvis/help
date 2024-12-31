# :bookmark_tabs: Sumário

- [:cloud: Heroku WEB](#-bug)

---

## :beetle: Bug

Tenho um problema para buildar o projeto do **Flutter**. Seguem os passos necessários:

1. **Editar** o arquivo: `Android/app/build.gradle`

   ```sh
   ndkVersion = "25.1.8937393"

   ```

2. Modificar o arquivo: `Android/gradle/wrapper/gradle-wrapper.properties`

   ```sh
   distributionUrl=https\://services.gradle.org/distributions/gradle-8.4-all.zip

   ```

3. Verificar o arquivo: `Android/settings.gradle`

   ```sh
   id "com.android.application" version "8.3.2" apply false
   ```

> Observação: Estava dando B.O. em uma das bibliotecas. Se acontecer de novo, verifique se não é o device_info_plus: 11.2.0.
