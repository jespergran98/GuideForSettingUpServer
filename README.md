
Tutorial for å sette opp server:

Download Dotnet: https://dotnet.microsoft.com/en-us/download, her er commands for terminalen:

Dotnet version for å sjekke versjon:
dotnet --version

Dotnet help for alle commands:
dotnet --help

outputs exe file:
which dotnet

Genererer filer i nytt prosjekt (alle filer i hele dette prosjektet):
dotnet new web

Initialize repository?

Start et prosjekt:
dotnet run (kopier inn localhost i nettleseren)

Slutt et prosjekt:
ctrl+c mens terminalen er markert

--

(C# Dev Kit må lastes ned først)
mer avansert, for å sette opp Server.csproj filen:

får opp ekstra fil:
dotnet new sln

dotnet new web?

dotnet new sln add <firstBackendCode.csproj> (eller andre fil proj fil navn)

Lag en fil navngitt .gitignore med bin og obj

--

Legg til 2 extenions: Thunder Client (enable workspace) lynikon i baren på venstre side og

Last ned hoppscotch.io istedenfor Thunder Client? https://hoppscotch.io
Hoppscotch tilater å konstruere meldinger vi sender med HTTP requests.

--

BRUK CHROME (ikke Opera GX) FOR HOPPSCOTCH:

Get Request sendes fra PC. (HOST: URL)
GET /some/path. Optional: Body, headers.

HTTP Verb:
https://hoppscotch.io har en rekke "verb", blant annet GET, POST, PUT og DELETE.

HTTP Verb meninger "crud operasjoner":
Post -> Create
Get -> Read
Put -> Update
Delete -> Delete

Bytt ut URL adressen på hoppscotch med localhost linken fra dotnet run, dette gjør det mulig å endre "Hello World!" til noe annet. Sender data til serveren. bytt ut teksten i hoppscotch Body og headers etc. Trykk send for outputte en JSON fil i hoppscotch ved å trykkke send til localhost serveren.

meldingen sendes fra readme.md filen. "Hello Word!"

--

Alternativer til hoppscotch: Mellom terminalen har vi "curl", for eksempel curl https//www.google.com
Får IP, Adresse, Host etc. (metadata)
curl -v

--

Hovedbiten vi har når vi skal lage servere:

Bestemmelser:
Hvilken HTTP metode?
Hvilken Sti/Path?
Hva skal skje?

(Dette gjøres med funksjonen app.MapGet("/", () => "Hello World!"); i program.cs)

bruker "get".

--

Installer C# DEV KIT extension i vs code.

--

Dag 2 tutorial:

Legge til i body i Hoppscotch.

HTTP response status codes:
Informational responses (100 – 199)
Successful responses (200 – 299)
Redirection messages (300 – 399)
Client error responses (400 – 499)
Server error responses (500 – 599)

-

Object Oriented Programming "substantiv".

Data typene:
Boolean: sant/usant
Tekst streng: Sekvens med symboler
Tall: tall

Gjøremål:
Egenskaper/properties/data: Oppgave tekst streng, erFulført er sant/usant, tidsfrist, opprettelse tidspunkt

Metoder/methods/funksjoner: slette, redigere, utseende, gjøre

//////////////////////////////////////////////////////////
//////////////////////////////////////////////////////////
//////////////////////////////////////////////////////////

LARS GUIDE: https://github.com/LarsGJobloop/2025-09-22-backend-intro (for full kode)

## Sketches

![Sketches](/documentation/backend-introduction.excalidraw.png)

## Command shortlist (The most important)

- Get Help

  ```sh
  dotnet --help
  ```

-- Get Version

  ```sh
  dotnet --version
  ```

- Generate new project

  ```sh
  dotnet new sln
  dotnet new web
  dotnet sln add <name-of-.csproj>
  ```

- Start the project

  ```sh
  dotnet run
  ```

- Stop the server (any console program really)

  ```sh
  Ctrl + C
  ```

## References

- [.NET SDK installation](https://dotnet.microsoft.com/en-us/download)

### HTTP Clients

There's many alternatives here, doesn't matter really what you pick.

- [Hoppscotch](https://hoppscotch.io/)

> [!NOTE]
> 
> You need to add the [Hoppscotch Extension](https://www.google.com/search?q=hoppscotch+extension) to your browser for it to be able to send message to your local server.

- [Client URL (curl)](https://curl.se/)
- [Postman](https://www.postman.com/)

