### EEAT Vilela (AUTAG)

Abastecimento normalmente entre `22:00` e `14:00`

| Parâmetro     | Valor |
| -------------    | ------------- |
| Início horário de ponta  | 14:30 |
| Final horário de ponta  | 21:30 |
| Desliga máx. jusante  | 65,0 mca|
| Liga mín. jusante  | 1,0 mca|
| Liga máx. montante  | 2,10 m|
| Desliga mín. montante  | 1,20 m|
| Frequência  | 54 hz|
| Setpoint  | 1,50 m|

Pontos relacionados:
- [49924795 - MACRO TEOTÔNIO VILELA PONTE](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBU3VAHeku9slPteHB1pGu94UrVuULI=)
- [49951020 - RUA CESÁRIO DAS NEVES 198 S 17](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBCgUKHeku9slPteHB1pGu94UuQ0UhI=)
- [49943727 - RUA IPIRANGA 188 MAT 46518932](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBU3VgHeku9slPteHB1pGu94UrDtWLM=)
- [49921723 - RUA CONTORNO 563 MAT 46548025](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBUgVgHeku9slPteHB1pGu94UrJuWBQ=)  

```mermaid
flowchart LR
    subgraph ETA["ETA Centro"]
    end

    subgraph B1["EEAT Vilela"]
    end

    subgraph B2["RED Vilela"]
    end    

    subgraph Bairro[" Bairros: Teotônio Vilela "]
    end

    ETA --> B1
    B1 --> B2
    B2 --> Bairro
```
