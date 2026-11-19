# Ilhas de Papel V3

## Executar no Windows
Instale Node.js (https://nodejs.org/). Abra a pasta que contém `package.json` no Explorador, digite `cmd` na barra de endereço e execute:

```
npm install
npm start
```

Abra http://localhost:3000 no navegador. Para jogar online com amigos em outras redes, hospede o servidor Node.js com suporte a WebSocket.

## Regras implementadas
- Salas com código e turnos sincronizados.
- Dado de 10, 20, 30, 40, 50, 60.
- Mineração: escolha 3 números; sucesso dá 1 minério, ou 2 com 2+ ilhas.
- Pesquisa: escolha 2 números; com 2+ ilhas, até 2 tecnologias na mesma ação, com sorteios independentes.
- Fábricas: cada uma custa 1 minério, escolha 1 número; fábrica de fábricas aumenta em 1 o número de escolhas. Fábrica de pesquisa aumenta em 1 as escolhas de pesquisa. Fábrica de minério produz 1 por rodada.
- Fazendas, população, recrutamento, combate e fabricação de tecnologias.
- Ponte custa 2 minérios, exige pesquisa, e habilita conquista de outras ilhas (modelo simplificado sem traçado físico).
- Avião permite bombardear uma fábrica ou fazenda inimiga por ação (modelo inicial sem munição nem defesa).

## Pendências para definir
Conexões reais entre ilhas, alcance e custo de bombas, persistência das salas, reconexão e balanceamento.
