# Milimetrich Public Schemas

Este diretorio documenta os padroes publicos usados pelo Milimetrich Public Cloud.

Todos os manifests publicos devem declarar:

* `schema`: nome publico e estavel do contrato de dados.
* `schema_version`: versao semantica do contrato.
* `status`: um dos valores `draft`, `active`, `legacy`, `reserved` ou `deprecated`.
* `public`: sempre `true` para arquivos servidos por este GitHub Pages.
* `key`: identificador oficial publico de grupos, definicoes, presets e outros itens versionados.
* `labels` e `descriptions`: textos preparados por locale, como `pt-BR` e `en-US`.
* `validation`: regras publicas de tipo, obrigatoriedade, limites, passos e formatos.
* `visibility`: regras publicas para exibir ou ocultar campos conforme contexto.
* `assets`: referencias futuras para imagens, videos e outros assets publicos.

O campo `id` pode existir temporariamente em manifests draft como alias de compatibilidade, mas `key` e o identificador oficial para novos consumidores.

Dados privados nunca entram no GitHub Pages. Nao colocar login, senha, token, licenca, preferencias pessoais de usuario, dados privados ou projetos privados neste repositorio.
