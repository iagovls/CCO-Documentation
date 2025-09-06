### EEAT Centro/Malhado (AUTAG)

Abastecimento normalmente entre `23:00` e `13:00`

| Parâmetro     | Valor |
| -------------    | ------------- |
| Início horário de ponta  | 15:30 |
| Final horário de ponta  | 22:30 |
| Desliga máx. jusante  | 4,00 m|
| Liga mín. jusante  | 3,00 m|
| Liga máx. montante  | 2,10 m|
| Desliga mín. montante  | 1,20 m|
| Frequência  | 54 hz|
| Setpoint  | 3,50 m|

Pontos relacionados:
- [49945148 - MALHADO MAT 46254129](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBUgUAHeku9slPteHB1pGu94UuNsUBM=)
- [49945532 - AVN GOVERNADOR ROBERTO SANTOS](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBkeVAHeku9slPteHB1pGu94UrVuHrU=)
- [49945501 - AVN UBAITABA 1251 MAT 46324348](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBU4UqHeku9slPteHB1pGu94UuHtVhk=)
  
```mermaid
flowchart LR
        
    ETA["ETA Centro"]    

    EEATCentro[/"EEAT Centro"\] 
    
    RADTapera[("RAD Tapera")] 
    
    RegistroGertec(("Registro GERTEC"))
    
    Centro(["Centro"])

    Malhado(["Malhado"])
   
    BoosterAmparoInter[/"Booster Amparo Intermediária"\]

    BoosterAmparoAlta[/"Booster Amparo Alta"\]

    BoosterCarvalho[/"Booster Carvalho"\]

    BoosterSoledadeInter[/"Booster Soledade Intermediária"\]

    BoosterSoledadeAlta[/"Booster Soledade Alta"\]

    BoosterRuaDaHorta[/"Booster Rua da Horta"\]
    
    CoqueiroInter(["Coqueiro Zona Intermediária"])
    CoqueiroAlta(["Coqueiro Zona Alta"])
    LegiaoInter(["Legião Zona Intermediária"])
    LegiaoAlta(["Legião Zona Alta"])
    AmparoInter(["Alto Amparo Zona Intermediária"])
    AmparoAlta(["Alto Amparo Zona Alta"])

    AltoCarvalho(["Alto Carvalho"])
    Esperança(["Esperança"])

    NerivalZonaInter(["Nerival Zona Intermediária"])

    AltoSoledade(["Alto Soledade"])
    NerivalZonaAlta(["Nerival Zona Alta"])

    RuaDaHorta(["Rua da Horta"])
    AltoAureliano(["Alto Aureliano"]) 

    %% Ligações
    ETA --> EEATCentro
    EEATCentro --> RADTapera
    RADTapera --> RegistroGertec

    RegistroGertec --> |Geralmente fechado para o Centro| Centro
    RADTapera --> Malhado
    RADTapera --> BoosterAmparoInter
    RADTapera --> BoosterAmparoAlta
    RADTapera --> BoosterCarvalho
    RADTapera --> BoosterSoledadeInter
    RADTapera --> BoosterSoledadeAlta
    RADTapera --> BoosterRuaDaHorta

    BoosterAmparoInter --> CoqueiroInter
    BoosterAmparoInter --> LegiaoInter
    BoosterAmparoInter --> AmparoInter
    BoosterAmparoAlta --> CoqueiroAlta
    BoosterAmparoAlta --> LegiaoAlta
    BoosterAmparoAlta --> AmparoAlta

    BoosterCarvalho --> AltoCarvalho
    BoosterCarvalho --> Esperança

    BoosterSoledadeInter --> NerivalZonaInter

    BoosterSoledadeAlta --> NerivalZonaAlta
    BoosterSoledadeAlta --> AltoSoledade

    BoosterRuaDaHorta --> RuaDaHorta
    BoosterRuaDaHorta --> AltoAureliano
    
```
