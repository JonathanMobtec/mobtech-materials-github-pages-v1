# Milimetrich Public Cloud

Este repositorio e o CDN publico e versionado do Milimetrich via GitHub Pages.

Ele deve conter somente dados e assets publicos: catalogos, definicoes publicas, presets publicos, releases e arquivos estaticos publicados.

Nao colocar aqui:

* login
* senha
* token
* licenca
* preferencias pessoais de usuario
* dados privados
* projetos privados

Dados privados devem ficar em backend seguro separado.

## Servicos publicos

O arquivo principal de descoberta e `index.json`.

Servicos declarados:

* `materials_v1_legacy`: catalogo legado v1 preservado em `materials_manifest.json`.
* `materials_v2`: catalogo publico ativo em `materials-v2/`.
* `definitions_v1`: definicoes publicas versionadas em `definitions-v1/`.
* `presets_v1`: espaco reservado para presets publicos em `presets-v1/`.
* `releases`: espaco reservado para metadados publicos de releases em `releases/`.

## Schemas

Os padroes publicos de manifests ficam documentados em `schemas/README.md`.
