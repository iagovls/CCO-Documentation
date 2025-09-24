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
    
    RegistroRedBasilio(("Registro RED Basílio")) 
    
    RegistroFrutaria(("Registro Frutaria"))
    
    RedBasilio[("RED Basílio 200 m³")]
   
    RadBancoDaVitoria[("RAD Banco da Vitória 500 m³")]
    
    BoosterIraque[/"Booster Iraque"\]
    
    Basilio(["Basílio"])
    
    BancoDaVitoria(["Banco da Vitória"])
    
    Iraque(["Iraque"])
    
    Salobrinho(["Salobrinho"])
    
    RuaDoOuro(["Rua do Ouro"])
   
    ParqueUniversitario(["Parque Universitário"])
    
    BoosterRuaDoOuro[/"Booster Rua do Ouro"\]
    
    BoosterParqueUniversitario[/"Booster Parque Universitário"\]   


    %% Ligações
    ETA ---> EEATBasilio
    EEATBasilio ---> RegistroRedBasilio
    RegistroRedBasilio ---> RedBasilio
    RegistroRedBasilio ---> RegistroFrutaria
    RedBasilio ---> Basilio
    RegistroFrutaria ---> RadBancoDaVitoria
    RadBancoDaVitoria ---> BancoDaVitoria
    RadBancoDaVitoria ---> BoosterIraque
    BoosterIraque ---> Iraque
    RegistroFrutaria ---> Salobrinho
    Salobrinho ---> BoosterRuaDoOuro
    Salobrinho ---> BoosterParqueUniversitario       
    BoosterRuaDoOuro---> RuaDoOuro       
    BoosterParqueUniversitario ---> ParqueUniversitario       
       
    
```
