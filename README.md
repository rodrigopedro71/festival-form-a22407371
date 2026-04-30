# Festival

## Alterações e correções realizadas

Neste projeto foram feitas várias alterações para melhorar a gestão dos concertos e dos palcos do festival.

## Modelos

Foi adicionada ao modelo `Palco` a variável `acessibilidade_mobilidade_reduzida`, que permite indicar se um palco tem ou não acessibilidade para pessoas com mobilidade reduzida.

```python
acessibilidade_mobilidade_reduzida = models.BooleanField(default=True)
        ordering = ["dia__data", "hora"] : Faz com que ordene as bandas pelo horario em cada dia