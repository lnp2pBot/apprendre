# Documentation en Français

[Site de la documentation en français](https://lnp2pbot.com/apprendre/)

## Pour les contributeurs

### Prérequis

* Installer [Just](https://github.com/casey/just)
```bash
cargo install just
```

### Procédures

#### Initialiser le projet

Initialise le projet de documentation mdBook avec les dépendances requises.

```bash
just init
```

#### Servir localement

Démarre un serveur de développement local avec rechargement en direct pour prévisualisation.

```bash
just serve
```

#### Compiler la documentation

Génère le site de documentation statique pour le déploiement en production.

```bash
just build
```
