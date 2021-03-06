[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[<img align="right" width="150" src="assets/join-slack-team.png">](https://join.slack.com/t/firstcontributors/shared_invite/enQtMzE1MTYwNzI3ODQ0LTZiMDA2OGI2NTYyNjM1MTFiNTc4YTRhZTg4OWZjMzA0ZWZmY2UxYzVkMzI1ZmVmOWI4ODdkZWQwNTM2NDVmNjY)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Open Source Helpers](https://www.codetriage.com/roshanjossey/first-contributions/badges/users.svg)](https://www.codetriage.com/roshanjossey/first-contributions)


# First Contributions

Det är svårt. Det är alltid svårt första gången men gör något. När du samarbetar med andra kan det vara extra känsligt att göra misstag. Vi vill förenkla att lära sig hur man tillför till ett öppen källkods-projekt.

Att läsa artiklar och titta på handledningar kan så klart hjälpa men det är alltid bättre att göra det på riktigt. Detta projeket har som mål att tillhandahålla en guide och förenkla för nybörjare att göra sina första bidrag. Om du är ute efter att göra ditt första bidrag kan du följa stegen nedan.


#### *Om du inte känner dig bekväm med kommandoraden, [så finns en vägledning här.]( #tutorials-using-other-tools )*

#### *Läs detta på [andra språk](Translations.md).*

<img align="right" width="300" src="assets/fork.png" alt="fork this repository" />

Om du inte har git installerat [så installera det]( https://help.github.com/articles/set-up-git/).

## Gör en Fork på detta repository

Forka detta repo genom att klicka på fork-knappen överst på denna sida.
Detta kommer att skapa en kopia av detta repo i ditt konto.

## Clona repositoryt

<img align="right" width="300" src="assets/clone.png" alt="clone this repository" />

Clona repot till din dator. Gå till ditt GitHub-konto och klicka på clone-knappen och klickka sedan på *copy to cliboard*-ikonen.

Öppna en terminal och kör följande git-kommando:

```
git clone "url you just copied"
```
där "url you just copied" (utan citat-tecken) är URL:en för detta repo (din fork för detta projekt). Se föregående steg för att hitta URL:en.

<img align="right" width="300" src="assets/copy-to-clipboard.png" alt="copy URL to clipboard" />

Till exempel:
```
git clone https://github.com/this-is-you/first-contributions.git
```
där `this-is-you` är ditt användarnamn på GitHub. På detta sätt kopierar du innehållet i detta rep till din dator.

## Skapa en branch

Gå till repo-katalogen på din dator (om du inte redan står i den katalogen):

```
cd first-contributions
```

Nu skapar du en branch genom att använda `git checkout`-kommandot:
```
git checkout -b <lägg till ditt branch-namn>
```

Till exempel:
```
git checkout -b mitt-tillag
```

## Gör de ändringar du vill göra och commita dem

Nu öppnar du `Contributors.md` i en text-editor och lägger till ditt namn. Lägg inte till något i början eller slutet av dokumentet. Lägg till någonstans mitt emellan. Spara filen.

<img align="right" width="450" src="assets/git-status.png" alt="git status" />

Ge kommando `git status` i projektkatalogen för att se de ändringar du gjort.


Lägg till dina ändringar genom att använda kommando `git add -A`:

```
git add -A
```

Commita dina ändringar genom att använda `git commit`:
```
git commit -m "Add <your-name> to Contributors list"
```
erätt `<your-name>` med ditt namn.

## Pusha ändringar till GitHub

Pusha dina ändringar genom att använda kommando `git push`:
```
git push origin <add-your-branch-name>
```
ersätt `<add-your-branch-name>` med det branch-namn du använt tidigare.

## Skicka iväg dina ändringar för granskning

Om du navigerar till ditt repo på GitHub kan du se en knapp med texten `Compare & pull request`. Klicka på den.

<img style="float: right;" src="assets/compare-and-pull.png" alt="create a pull request" />

Skicka iväg din s.k. pull request.

<img style="float: right;" src="assets/submit-pull.png" alt="submit pull request" />

Snart kommer jag införa dina ändringar i huvudprojektet. Du kommer att få ett e-mail så fort dina ändringar blivit införda.

## Ta bort din branch efter det att dina ändringar blivit införda

Du kan lugnt ta bort din branch "<add-your-branch-name> efter det att din begäran blivit införd. Du kommer att se en knapp i GitHub:

<img style="float: right;" src="assets/delete-branch-after-pr.png" alt="delete branch after PR is merged" />

Om din begäran stängdes utan att införas kommer GitHub att varna för att du försöker ta bort ändringar som inte införts, knappen kommer se ut så här:

<img style="float: right;" src="assets/delete-branch-warning.png" alt="delete branch after PR is not merged" />

## Hur går man vidare?

Gratulerar! Du har just genomfört standardprocessen för _fork -> clone -> edit -> PR_ som du kommer att stöta på ofta!

Fira genom att dela med dina vänner och följare genom att gå till [web app](https://roshanjossey.github.io/first-contributions/#social-share).

Behöver du hjälp eller vill ställa frågor kan du gå med i vår slack-grupp. [Gå med i slack-gruppen](https://join.slack.com/t/firstcontributors/shared_invite/enQtMzE1MTYwNzI3ODQ0LTZiMDA2OGI2NTYyNjM1MTFiNTc4YTRhZTg4OWZjMzA0ZWZmY2UxYzVkMzI1ZmVmOWI4ODdkZWQwNTM2NDVmNjY).

Nu kan du gå vidare genom att bidra i andra projekt. Vi har sammanställt en lista med enkla uppgifter som du kan starta med. Kolla in [projektlistan i webbapplikationen](https://roshanjossey.github.io/first-contributions/#project-list).

### [Ytterligare material](additional-material/git_workflow_scenarios/additional-material.md)


## Handledningar för andra verktyg

|<a href="github-desktop-tutorial.md"><img alt="GitHub Desktop" src="https://desktop.github.com/images/desktop-icon.svg" width="100"></a>|<a href="github-windows-vs2017-tutorial.md"><img alt="Visual Studio 2017" src="https://www.visualstudio.com/wp-content/uploads/2017/11/microsoft-visual-studio.svg" width="100"></a>|<a href="gitkraken-tutorial.md"><img alt="GitKraken" src="/assets/gk-icon.png" width="100"></a>|
|---|---|---|
|[GitHub Desktop](github-desktop-tutorial.md)|[Visual Studio 2017](github-windows-vs2017-tutorial.md)|[GitKraken](gitkraken-tutorial.md)|

## Beröm

Om du tyckte om detta projektet kan du tilldela stjärnor på [GitHub](https://github.com/Roshanjossey/first-contributions).
Känner du dig särskilt snäll kan du följa [Roshan](https://roshanjossey.github.io/) på
[Twitter](https://twitter.com/sudo__bangbang) och
[GitHub](https://github.com/roshanjossey).

<a href="http://saasgrids.com"> <img alt="https://app.saasgrids.com" src="assets/saasgrids-banner.png" width="500"></a>
