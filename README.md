[![Build](https://github.com/Szymek007/WARP-07.DEMO/actions/workflows/build.yml/badge.svg)](https://github.com/Szymek007/WARP-07.DEMO/actions/workflows/build.yml)

Continuous Integration

Projekt korzysta z GitHub Actions do automatycznego sprawdzania poprawnosci dzialania.

Sprawdzany projekt: WARP-07.DEMO/WARP-07.DEMO.csproj

Wersja .NET: 10.0.x

Wykonywane kontrole:

1.Sprawdzenie struktury repozytorium.
2.Przywrocenie zaleznosci (dotnet restore).
3.Budowanie projektu w konfiguracji Release (dotnet build).
4.Uruchomienie projektu (dotnet run).
5.Publikacja projektu (dotnet publish).