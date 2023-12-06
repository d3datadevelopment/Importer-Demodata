# D³ Importer Demodaten für OXID eShop

Demodaten für Tests des D3 Importmoduls für OXID eSales

## Systemanforderungen:
- installierter OXID eShop
- D3 Importer Modul ab Version 6.0

## Installation:

Installieren Sie dieses Paket bitte über den folgenden Befehl auf der Konsole Ihres Servers:

```
composer require d3/importer-demodata
```

Füge folgende Informaionen zur composer.json des Projektes hinzu:
```
  "extra": {
    "ajgl-symlinks": {
      "d3/importer-demodata": {
        "source/import/demo_artikel_komplett.csv": "source/import/demo_artikel_komplett.csv",
        "source/import/demo_artikel_test.csv": "source/import/demo_artikel_test.csv"
      }
    }
  }
```