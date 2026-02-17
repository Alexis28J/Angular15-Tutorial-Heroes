TUTORIAL "TOUR OF HEROES"
https://v15.angular.io/tutorial/tour-of-heroes

Per usare una versione precedente di Angular, il metodo migliore consiste nell'installare una specifica versione della CLI localmente nel progetto, 
invece di usare quella globale, usando npm install @angular/cli@<versione>. 
Questo permette di gestire diverse versioni di Angular per progetti differenti senza conflitti. 

Ecco i passaggi dettagliati per utilizzare una versione precedente:
1. Creare un nuovo progetto con una specifica versione
Se vuoi creare un nuovo progetto usando, ad esempio, Angular 15, non installare la CLI globalmente. Usa invece npx per utilizzare la versione desiderata al volo:

npx @angular/cli@15 new nome-progetto

Questo comando scaricherà temporaneamente la CLI 15, creerà il progetto e configurerà correttamente il file package.json

Quindi, ho eseguito il comando "npx @angular/cli@15 new angular-tour-of-heroes --directory ./" per creare un nuovo progetto con Angular 15
In questa versione non ti aggiunge il file della routing automaticamente quindi dire di si all'opzione "Would you like to add Angular routing?"

ng serve --open o ng serve -o per lanciare e aprire direttamente l'applicazione.