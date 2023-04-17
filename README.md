# r-template-tb

Análises para relatório.

## Para desenvolver

Dados vão em `data`. Opcionalmente, crie subdiretórios para dados brutos com o nome `data/raw` ou para dados prontos para análise com o nome `data/ready`. Dados temporários podem ser colocados em `data/temp` (incluído no `.gitignore`).

Código para obter dados (e colocá-los em `data` ou `data/raw`) e transformar dados (colocando-os em `data` ou `data/ready`), assim como funções reusáveis vão em `src/`.

Relatórios que usam dados prontos ficam em `reports/`. Coloque o html de versões para publicação em `docs/` e eles estarão disponíveis [na página do projeto](https://transparencia-brasil.github.io/r-template-tb/). Não coloque o html dos relatórios em `reports/`.
