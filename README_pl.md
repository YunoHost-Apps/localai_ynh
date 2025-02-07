<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# LocalAI dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/localai)](https://ci-apps.yunohost.org/ci/apps/localai/)
![Status działania](https://apps.yunohost.org/badge/state/localai)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/localai)

[![Zainstaluj LocalAI z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=localai)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację LocalAI na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

LocalAI is the free, Open Source OpenAI alternative. LocalAI act as a drop-in replacement REST API that’s compatible with OpenAI (Elevenlabs, Anthropic... ) API specifications for local AI inferencing. It allows you to run LLMs, generate images, audio (and not only) locally or on-prem with consumer grade hardware, supporting multiple model families. Does not require GPU.


**Dostarczona wersja:** 2.25.0~ynh2

## Zrzuty ekranu

![Zrzut ekranu z LocalAI](./doc/screenshots/331878853-20b5ccd2-8393-44f0-aaf6-87a23806381e.png)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://localai.io/>
- Repozytorium z kodem źródłowym: <https://github.com/mudler/LocalAI>
- Sklep YunoHost: <https://apps.yunohost.org/app/localai>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/localai_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/localai_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/localai_ynh/tree/testing --debug
lub
sudo yunohost app upgrade localai -u https://github.com/YunoHost-Apps/localai_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
