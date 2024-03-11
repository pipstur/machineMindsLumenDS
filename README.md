# machineMindsLumenDS
Repozitorijum za Lumen Data Science takmičenje

![image](https://github.com/pipstur/machineMindsLumenDS/assets/95634547/5ca94319-a7c0-4e4b-8165-6c29a22691e9)

Ja sam ovako organizovao fajlove cisto da znate za loadovanje, tj. ako zelite da runujete moj jupyter notebook

## Explore the data 
## Clean the data 
- 21/02/24 Za ovo sam aploudovao notebook u kom sam grupisao dataframe-ove, eksportovao ih, malkice ocistio podatke mada bi moglo lepse najverovatnije, svaka kritika je dobrodosla
## Build a baseline model
- 23/02/24 Napravio sam nekoliko bejslajn modela koji su uglavnom solidno losi, to vidim po R^2 vrednostima, iako su MAE i MSE vrednosti ok, tj. neke su cak i dosta dobre. Ispod su vrednosti za razlicite modele, a pogledajte i notebook za baseline modele, ima i dalje mnogo posla
- ![image](https://github.com/pipstur/machineMindsLumenDS/assets/95634547/3d1fe3a5-485d-432f-85da-0e46be8abc6e)
- Vrlo verovatno ovi komplikovaniji modeli overfittuju, treba da se radi feature engineering, biranje feature-a itd. Imajte na umu da tree based modeli dobro performuju sa vecim brojem feature-a 

## Improve the chosen model and evaluate it
- ![image](https://github.com/pipstur/machineMindsLumenDS/assets/95634547/ad2fdead-463c-4c9a-948d-9ada52f00f9e)
- U teoriji ovaj RandomForest model koji sam implementirao radi okej, ali je pitanje da li overfittuje. Probao sam putem unakrsne validacije i odradio sam neku malu hiperparametarsku optimizaciju putem RandomizedSearch-a
- ![image](https://github.com/pipstur/machineMindsLumenDS/assets/95634547/67e0b836-8c40-47f2-b863-82f797dc6ad8)
- Nakon toga sam testirao na hotel_id=1 datasetu, i to je radilo solidno
- ![image](https://github.com/pipstur/machineMindsLumenDS/assets/95634547/04917d02-3a0c-4780-a92e-cebe03a0fdee)

## Task List (ovde zapišite bilo kakvu ideju šta bi se moglo uraditi ili nešto sa cime se hvatate u koštac trenutno)
- Razmisliti o CRISP-DM metodologiji i načinu na koji se pristupa podacima
- Explore the data (izvesti zakljucke itd.) [in progress]
- Clean and format the data [in progress, mada bi moglo još ponešto da se uradi verovatno]
  - Formatirati kolone +
  - Odluciti sta sa kategorickim podacima 
  - Feature engineering
  - Razmisliti o tome kako formatirati datasetove (dnevni, nedeljni, mesecni, godisnji) da bi se mogli testirati modeli na smislen nacin
- Build a baseline model (koji god da izaberemo) [otprilike završeno]
  - Random Forest za sada, mada je nekoliko njih napravljeno
- Improve the chosen model and evaluate it on new data [in progress]
  - Ispitati moguće overfittovanje modela
  - Objasniti rezultate
- Explore additional models [to do]
- Model Deployment
- MLFlow ?

