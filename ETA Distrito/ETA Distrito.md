# ETA Distrito

## ℹ️ Informações
- Endereço: Estrada Carobeira
- Matrícula: 178795321
- Vazão: 250 m³/h
- Volume do RAD: 1400 m³
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
    EEATLitoralNorte[/"EEAT Litoral Norte"\] 
    BoosterNovoIlheus[/"Booster Novo Ilhéus"\]
    Cargil(["Cargil"]) 
    RADSambaituba[(RAD Sambaituba)]
    RADJuerana[(RAD Juerana)]
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
    
    B@{ shape: sm-circ, label: "Small start" }

    %% Ligações
    
    ETA --> EEATRecalque

    


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
    ETA --> EEATLitoralNorte
    EEATLitoralNorte --> RADJuerana
    RADJuerana --> Setor23
    subgraph Setor23 [Setor 23]
      subgraph LitoralNorte [Litoral Norte]
        Juerana
      end
    end
  

    










    %% Parque Infantil
    EEATRecalque --> |Manobra para abastecer até o Parque Infantil. Registro usualmente fechado.| ParqueInfantil

    %% Cargil
    EEATRecalque --> Cargil
    
    

    

    
        
```
