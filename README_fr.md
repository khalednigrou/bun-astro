# Astro & Bun

Un point de départ simplifié pour les projets Astro avec l'intégration de Bun et le rendu côté serveur.

[Read in English](./README.md) | [日本語で読む](./README_ja.md)

## Installer

Installer les dépendances

```sh
bun install
```

## Dev

Démarrer le serveur de développement.

```sh
bun run dev
```

Visitez http://localhost:4321

## Build

Construire le projet.

```sh
bun run build
```

Pour exécuter le projet construit, utilisez la commande suivante.

```sh
bun ./dist/server/entry.mjs
```

Visitez http://localhost:4321 (ou http://127.0.0.1:4321)