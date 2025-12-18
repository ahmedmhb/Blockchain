# TP 8 – Développement d’une Application Décentralisée (DApp)

## Présentation

Ce projet a été réalisé dans le cadre du **TP 8 du module Blockchain**.  
Il met en œuvre une **blockchain Ethereum locale**, un **smart contract en Solidity**, et une **application Flutter** permettant d’interagir avec ce contrat via Web3.

L’objectif principal est de comprendre le cycle complet :
**écriture → déploiement → test → interaction front-end** d’un smart contract.

---

## Environnement de travail

- **Blockchain locale** : Ganache
- **Framework Ethereum** : Truffle
- **Langage smart contract** : Solidity
- **Application front-end** : Flutter
- **Communication blockchain** : web3dart (HTTP & WebSocket)
- **Gestion d’état** : Provider

---

## Organisation du projet

```text
contracts/        → Smart contracts Solidity  
migrations/       → Scripts de déploiement Truffle  
test/             → Tests automatisés du contrat  
src/artifacts/    → ABI + adresse du contrat  
lib/              → Code Flutter (UI + logique Web3)
