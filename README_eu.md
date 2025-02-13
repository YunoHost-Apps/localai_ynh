<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# LocalAI YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/localai)](https://ci-apps.yunohost.org/ci/apps/localai/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/localai)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/localai)

[![Instalatu LocalAI YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=localai)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek LocalAI YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

LocalAI is the free, Open Source OpenAI alternative. LocalAI act as a drop-in replacement REST API that’s compatible with OpenAI (Elevenlabs, Anthropic... ) API specifications for local AI inferencing. It allows you to run LLMs, generate images, audio (and not only) locally or on-prem with consumer grade hardware, supporting multiple model families. Does not require GPU.


**Paketatutako bertsioa:** 2.25.0~ynh2

## Pantaila-argazkiak

![LocalAI(r)en pantaila-argazkia](./doc/screenshots/331878853-20b5ccd2-8393-44f0-aaf6-87a23806381e.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://localai.io/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/mudler/LocalAI>
- YunoHost Denda: <https://apps.yunohost.org/app/localai>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/localai_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/localai_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/localai_ynh/tree/testing --debug
edo
sudo yunohost app upgrade localai -u https://github.com/YunoHost-Apps/localai_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
