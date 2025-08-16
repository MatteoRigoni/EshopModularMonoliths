# EshopModularMonoliths

> Modular Monolithic Architecture con .NET — approccio modulare, DDD/CQRS-ready, pensato per crescere senza il costo iniziale dei microservizi.

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

## Indice
- [Panoramica](#panoramica)
- [Principi chiave](#principi-chiave)
- [Struttura della soluzione](#struttura-della-soluzione)
- [Prerequisiti](#prerequisiti)
- [Avvio rapido (dev)](#avvio-rapido-dev)
- [Configurazione](#configurazione)
- [Quality & DX](#quality--dx)
- [Roadmap](#roadmap)
- [Licenza](#licenza)

---

## Panoramica

EshopModularMonoliths è un template/progetto didattico per costruire un **monolite modulare** su .NET. L’obiettivo è separare i **moduli di dominio** (boundary chiari, indipendenza dei deploy interni) e abilitare pattern come **CQRS**, **Outbox**, integrazioni asincrone e migrazione graduale verso microservizi quando/solo se necessario.

## Principi chiave

- **Modularità**: confini espliciti tra moduli, dipendenze interne controllate.
- **Indipendenza del dominio**: modellazione con DDD (entità, aggregate, policy).
- **CQRS-friendly**: canali di comando/lettura separabili, proiezioni indipendenti.
- **Observability**: log/metrics/tracing integrabili fin dall’inizio.
- **Dev ergonomics**: script di avvio, hot reload, lint/format.

