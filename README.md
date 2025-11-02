# notas-atletas

Projeto simples que calcula a média válida das notas de cada atleta. O código fonte está em [notas-atletas.js](notas-atletas.js).

## O que o script faz

- Define um array [`atletas`](notas-atletas.js) contendo objetos com `nome` e `notas`.
- Para cada atleta:
  1. Ordena as notas em ordem crescente.
  2. Remove a menor e a maior nota, mantendo as notas do meio (variável [`notasComputadas`](notas-atletas.js)).
  3. Soma as notas restantes e calcula a média (variável [`media`](notas-atletas.js)) usando a fórmula:
  
  Inline: $ \bar{x} = \dfrac{\sum x_i}{n} $
  
  Bloco:
  $$
  \bar{x} = \frac{\sum_{i=1}^{n} x_i}{n}
  $$

## Exemplo de saída

Para cada atleta o script imprime:
- Atleta: nome
- Notas Obtidas: lista completa de notas
- Média Válida: média calculada (após remover maior e menor nota)

## Como executar

No terminal do projeto, execute:

```sh
node notas-atletas.js
```

Arquivo fonte: [notas-atletas.js](notas-atletas.js)  
README atual: [README.md](README.md)
