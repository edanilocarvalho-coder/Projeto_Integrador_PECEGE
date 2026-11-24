# README - Execução do Notebook

## Estrutura esperada das pastas

Manter os arquivos na seguinte estrutura:

```text
Projeto/
│
├── Projeto_Integrador.ipynb
│
├── Base/
│   ├── BALANCO_ENERGIA_SUBSISTEMA_2023.csv
│   ├── BALANCO_ENERGIA_SUBSISTEMA_2024.csv
│   └── BALANCO_ENERGIA_SUBSISTEMA_2025.csv
│
└── Saidas/
```

A pasta **Saidas** será criada automaticamente pelo notebook caso não exista.

---

## Bibliotecas necessárias

Instalar as bibliotecas abaixo:

```bash
pip install pandas numpy matplotlib seaborn plotly
```

---

## Como executar

1. Abrir o notebook `Projeto_Integrador.ipynb`.
2. Verificar se os arquivos CSV estão na pasta `Base`.
3. Executar todas as células em sequência:
   
```text
Kernel → Restart & Run All
```

ou

```text
Run All Cells
```

---

## Arquivos de entrada

O notebook utiliza os seguintes arquivos:

```text
Base/BALANCO_ENERGIA_SUBSISTEMA_2023.csv

Base/BALANCO_ENERGIA_SUBSISTEMA_2024.csv

Base/BALANCO_ENERGIA_SUBSISTEMA_2025.csv
```

---


## Resultado esperado

Ao final da execução o notebook:

- consolida os dados de 2023, 2024 e 2025;
- valida o fechamento do balanço energético;
- gera as análises exploratórias;
- produz tabelas estatísticas;
- exporta automaticamente todos os gráficos e tabelas para a pasta `Saidas`.

Todos os resultados utilizados no relatório final do Projeto Integrador são gerados automaticamente pelo notebook.