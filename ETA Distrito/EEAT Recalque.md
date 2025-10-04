### EEAT Recalque (AUTAG)

Abastecimento normalmente entre `01:30` e `13:00`

| Parâmetro     | Valor |
| -------------    | ------------- |
| Início horário de ponta  | 13:00 |
| Final horário de ponta  | 23:59 |
| Desliga máx. jusante  | - |
| Liga mín. jusante  | - |
| Liga máx. montante  | 1,00 m|
| Desliga mín. montante  | 0,90 m|
| Frequência  | 60 hz|
| Setpoint  | 13,00 mca|

Pontos relacionados:
- Iguape
  - [49938927 - RECALQUE MAT 46493247](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBYeUKHeku9slPteHB1pGu94UrQ4GhI=)
  - [49921632 - RUA DO DETRA IGUAPE*](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBs2UqHeku9slPteHB1pGu94UrY3UhI=)
  - [49935613 - IGUAPE MARIA LUIZA 777 MAT 463](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBYgUgHeku9slPteHB1pGu94UuQ5UrM=)
  - [49939481 - AV OCEÂNICA DISTRITO INDUSTRIA](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBk5UAHeku9slPteHB1pGu94UuNtUrk=)
  
- Savóia/Barra/Parque Infantil
  - [49947810 - AVN JOSE LUIS DA FONSECA 1009](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBG5WAHeku9slPteHB1pGu94Urs0VhM=)
  - [49945455 - AVN RAIMUNDO SÁ BARRETO 5](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBk3VgHeku9slPteHB1pGu94UrHuGhI=)
  - [49947149 - AVN UBAITABA 1513 MAT](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBUfUAHeku9slPteHB1pGu94UrDsHBM=)

- São Miguel  
  - [49924750 - SAO MIGUEL SAO DOMINGOS 46493!](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBU5VKHeku9slPteHB1pGu94UuVrGBC=)
  - [49946018 - RUA OVIDIO LEAL 14](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBG5VqHeku9slPteHB1pGu94UrGeUhY=)
  - [49940720 - AVN SAO DOMINGOS 21](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBk3VKHeku9slPteHB1pGu94UrttWLI=)
  - [49946936 - AVN PEDRO LAVIGNE DE LEMOS 90](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBk3UgHeku9slPteHB1pGu94UuNrGhQ=)
  - [49947013 - RUA PROF. INOCÊNCIA JOVITA 16](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBk3UqHeku9slPteHB1pGu94UrVrULU=)

- São Domingos
  - [49941803 - RUA INGA 166 MAT 46477675](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBU5VAHeku9slPteHB1pGu94UrDrVrY=)

- Sambaituba
  - [49944125 - RODOVIA SAMBAITUBA PEDREIRA](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBYhUAHeku9slPteHB1pGu94UrY4HrM=)
  - [49941484 - SAO JOAO RUA DA JAQUEIRA MAT 4](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBYgWAHeku9slPteHB1pGu94UrNtGBk=)
  - [49943562 - RODOVIA ARITAGUA SAMBAITUBA](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBYhUKHeku9slPteHB1pGu94UuY4UhI=)


  
```mermaid
flowchart LR
        
    ETA["ETA Distrito"] 
    EEATRecalque[/"EEAT Recalque"\]
    BoosterNovoIlheus[/"Booster Novo Ilhéus"\]
    click BoosterNovoIlheus "https://github.com/iagovls/CCO-Documentation/blob/main/ETA%20Distrito/Booster%20Novo%20Ilh%C3%A9us.md"
    RADSambaituba[(RAD Sambaituba)]
    Sambaituba(["Sambaituba"]) 
    Urucutuca(["Urucutuca"]) 
    CentroIndustrial(["Centro Industrial"]) 
    Iguape(["Iguape"]) 
    Savoia(["Savóia"]) 
    Barra(["Barra"]) 
    SaoMiguel(["São Miguel"]) 
    SaoDomingos(["São Domingos"]) 
    Cargil(["Cargil"]) 
    A@{ shape: sm-circ, label: "Small start" }

    %% Ligações
    ETA --> EEATRecalque

    EEATRecalque --> Setor28
    EEATRecalque --> Setor31
    EEATRecalque --> Cargil

    %% São Miguel e São Domingos
    EEATRecalque --> A
    A --> SaoMiguel
    A --> SaoDomingos


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

%% Sambaituba  
    subgraph Loc1315
      subgraph Setor1
        Sambaituba
        Urucutuca
      end 
    end

    EEATRecalque --> RADSambaituba
    RADSambaituba --> Loc1315

    

    EEATRecalque --> BoosterNovoIlheus


    

    
        
```
