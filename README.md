
Tutorial for å sette opp server:

Download Dotnet: https://dotnet.microsoft.com/en-us/download, her er commands for terminalen:

Dotnet version for å sjekke versjon:
dotnet --version

Dotnet help for alle commands:
dotnet --help

outputs exe file:
which dotnet

Genererer filer (alle filer i hele dette prosjektet):
dotnet new web

Lag en fil navngitt .gitignore med bin og obj

Initialize repository?

Start et prosjekt:
dotnet run (kopier inn localhost i nettleseren)

Slutt et prosjekt:
ctrl+c mens terminalen er markert

--

Legg til 2 extenions: Thunder Client (enable workspace) lynikon i baren på venstre side og

Last ned hoppscotch.io istedenfor Thunder Client? https://hoppscotch.io
Hoppscotch tilater å konstruere meldinger vi sender med HTTP requests.

--

Get Request sendes fra PC. (HOST: URL)
GET /some/path. Optional: Body, headers.

HTTP Verb:
https://hoppscotch.io har en rekke "verb", blant annet GET, POST, PUT og DELETE.

Bytt ut URL adressen på hoppscotch med localhost linken fra dotnet run, dette gjør det mulig å endre "Hello World!" til noe annet. Sender data til serveren. bytt ut teksten i hoppscotch Body og headers etc. Trykk send for outputte en JSON fil i hoppscotch ved å trykkke send til localhost serveren.

--