### Booster Rua do Ouro (AUTAG)

Abastecimento normalmente entre `04:00` e `08:00` e entre `12:00` e `13:00` 

| Parâmetro     | Valor |
| -------------    | ------------- |
| Desliga máx. jusante  | 60,00 mca|
| Liga mín. jusante  | 25,00 mca|
| Liga máx. montante  | 14,00 mca|
| Desliga mín. montante  | 5,00 mca|

Pontos relacionados:
- [49943363 - RUA DO OURO 111 MAT 46465340](https://www.vectorasys.com.br/vectorasys/?inc=jE9ciFZdkq5eiPI/kPRdHL0fUgHpk249WBQ3WAHeku9slPteHB1pGu94UuU2VBY=)
  
```mermaid
flowchart LR
        
    ETA["ETA Centro"]    

    EEATBasilio[/"EEAT Basílio"\]    
    
    BoosterRuaDoOuro[/"Booster Rua do Ouro"\]     
    
    RuaDoOuro(["Rua do Ouro"])   
     


    %% Ligações
    ETA ---> EEATBasilio
    EEATBasilio ---> BoosterRuaDoOuro        
    BoosterRuaDoOuro ---> RuaDoOuro
```
