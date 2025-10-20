# Infra Microservice
Microservice Infrastructure components

## Add the GitHub package source
```powershell
$owner="dotnetmicroserviceproject"
$gh_pat="[PAT Here]"

dotnet nuget add source --username OBE96 --password $gh_pat --store-password-in-clear-text --name github "https://nuget.pkg.github.com/$owner/index.json"
```