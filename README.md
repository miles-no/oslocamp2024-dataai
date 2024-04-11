# Bruk av Codespaces
Vi har lagt opp for Github Codespaces. 

Klik på den grønne Code knappen til høyre. Der vil det være en tab for Codespaces.

I denne taben vil det være et + symbol for å lage en Codespace instans. 

Dette vil initialisere den og åpne en ny fane med koden i en online VS Code IDE.
![codespaces_button](https://github.com/miles-no/oslocamp2024-dataai/blob/main/img/codespaces_button.png?raw=true)

Ved oppstart første gang vil Codespaces automatisk installere alle de predefinerte pakkene. Dette tar noen sekunder, bare vent litt før dere begynner å kjøre noe.

Dere skal ha fått skrive rettigheter så da kan vi jobbe som vanlig med git.

### NB Viktig: Dette er et public repo. Ikke last opp noe data til dette repoet eller API nøkkler som dere ikke har fått tilatelse til å dele.

Det ligger noe eksempel data her allerede i form av min CV i pdf format, som dere kan leke med.

Ellers kan dere selv laste opp data ved å høye klikke på relevant mappe og trykke på ´Upload...´.


## Miljø variabler
I dette prosjektet laster vi inn miljøvariabler i fra en .env fil. Siden denne filen inneholder secrets så er den del av git ignore så denne må dere lage selv.

Lag en ny fil med navn `.env` i root.

Fyll in med miljø variable `OPENAI_API_KEY` og set den lik nøkkelen vi skal dele med dere på camp.

#### OBS: Viktig at miljø variablen har akkurat det navnet.

![.env](https://github.com/miles-no/oslocamp2024-dataai/blob/main/img/env_eksempel.png?raw=true)

## Notebook
I mappen notebooks finner dere en demo som viser litt hvordan dere kan bruke openai SDK.

Første gang man kjører en notebook blir man spurt om å velge en kernel.

Forslaget til VS code, en python 3.10 kernel, er det riktige valget.

Man kan også velge en kernel oppe i høyre hjørne av notebooken som følger:

![kernel](https://github.com/miles-no/oslocamp2024-dataai/blob/main/img/kernel.png?raw=true)