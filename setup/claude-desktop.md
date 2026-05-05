# Setup Claude Desktop — Meta Ads MCP

## Prerequis
- Claude Desktop installe (Mac ou Windows)
- Un compte Meta Business avec acces a un compte pub

---

## Etape 1 — Ouvrir les parametres Claude Desktop

`Settings` > `Integrations` > `Add custom MCP server`

---

## Etape 2 — Configurer le serveur

| Champ | Valeur |
|-------|--------|
| Name | Meta Ads |
| URL | `https://mcp.facebook.com/ads` |
| Type | HTTP (Streamable) |

---

## Etape 3 — Authentification OAuth

1. Cliquer "Connect"
2. Connexion avec le compte Facebook associe a ton Business Manager
3. Selectionner le(s) compte(s) pub a autoriser
4. Valider les permissions

---

## Etape 4 — Test de connexion

Dans Claude, tape :
```
Liste mes campagnes Meta actives
```

Si le MCP repond avec tes campagnes, la connexion est operationnelle.

---

## Problemes courants

| Probleme | Solution |
|----------|----------|
| Compte bloque de la beta | Utilise un compte pub avec historique de depenses > 6 mois |
| Erreur OAuth | Verifie que ton utilisateur Facebook a le role "Annonceur" sur le compte pub |
| Token expire | Reconnecte via Settings > Integrations > Reconnect |
| Placements manquants | Audience Network reservation et branded content non disponibles en beta |

---

## Source officielle Meta

[Manage Ads from an AI Agent](https://www.facebook.com/business/help/1456422242197840)