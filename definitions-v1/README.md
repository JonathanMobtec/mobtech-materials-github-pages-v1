# Milimetrich Public Cloud - definitions-v1

Status: draft

Este diretório contém o contrato público inicial das definições do plugin Milimetrich.

## v1.4 - Inventário completo em draft

Esta revisão mantém os grupos já publicados (`prateleiras`, `portas` e `gavetas`) e expande o `definitions-v1` para cobrir todas as 92 chaves conhecidas no inventário interno do plugin.

A intenção desta versão é criar um contrato público técnico e auditável, ainda em `draft`, sem congelar textos, limites ou decisões comerciais finais.

Resultado esperado após sincronizar no plugin v3.242:

- grupos públicos em overlay: 13
- campos públicos totais: 92
- campos Public Cloud puro: 0
- fallback interno seguro: SIM
- alteração de motor/receitas/valores: NAO

## Grupos publicados

- `medidas_gerais`
- `estrutura_corpo`
- `prateleiras`
- `portas`
- `gavetas`
- `divisores`
- `painel_ripado`
- `tamponamentos`
- `fitagem`
- `usinagem`
- `fixadores_dispositivos`
- `geladeira`
- `folgas_recuos`

## Regras de segurança

- Este manifesto é público e não deve conter login, senha, token, licença, preferências pessoais ou dados privados.
- O Public Cloud define contrato e metadados públicos.
- O plugin continua responsável por cachear, validar e mesclar localmente.
- O backend futuro será responsável por preferências privadas de usuário/equipe.
- Esta revisão não altera motor, receitas, materiais, exportadores, Scale Guard ou Undo.
- Campos ainda incertos permanecem com status `draft` e metadados conservadores.

## Fluxo de teste recomendado

Depois de publicar no GitHub Pages:

1. Abrir o plugin Milimetrich no SketchUp.
2. Ir em Técnico > Public Cloud.
3. Clicar em `Sincronizar definitions-v1`.
4. Clicar em `Status Public Cloud`.
5. Clicar em `Inspecionar origem das definições`.
6. Clicar em `Gerar relatório de origem`.
7. Rodar o teste rápido do plugin.

Resultado esperado:

- campos resolvidos no catálogo: 92
- grupos resolvidos: 13
- campos públicos totais: 92
- campos Public Cloud puro: 0
- teste rápido: 21 OK / 0 falhas
