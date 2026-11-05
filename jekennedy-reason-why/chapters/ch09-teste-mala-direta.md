# Capítulo 09 — "How Mail Order Advertising is Tested" (Como testar a propaganda de mala direta)

**Fonte**: Kennedy, *Reason-Why Advertising*, Chapter IX. Páginas 32-34.

## Core Idea
O teste de mala direta é simples e conclusivo: cada anúncio recebe uma chave (endereço ou andar diferente) em cada veículo. Assim, cada consulta mostra de onde veio. Com a troca (cross) dos textos entre veículos, o teste elimina o efeito do veículo e mede só o texto. O custo por consulta de cada copy é a medida do valor dele.

## Frameworks Introduced
- **Keyed advertising (anúncio com chave)**: cada inserção tem um endereço de resposta próprio. Quando usar: sempre que houver mais de uma versão ou veículo. Como: mudar o endereço (ou um andar, um código) em cada anúncio e em cada veículo.
- **Split run (metade da lista)**: roda o copy atual em metade dos veículos e o novo na outra metade, no mesmo mês. Quando usar: teste inicial. Como: escolher um conjunto representativo de veículos e dividi-lo.
- **Cross (troca)**: no mês seguinte, o copy que estava em um veículo passa para o outro. Quando usar: para eliminar o efeito do veículo. Como: trocar a posição dos textos e repetir a conta.
- **Custo por consulta comparado**: custo do espaço ÷ consultas de cada copy. Quando usar: para decidir qual copy fica. Como: somar consultas por copy e dividir pelo custo do espaço.
- **Follow-up igual para os dois grupos**: a mesma sequência de cartas e folhetos para as consultas de ambos. Quando usar: para comparar lucro. Como: medir a porcentagem de venda de cada grupo.

## Key Concepts
- **Consulta (inquiry)** — primeiro sinal tangível; é a unidade de medida do teste. (ch09)
- **Keying** — mudar o endereço de resposta por anúncio e por veículo, para saber a origem. (ch09)
- **Consistência entre produtos** — o livro afirma que o copy que vende lavadoras por um terço do custo vende violinos, sapatos e pianos na mesma proporção. (ch09)
- **Escolha pelo resultado, não pelo gosto** — o copy que mais vende pode ser o que o anunciante menos gosta. (ch09)

## Mental Models
- **Experimento de laboratório**: uma variável por vez (o texto), com o veículo trocado para não viciar o resultado.
- **Recibo de cada anúncio**: cada consulta carrega a etiqueta de origem.

## Anti-patterns
- Testar dois copies no mesmo veículo e no mesmo período sem chave: não se sabe de qual veio cada venda.
- Concluir com um mês só, sem o cross.
- Julgar pelo número total de consultas, sem dividir pelo custo.

## Worked Example (reconstruído)
Escolha 6 revistas. Em 3 roda o copy A, nas outras 3 o copy B, cada um com endereço diferente (ex.: "86 State St." em uma, "75 State St." em outra). Ao fim do mês, conte as consultas por endereço e divida o custo do espaço. No mês seguinte, troque: A vai para as revistas de B e vice-versa. Compare o custo por consulta médio de A e de B. O copy de menor custo ganha, e o follow-up confirma o lucro.

## Key Takeaways
1. Cada anúncio e cada veículo precisa de uma chave própria.
2. Troque os textos de veículo (cross) para isolar o efeito do texto.
3. Compare o custo por consulta e, depois, a taxa de venda.
4. Um bom teste é barato de fazer e decisivo.

## Connects To
- ch10 (o teste equivalente para propaganda de varejo)
- ch17 (o Record of Results que acumula esses testes)
- ch06 (o custo por consulta como critério)
