# ETA Distrito

## ℹ️ Informações
- Endereço: Estrada Carobeira
- Matrícula: 178795321
- Vazão: 250 m³/h
- Volume do RAD: -
- Volume do RED: -


## 👷 Operadores
| Nome     | Empresa |
| -------------    | ------------- |
| Alessandro  | Porto Fino |
| André Macedo  | EMBASA |
| Antônio Carlos  | EMBASA|
| Edson  | Porto Fino |
| Idaízio  | EMBASA |

## 👷 Auxiliares
| Nome     | Empresa |
| -------------    | ------------- |
| Lico  | Porto Fino |


## 🧪 Produtos químicos

| Função     | Produto |
| -------------    | ------------- |
| Coagulante  | Polyfer|
| Alcalinizante  | Barrília |
| Desinfetante  | Cloro Gás |

## 📖 Índice

- [EEAT Recalque](EEAT%20Recalque.md)
  - [Booster Novo Ilhéus](Booster%20Novo%20Ilhéus.md)
- [EEAT São José](EEAT%20São%20José.md)

```mermaid
flowchart LR
        
    ETA["ETA Distrito"] 
    EEATRecalque[/"EEAT Recalque"\]
    EEATSaoJose[/"EEAT São José"\] 
    BoosterNovoIlheus[/"Booster Novo Ilhéus"\]
    Cargil(["Cargil"]) 
    RADSambaituba[(RAD Sambaituba)]
    Iguape(["Iguape"]) 
    CentroIndustrial(["Centro Industrial"]) 
    Savoia(["Savóia"]) 
    Barra(["Barra"]) 
    ParqueInfantil(["Parque Infantil"]) 
    SaoMiguel(["São Miguel"]) 
    SaoDomingos(["São Domingos"]) 
    Juerana(["Juerana"]) 
    LitoralNorte(["LitoralNorte"]) 
    Sambaituba(["Sambaituba"]) 
    NovoIlheus(["Novo Ilhéus"])
    BoosterCachorroPelado[/"Booster Cachorro Pelado"\] 
    SaoJose(["São José"]) 
    CachorroPelado(["Cachorro Pelado"])
    A@{ shape: sm-circ, label: "Small start" }

    %% Ligações
    
    ETA --> EEATRecalque

    EEATRecalque --> Setor23
    EEATRecalque --> Setor28
    EEATRecalque --> Setor31


    %% Sambaituba  
    subgraph Loc1315
      subgraph Setor1
        Sambaituba
        Urucutuca
      end 
    end

    EEATRecalque --> RADSambaituba
    RADSambaituba --> Loc1315


    %% Litoral Norte
    subgraph Setor23 [Setor 23]
      subgraph LitoralNorte [Litoral Norte]
        Juerana
      end
    end
  

    
    %% Iguape
    subgraph Setor28 [Setor 28]
      Iguape
    end


    %% Setor 31
    subgraph Setor31 [Setor 31]
      CentroIndustrial
      Barra
      Savoia
    end

    %% São Miguel e São Domingos
    EEATRecalque --> A
    A --> SaoMiguel
    A --> SaoDomingos

    %% Novo Ilhéus
    EEATRecalque --> BoosterNovoIlheus
    BoosterNovoIlheus --> Setor29
    subgraph Setor29 [Setor 29]
      NovoIlheus
    end

    %% São José
    ETA --> EEATSaoJose    
    EEATSaoJose --> Loc1317
    subgraph Loc1317 [Localização 1317]
      subgraph Setor 1
        SaoJose
      end
    end


    %% Cachorro Pelado
    EEATSaoJose --> BoosterCachorroPelado
    BoosterCachorroPelado --> CachorroPelado

    %% Parque Infantil
    EEATRecalque --> |Manobra para abastecer até o Parque Infantil. Registro usualmente fechado.| ParqueInfantil

    %% Cargil
    EEATRecalque --> Cargil
    
    

    

    
        
```
