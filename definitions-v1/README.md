# Milimetrich Public Cloud - definitions-v1

Status: draft

Este diretório contém o contrato público inicial das definições do plugin Milimetrich.

## v1.2 - Portas e folgas

Esta revisão mantém o grupo `prateleiras` e adiciona o grupo `portas`, com campos públicos iniciais para configuração de portas, frentes e folgas.

Campos adicionados no grupo `portas`:

- `espacamento_portas`
- `folga_frentes_lateral`
- `folga_frentes_topo`
- `folga_frentes_base`
- `puxador`
- `sentido_veio_frentes`

## Regras de segurança

- Este manifesto é público e não deve conter login, senha, token, licença, preferências pessoais ou dados privados.
- O Public Cloud define contrato e metadados públicos.
- O plugin continua responsável por cachear, validar e mesclar localmente.
- O backend futuro será responsável por preferências privadas de usuário/equipe.
- Esta revisão não altera motor, receitas, materiais, exportadores, Scale Guard ou Undo.

## Fluxo de teste recomendado

Depois de publicar no GitHub Pages:

1. Abrir o plugin Milimetrich no SketchUp.
2. Ir em Técnico > Public Cloud.
3. Clicar em `Sincronizar definitions-v1`.
4. Clicar em `Inspecionar origem das definições`.
5. Clicar em `Gerar relatório de origem`.
6. Rodar o teste rápido do plugin.

Resultado esperado após esta revisão:

- grupos públicos em overlay: 2
- campos públicos em overlay: 9
- campos apenas do Public Cloud: 0

