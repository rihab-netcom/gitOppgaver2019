# Sommerprosjekt 2017

Tilhører Git-kurs for sommerprosjektet 2017

(http://memeshappen.com/media/created/One-does-not-simply-understand-git-meme-60285.jpg)

Skrivefeil

# Oppgaver
Hvis du står fast kan du gå tilbake til (https://try.github.io) for å se over
kommandoer

## Oppgave 1
Lag en liten feature

- Lag en ny branch utifra master med navn ```feature-<branch_navn>```
- Legg til en ny linje i SOME_FILE.MD
- Commit med passende melding
- Push opp branchen til repoet
    - Hint: Nye branches lagd lokalt må kobles opp mot en ny branch i remote repo.
    ```git push -u origin min-custom-branch```
- Sjekk at branchen eksisterer i remote repo på Gitlab

## Oppgave 2
Fiks en liten bug

- Lag en ny branch utifra master med navn ```bugfix-<branch_navn>```
- Gjør om linjen ”Skriveleif” til ”Skrivefeil” i README.MD
- Commit med passende melding
- Push opp branchen til repoet
- Sjekk at branchen eksisterer i remote repo på Gitlab

## Oppgave 3
Fiks en merge-konflikt

- Bytt branch til master
- Hent ned branchene ```conflict-branch-1``` og ```conflict-branch-2```
    - Hint: Bruk ```git checkout -b conflict-branch-1 origin/conflict-branch-1```
    for å lage en lokal branch som er koblet opp til samme branch i remote repo. Kjør
    kommandoen for begge branches slik at du har de lokalt.
- Merge ```conflict-branch-2``` inn i ```conflict-branch-1``` og løs konfliktene med
konflikhåndteringsverktøy i IntelliJ
- Commit etter å ha løst merge-konflikt (ikke push opp resultatet)

## Oppgave 4
Lag en merge request

- Lag en ny branch utifra master
- Push den nye branchen til remote repo
- Lag en merge request for branchen du lagde i oppgave 1. Branchen du nettopp lagde 
skal være "target" branch for merge request, mens branchen fra oppgave 1 skal være "source"
branch.
    - Hint: Hvis du tidligere har pushet en branch til remote i terminal har du kanskje sett
    link til å lage merge request?
- Få noen andre til å ta "code-review" på endringen du lagde
    - Vedkommende skal lage minst en kommentar på en vilkårlig linje i "changes"-view
    - Vedkommende skal akseptere merge-requesten (trykk "merge") etter å ha lagd
    en kommentar
    
## Oppgave 5
Now with GUI!

- Gjør oppgave 1 med kun bruk av Git-verktøy i IntelliJ
