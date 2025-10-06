### EEAT Basílio (AUTAG)

Abastecimento normalmente entre `22:00` e `16:00`

| Parâmetro     | Valor |
| -------------    | ------------- |
| Início horário de ponta  | 15:40 |
| Final horário de ponta  | 21:40 |
| Desliga máx. jusante  | 4,00 m|
| Liga mín. jusante  | 3,00 m|
| Liga máx. montante  | 2,10 m|
| Desliga mín. montante  | 1,20 m|
| Frequência  | 60 hz|
| Setpoint  | 3,50 m|

Pontos relacionados:
- [49943042 - ALTO LUIZ GAMA 89 MAT 46223991](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBQ3VqHeku9slPteHB1pGu94UrUgUBM=)
- [49932010 - RUA PORTO SEGURO PARK NOVA ESP](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WLs3VgHeku9slPteHB1pGu94Urk4WEG=)
  
```mermaid
flowchart LR
        
    ETA["ETA Centro"]    

    EEATBasilio[/"EEAT Basílio"\] 
    
   
    
    RedBasilio[("RED Basílio 200 m³")]   
    RadBancoDaVitoria[("RAD Banco da Vitória 500 m³")]    
    BoosterIraque[/"Booster Iraque"\]
    click BoosterIraque "https://github.com/iagovls/CCO-Documentation/blob/main/ETA%20Centro/Bas%C3%ADlio/Booster%20Iraque.md"
    Basilio(["Basílio"])    
    BancoDaVitoria(["Banco da Vitória"])    
    Salobrinho(["Salobrinho"])    
    BoosterRuaDoOuro[/"Booster Rua do Ouro"\]
    click BoosterRuaDoOuro "https://github.com/iagovls/CCO-Documentation/blob/main/ETA%20Centro/Bas%C3%ADlio/Booster%20Rua%20do%20Ouro.md"
BoosterParqueUniversitario[/"Booster Parque Universitário"\]   
    click BoosterParqueUniversitario "https://github.com/iagovls/CCO-Documentation/blob/main/ETA%20Centro/Bas%C3%ADlio/Booster%20Parque%20Universit%C3%A1rio.md"
    RegistroRedBasilio@{shape: sm-circ}
    RegistroFrutaria@{shape: sm-circ}

    %% Ligações
    ETA ---> EEATBasilio
    EEATBasilio ---> RegistroRedBasilio
    RegistroRedBasilio ---> |Registro estrangulado| RedBasilio
    RedBasilio ---> Basilio
    RegistroRedBasilio ---> RegistroFrutaria
    RegistroFrutaria ---> RadBancoDaVitoria
    RadBancoDaVitoria ---> BancoDaVitoria
    RadBancoDaVitoria ---> BoosterIraque
    RegistroFrutaria --->|Registro aberto| Salobrinho
    Salobrinho ---> BoosterRuaDoOuro
    Salobrinho ---> BoosterParqueUniversitario       
       
    
```
