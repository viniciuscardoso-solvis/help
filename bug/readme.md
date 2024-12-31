# Sumário

- [Heroku WEB](#-Bug)

## Bug

Tenho um problema para buildar o projeto do Flutter, tenho que fazer os seguintes passos.

Abrir primeiro o arquivo `Android/app/build.gradle`

```sh
    ndkVersion = "25.1.8937393"
```

Agora o arquivo `Android/gradle/wrapper/grandle-wrapper.properties `

```sh
    distributionUrl=https\://services.gradle.org/distributions/gradle-8.4-all.zip
```

Por último na pasta ` Android/settings.gradle`

```sh
    id "com.android.application" version "8.3.2" apply false
```

algo sugestivo agora, tava dando B.O. em uma das bibliotecas, se der algum problema, verifique se não é o `device_info_plus: 11.2.0`
