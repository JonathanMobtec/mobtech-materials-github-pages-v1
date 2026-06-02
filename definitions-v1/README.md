# Milimetrich Public Cloud - definitions-v1

Status: draft

Este diretório contém o contrato público inicial das definições do plugin Milimetrich.

## v1.3 - Gavetas e frentes de gaveta

Esta revisão mantém os grupos `prateleiras` e `portas`, e adiciona o grupo `gavetas`, com campos públicos iniciais para configuração de gavetas, frentes de gaveta, folgas e ferragens relacionadas.

Campos adicionados no grupo `gavetas`:

- `numero_gavetas`
- `altura_gaveta`
- `espacamento_frente_gaveta`
- `desconto_contrafrente`
- `folga_superior_gaveta`
- `folga_fundo_gaveta`
- `tipo_corredica_gaveta`
- `tipo_fundo_gaveta`

## Histórico recente

### v1.2 - Portas e folgas

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

- grupos públicos em overlay: 3
- campos públicos em overlay: 17
- campos apenas do Public Cloud puro: 0

Dados privados devem ficar em backend seguro separado.
