# BlazorAdB2CDemo

Codice di DEMO per l'articolo [Autenticazione con Azure AD B2C in Blazor](https://blazordev.it/articoli/autenticazione-con-azure-ad-b2c-in-blazor/) pubblicato su [Blazor Developer Italiani](https://blazordev.it/).

## Prerequisiti
- .NET 6 SDK
- Account Azure

## Esecuzione
Una volta configurato il tenant Active Directory B2C sul Portal di Azure è sufficiente modificare i file:
- [BlazorAdB2CDemo/Client/wwwroot/appsettings.json](./BlazorAdB2CDemo/Client/wwwroot/appsettings.json)
- [BlazorAdB2CDemo/Server/appsettings.json](./BlazorAdB2CDemo/Server/appsettings.json)

e sostituire i placeholder con i valori presi dalla configurazione del servizio. A questo punto è sufficiente eseguire l'applicazione e verificare che la pagina */fetchdata* sia visibile solo in caso di utente autenticato.

# Contributing
Qualsiasi genere di feedback è sempre bene accetto. Sentitevi liberi di aprire issue, forkare e fare pull request :)
