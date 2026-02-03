# Sleep & Mental Health — Pilot Study

Este projeto apresenta uma análise exploratória da relação entre sono e
bem-estar psicológico a partir de um **estudo piloto**.

O objetivo não é estabelecer causalidade, mas explorar padrões iniciais,
avaliar a adequação das variáveis disponíveis e formular hipóteses para
análises em maior escala.

---

## Pergunta de pesquisa

Dormir mal está associado a pior bem-estar psicológico?

---

## Abordagem

A análise utiliza:
- **Horas de sono** e **percepção de sono suficiente** como variáveis explicativas
- **Cansaço diário** como *proxy* de bem-estar psicológico

A escolha do proxy se deve à ausência de medidas clínicas de saúde mental
no conjunto de dados.

A análise é **exploratória e não causal**, baseada em estatísticas descritivas
e visualizações.

---

## Dados

Foi utilizado um conjunto de dados piloto com **9 participantes**, contendo
informações sobre:
- horas de sono
- percepção de sono suficiente
- cansaço diário
- hábitos noturnos

Por se tratar de um estudo piloto, o tamanho amostral reduzido é uma
característica esperada e considerada na interpretação dos resultados.

---

## Principais achados

- Apesar da média de horas de sono estar próxima de 7 horas por noite,
  a maioria dos participantes (7 de 9) relata **não sentir que dormiu o suficiente**.
- A percepção de não dormir o suficiente está associada a **maior variabilidade
  no cansaço diário**, incluindo níveis mais elevados de exaustão.
- A relação entre horas de sono e cansaço diário **não apresenta um padrão
  visual claro** no estudo piloto, sugerindo que a quantidade de sono,
  isoladamente, pode não explicar o bem-estar percebido.
- O uso do celular antes de dormir foi um comportamento **universal no grupo**,
  não permitindo comparações entre participantes.

---

## Limitações

- Tamanho amostral reduzido
- Estudo piloto
- Medidas subjetivas
- Uso de proxy para bem-estar psicológico

---

## Próximos passos

- Repetir a análise utilizando o conjunto de dados completo
- Investigar indicadores adicionais relacionados à qualidade do sono
- Avaliar a consistência dos padrões observados em uma amostra maior

---

## Estrutura do repositório

```text
sleep-mental-health-pilot/
├── data/
│   └── SleepStudyPilot.csv
├── notebooks/
│   └── analysis.ipynb
└── README.md
```
---

## Observação final

Este projeto faz parte de um portfólio em construção, com foco em
análises que conectam **psicologia e ciência de dados**.