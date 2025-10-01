# Documentação CCO - Ilhéus

## Índice

### ETA Centro

- [EEAT Basílio](ETA%20Centro/Basílio/Basílio.md)
  - [Booster Iraque](ETA%20Centro/Basílio/Booster%20Iraque.md)
  - [Booster Rua do Ouro](ETA%20Centro/Basílio/Booster%20Rua%20do%20Ouro.md)
  - [Booster Parque Universitário](ETA%20Centro/Basílio/Booster%20Parque%20Universitário.md)
- [EEAT Centro/Malhado](ETA%20Centro/Centro/Centro.md)
  - [Booster Amparo Intermediária](ETA%20Centro/Centro/Booster%20Amparo%20Intermediária.md)
  - [Booster Amparo Alta](ETA%20Centro/Centro/Booster%20Amparo%20Alta.md)
  - [Booster Carvalho](ETA%20Centro/Centro/Booster%20Carvalho.md)
  - [Booster Soledade Alta](ETA%20Centro/Centro/Booster%20Soledade%20Alta.md)
  - [Booster Soledade Intermediária](ETA%20Centro/Centro/Booster%20Soledade%20Intermediária.md)
- [EEAT Pacheco](ETA%20Centro/Pacheco/Pacheco.md)
- [EEAT Conquista Intermediária](ETA%20Centro/Conquista%20Intermediária/Conquista%20Intermediária.md)
- [EEAT Conquista Alta](ETA%20Centro/Conquista%20Alta/Conquista%20Alta.md)
- [EEAT Vilela](ETA%20Centro/Vilela/Vilela.md)
  - [Booster São Francisco](ETA%20Centro/Vilela/Booster%20São%20Francisco.md)
  - [Booster Condomínio Vilela](ETA%20Centro/Vilela/Booster%20Condomínio%20Vilela.md)


## 🕐 Horários de ponta AUTAG

Ao ajustar os parâmetros do horário de ponta `inicial` e `final` de cada CMB, é preciso considerar a falta de sincronização com o relógio principal. 
Dependendo do setor que queira ajustar, utilize a tabela abaixo para configurar o horário exato.

| Setor     | Ajustar para |
| -------------    | ------------- |
| Captação Iguape  | 9 minutos `depois`|
| Captação do Engenho  | 1 minutos `depois`|
| ETA Centro       | 22 minutos `antes`|
| ETA Distrito     | 12 minutos `antes`|
| ETA Pontal     | Não funciona|
| Booster Mar a Vista     | 7 minutos `antes`|
| Booster Pérola do Mar  | 6 minutos `antes`|
| Booster Outeiro  | 12 minutos `antes`|
| Booster Mambape  | 10 minutos `antes`|
| Booster Pontal  | 19 minutos `depois`|
| Booster Condomínio Vilela  | 9 minutos `antes`|


### Booster Parque de Olivença (Local)

Abastecimento normalmente entre `04:00` e `13:00`

Acionamento por temporizador in loco 

| Parâmetro     | Valor |
| -------------    | ------------- |
| Início | 04:00 |
| Final | 13:30  |

Pontos relacionados:
- [49946143 - R MATA ATLÂNTICA 37 MAT. 50402](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBQgUKHeku9slPteHB1pGu94UuUfWLM=)
  
| Pressão     | Valor |
| -------------    | ------------- |
| Objetiva | 10 mca |
| Máxima | 18 mca  |

```mermaid
flowchart LR
    subgraph ETA["ETA Pontal"]
    end

    subgraph B1["Booster Parque de Olivença"]
    end    

    subgraph Bairro["Rua Mata Atlântica"]
    end

    ETA --> B1
    B1 --> Bairro
```

### Booster Cidadele (Local)

Abastecimento normalmente entre `04:00` e `13:00`

Acionamento por temporizador in loco 

| Parâmetro     | Valor |
| -------------    | ------------- |
| Início | 04:00 |
| Final | 13:30  |

Pontos relacionados:
- [49942505 - CIDADELE QUADRA T](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBU0UAHeku9slPteHB1pGu94UrJrHrQ=)
  
| Pressão     | Valor |
| -------------    | ------------- |
| Objetiva | 10 mca |
| Máxima | 18 mca  |

```mermaid
flowchart LR
    subgraph ETA["ETA Pontal"]
    end

    subgraph B1["Booster Cidadele"]
    end    

    subgraph Bairro["Cidadele"]
    end

    ETA --> B1
    B1 --> Bairro
```

## Abastecimentos
