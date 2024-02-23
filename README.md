# machineMindsLumenDS
Repozitorijum za Lumen Data Science takmičenje

![image](https://github.com/pipstur/machineMindsLumenDS/assets/95634547/5ca94319-a7c0-4e4b-8165-6c29a22691e9)

Ja sam ovako organizovao fajlove cisto da znate za loadovanje, tj. ako zelite da runujete moj jupyter notebook


# CheckList
## Explore the data (korelacije izmedju kolona, njihovi odnosi, izvesti zakljucke itd.) [in progress]
## Clean the data (formatirati kolone, odluciti sta sa kategorickim podacima, koji su bitni koji ne itd) [in progress]
- 21/02/24 Za ovo sam aploudovao notebook u kom sam grupisao dataframe-ove, eksportovao ih, malkice ocistio podatke mada bi moglo lepse najverovatnije, svaka kritika je dobrodosla
## Build a baseline model (koji god da izaberemo) [in progress]
- 23/02/24 Napravio sam nekoliko bejslajn modela koji su uglavnom solidno losi, to vidim po R^2 vrednostima, iako su MAE i MSE vrednosti ok, tj. neke su cak i dosta dobre. Ispod su vrednosti za razlicite modele, a pogledajte i notebook za baseline modele, ima i dalje mnogo posla
- ![image](https://github.com/pipstur/machineMindsLumenDS/assets/95634547/3d1fe3a5-485d-432f-85da-0e46be8abc6e)
- Vrlo verovatno ovi komplikovaniji modeli overfittuju, treba da se radi feature engineering, biranje feature-a itd. Imajte na umu da tree based modeli dobro performuju sa vecim brojem feature-a 


## Unaprediti izabrani model
