# Estudo de Caso: Otimização de Produção Agrícola
## Descrição do problema
Uma fazenda possui diferentes culturas que podem ser plantadas em suas terras. O objetivo é maximizar o lucro total da fazenda, considerando as limitações de recursos disponíveis e as demandas de mercado.

## Detalhes do Problema
Existem cinco tipos de culturas que podem ser plantadas: A, B, C, D e E. Cada cultura requer diferentes quantidades de recursos (tempo, mão de obra, área) para ser cultivada e gera diferentes lucros por unidade produzida. A fazenda tem recursos limitados disponíveis para alocar para essas culturas.

### Objetivo:
Informar a quantidade produzida de cada cultura e o lucro final da fazenda

### Detalhes das Culturas
Cultura A: Requer 1 horas de trabalho, 1 acre de terra e 1 unidade de água para produzir uma unidade. Gera um lucro de 300 unidades monetárias por unidade.

Cultura B: Requer 1 horas de trabalho, 1 acre de terra e 1 unidade de água para produzir uma unidade. Gera um lucro de 400 unidades monetárias por unidade.

Cultura C: Requer 2 horas de trabalho, 1,5 acres de terra e 2 unidades de água para produzir uma unidade. Gera um lucro de 450 unidades monetárias por unidade.

Cultura D: Requer 2 horas de trabalho, 2 acres de terra e 3 unidades de água para produzir uma unidade. Gera um lucro de 600 unidades monetárias por unidade.

Cultura E: Requer 1 horas de trabalho, 2,5 acres de terra e 4 unidades de água para produzir uma unidade. Gera um lucro de 700 unidades monetárias por unidade.

### Restrições:
A fazenda tem um total de 100 horas de trabalho disponíveis por semana.

A fazenda possui 200 acres de terra disponíveis.

A fazenda tem acesso a 300 unidades de água por semana.

Pelo menos 20% das horas devem ser alocadas para a cultura D.

No máximo 30% das horas podem ser alocadas para a cultura E.

### Limitantes (bounds)
Além de maximizar o lucro total, é necessário garantir a demanda semanal mínima de mercado que é:

Cultura A: 05 unidades

Cultura B: 07 unidades

Cultura C: 08 unidades

Cultura D: 05 unidades

Cultura E: 20 unidades
