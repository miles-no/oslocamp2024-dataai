# Bruk av Codespaces
I denne workshopen har vi lagt opp for bruk av Github Codespaces. For å aktivere ditt codespace kan du klike på den grønne Code knappen til høyre. Der vil det være en tab for Codespaces. I denne taben vil det være et + symbol for å lage en Codespace instans. Dette vil initialisere den og åpne en ny fane med koden i en online VS Code IDE.
![codespaces_button](https://github.com/miles-no/oslocamp2024-dataai/img/codespaces_button.png?raw=true)

## NB Viktig: Dette er et publik repo som dere har skrive rettigheter til. Ikke last opp noe data til dette repoet eller API nøkkler som dere ikke har fått tilatelse til å dele

Det ligger noe eksempel data her allerede i form av min CV i pdf format og i json format, som dere kan leke med.

I dette prosjektet laster vi inn miljøvariabler i fra en .env fil. Siden denne filen inneholder secrets så er den del av git ignore så denne må dere lage selv.
Navnet på filen skal bare være `.env` og innholdet skal se slik ut:
![.env](https://github.com/miles-no/oslocamp2024-dataai/img/env_eksempel.png?raw=true)