# Localnord pour Claude

Le skill Localnord apprend à Claude les routines d'une agence Google Business Profile : revue de la semaine, réponses aux avis, suivi client, prospection. Avec le connecteur Localnord, Claude exécute les étapes et vous demande votre accord avant toute publication sur Google ou action payante. Sans connecteur, il vous conseille avec la même méthode à partir des informations que vous lui donnez.

## Installer

**claude.ai et application Claude (Mac, Windows)**

1. Téléchargez le skill : https://app.localnord.io/api/mcp/skill
2. Dans Claude, rubrique Skills, téléversez le fichier `localnord-skill.zip`. Les skills demandent que l'exécution de code soit activée.
3. Pour les routines, ajoutez aussi le connecteur Localnord : dans Claude, rubrique Connecteurs, ajoutez un connecteur personnalisé avec l'adresse `https://app.localnord.io/api/mcp/mcp`, puis connectez-vous à Localnord.

**Claude Code**

```bash
claude plugin marketplace add robingst/localnord-skills
claude plugin install localnord@localnord-skills
```

Le skill et le connecteur s'installent ensemble. Lancez ensuite `/mcp` dans Claude Code pour vous connecter à Localnord.

**Cowork** : depuis la gestion des plugins de l'application Claude, ajoutez la marketplace `robingst/localnord-skills`, puis installez `localnord`.

**Claude Team et Enterprise** : un administrateur peut téléverser `localnord-skill.zip` une fois pour toute l'organisation.

## Essayer

- « Fais ma revue du lundi »
- « Réponds aux avis en attente de [nom de la fiche] »
- « Prépare mon rendez-vous avec [client] »
- « Trouve-moi 5 plombiers à prospecter à Lyon »
- Sans connecteur : « Ma fiche Google est suspendue, que faire ? »

Pas encore client ? Essai gratuit sur https://www.localnord.io

---

# Localnord for Claude

The Localnord skill teaches Claude the routines of a Google Business Profile agency: weekly review, review replies, client follow-up, prospecting. With the Localnord connector, Claude runs the steps and asks for your approval before anything is published on Google or any paid action. Without the connector, it advises you with the same method from the information you give it.

## Install

**claude.ai and the Claude app (Mac, Windows)**

1. Download the skill: https://app.localnord.io/api/mcp/skill
2. In Claude, Skills section, upload `localnord-skill.zip`. Skills require code execution to be turned on.
3. For the routines, also add the Localnord connector: in Claude, Connectors section, add a custom connector with the URL `https://app.localnord.io/api/mcp/mcp`, then sign in to Localnord.

**Claude Code**

```bash
claude plugin marketplace add robingst/localnord-skills
claude plugin install localnord@localnord-skills
```

The skill and the connector install together. Then run `/mcp` in Claude Code to sign in to Localnord.

**Cowork**: from plugin management in the Claude app, add the `robingst/localnord-skills` marketplace, then install `localnord`.

**Claude Team and Enterprise**: an admin can upload `localnord-skill.zip` once for the whole organization.

## Try it

- "Run my Monday review"
- "Reply to the pending reviews of [listing name]"
- "Prepare my meeting with [client]"
- "Find me 5 plumbers to prospect in Lyon"
- Without the connector: "My Google listing is suspended, what should I do?"

Not a customer yet? Free trial at https://www.localnord.io
