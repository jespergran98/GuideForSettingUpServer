
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

-
mer avansert, for å sette opp Server.csproj filen:

får opp ekstra fil:
dotnet new sln

dotnet new web?

dotnet new sln add <Server.csproj> (eller andre fil proj fil navn)

Lag en fil navngitt .gitignore med bin og obj

-

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

Post -> Create
Get -> Read
Put -> Update
Delete -> Delete

--

Installer C# DEV KIT extension i vs code.

