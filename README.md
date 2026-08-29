# Les agents de Alain

Le catalogue personnel de Alain, construit et tenu a jour par
[apphero](https://apphero.tech). Un depot, autant d'agents que Alain en commande.

## Installer

Dans l'application Claude, une seule fois :

**Reglages → Customize → Plugins → Add → Add marketplace**, puis coller :

```
apphero-tech/agents-alain
```

Laisser **Sync automatically** active. C'est tout.

Les agents apparaissent ensuite dans la liste, a activer d'un clic. Ils sont
disponibles dans **Cowork** — pas de terminal, pas de dossier a choisir, pas de
compte GitHub.

## Les nouveaux agents arrivent seuls

Quand apphero ajoute un agent au catalogue, ou corrige un agent existant, la
mise a jour se fait toute seule. Alain n'a rien a reinstaller : le marketplace est
ajoute une fois, pour toujours.

## Au catalogue aujourd'hui

Voir `.claude-plugin/marketplace.json`. Chaque agent vit dans son propre
dossier sous `plugins/`.
