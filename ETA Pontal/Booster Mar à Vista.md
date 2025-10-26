
### Booster Mar à Vista (AUTAG)

Abastecimento normalmente entre `06:00` e `12:00`

| Parâmetro     | Valor |
| -------------    | ------------- |
| Início horário de ponta  | 00:00 |
| Final horário de ponta  | 06:00 |
| Desliga máx. jusante  | 90,00 mca |
| Liga mín. jusante  | 52,00 mca |
| Liga máx. montante  | 25,00 mca|
| Desliga mín. montante  | 4,00 mca|
| Frequência  | - |
| Setpoint  | - |

Pontos relacionados:
- Condomínio Mar à Vista
  - [49943440 - Condominio Mar a Vista](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249UBIgVhQukPRdHPZ5kOC9GERdmLQ0WOUg)

```mermaid
flowchart LR
ETA["ETA Pontal"]
click ETA "https://github.com/iagovls/CCO-Documentation/blob/main/ETA%20Pontal/ETA%20Pontal.md"
RADNSV[(RAD Nossa Senhora da Vitória 2000 m³)]
BoosterMarAVista[/"Booster Mar à Vista"\]
MarAVista(["Condomínio Mar à Vista"])
click MarAVista "https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249UBIgVhQukPRdHPZ5kOC9GERdmLQ0WOUg"

 %% Litoral Norte
    ETA --> RADNSV
    RADNSV --> BoosterMarAVista
    BoosterMarAVista --> MarAVista

    subgraph Setor4 [Setor 4]
      MarAVista
    end
```
