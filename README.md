# 🌌 Qovyn Studio — Premium Agentic IDE

[![Version](https://img.shields.io/badge/version-1.1.0-blue.svg)](https://qovyn-studio.vercel.app)
[![Status](https://img.shields.io/badge/status-active-success.svg)](https://qovyn-studio.vercel.app)
[![License](https://img.shields.io/badge/license-proprietary-red.svg)](https://qovyn-studio.vercel.app/terms)

> **Qovyn Studio** is a next-generation, high-performance agentic IDE designed for autonomous software development. By leveraging frontier AI models and native agentic workflows, Qovyn transforms the IDE from a text editor into a true autonomous collaborator.

---

## 🚀 The Agentic Edge

Qovyn Studio is built for developers who demand peak productivity. It goes beyond autocomplete to offer a full-cycle development experience.

* **🔄 Autonomous Agent Loops**: Agents can plan, execute, and self-critique complex multi-file changes.
* **🐙 Deep GitHub Integration**: Build, commit, list issues, and open Pull Requests directly from the agent interface.
* **⚡ Free Frontier Models**: Powered by **Puter.js**, providing access to high-end models without subscription friction.
* **🧠 Hierarchical Memory**: Long-term task retention and context-aware reasoning.

---

## 💰 Why Qovyn beats \$20/month subscriptions

The market is flooded with \$20/month AI coding tools. Qovyn Studio gives you more for less — or for free.

| Feature | Qovyn Studio | Claude Code / Codex |
|---|---|---|
| **Pricing** | Free tier available — \$0 to start | \$20/month minimum |
| **Models** | Bring your own API key or use free Puter.js models | Locked to their model |
| **Provider fallback** | 18 providers in an automatic fallback chain — if one fails, the next takes over | Single provider, single point of failure |
| **Agent loop** | Autonomous plan → execute → verify cycle with self-correction | Basic chat with file read/write |
| **File snapshots** | Automatic file snapshots before every mutation — revert any change | No built-in revert |
| **Inline completion** | Context-aware, no-subscription completion via the same provider chain | Included, but only with subscription |
| **Diff view** | Side-by-side Monaco diff for every agent change | Text-only diffs |
| **Privacy Shield** | Auto-excludes sensitive files (.env, .pem, credentials) from agent context | Manual configuration required |
| **Terminal integration** | Full PowerShell terminal with command execution, async commands, and session management | Limited terminal access |

**The bottom line**: If you already have an API key (OpenAI, Anthropic, Google, Groq, etc.), Qovyn costs you nothing. You use your own quota at cost price — no monthly markup. And if you want to start for free, Puter.js gives you access to frontier models immediately.

---

## 🔧 Features that matter

### True autonomy, not just chat

Qovyn's agent loop is structurally different from a chatbot with file access. Each turn follows a disciplined cycle:

1. **Think** — the agent analyzes the task and context
2. **Act** — one mutation per turn (write, edit, delete, create) plus any number of reads
3. **Verify** — the system automatically lists the parent directory after every mutation so the agent confirms the result
4. **Repeat** — the agent continues until all plan items are complete or it needs clarification

This means the agent never races ahead creating three files at once and assuming success. It confirms each step before proceeding — like a senior developer reviewing their own work.

### 18-provider fallback chain

Qovyn doesn't lock you into one model. Configure multiple providers and the system cascades through them automatically on failure:

```
OpenAI → Anthropic → Google Gemini → Groq → OpenRouter → GitHub Models
→ Azure OpenAI → Together AI → DeepInfra → Cerebras → NVIDIA NIM
→ Fireworks AI → Mistral AI → OpenCode AI → Kimi → Z.ai
→ Wafer AI → Puter.js (free)
```

Your workflow never stops because one API is down.

### File snapshots & revert

Before every file mutation, Qovyn takes a snapshot of the affected files. You can revert to any point in the agent's timeline — undoing changes file by file or in bulk. No more "the AI broke my code and I can't get it back."

### Diff preview for every change

Every write, edit, or replacement the agent makes can be opened in Monaco's side-by-side diff editor. Green for new lines, red for removed — clear, visual, immediate.

### Terminal as a first-class tool

The agent runs real PowerShell commands, not simulations. It can execute builds, run tests, install packages, check file existence, and read command output — all within the same loop that writes your code.

---

## 📥 Getting Started

Qovyn Studio is currently in **Early Access**.

1. **Download**: Get the latest build for your OS from the [Official Website](https://qovyn-studio.vercel.app).
2. **Install**:
   * **Windows**: Run the `.exe`. Note: As an indie project, you may see a "SmartScreen" warning. Click *More Info* -> *Run Anyway*.
   * **macOS and Linux**: Coming soon.
3. **Connect**: Link your GitHub account to enable autonomous PR workflows.

### First run

Open the app, switch to **Agent mode**, and try:

```
Create a responsive navbar component with HTML, CSS, and a dark mode toggle
```

Watch the agent plan the files, create them one by one, verify each step, and report back. No \$20 subscription required.

---

## 💬 Community & Feedback

This repository is the dedicated hub for the Qovyn Studio community. While the core engine remains proprietary, we are committed to building Qovyn in the open with our users.

* **🐛 Bug Reports**: Use the [Issues](https://github.com/braeljr/qovyn-studio-feedback/issues) tab to report reproducible bugs.
* **💡 Feature Requests**: Have an idea for a new agent tool? Open a [Discussion](https://github.com/braeljr/qovyn-studio-feedback/discussions).
* **📖 Documentation**: Check our [Docs](https://qovyn-studio.vercel.app/docs) for advanced configuration.

---

## 🛡️ Privacy & Security

Qovyn Studio is designed with a **Privacy-First** architecture:
* **Privacy Shield**: Sensitive files (`.env`, `.pem`, etc.) are automatically ignored by the AI agent.
* **Local Processing**: File indexing and context synthesis happen entirely on your local machine.
* **Your key, your cost**: When using your own API keys, Qovyn charges nothing — you pay only what your provider charges.

---

## 🗺️ Roadmap

* macOS and Linux native builds
* Agent version control with visual branch timeline
* Custom tool creation API
* Team collaboration mode with shared agent contexts
* VS Code extension mode

---

*Built with ❤️ by the Qovyn Studio Team.*

---

<a id="francais"></a>

# 🌌 Qovyn Studio — IDE Agentique Premium

[![Version](https://img.shields.io/badge/version-1.1.0-blue.svg)](https://qovyn-studio.vercel.app)
[![Statut](https://img.shields.io/badge/statut-actif-success.svg)](https://qovyn-studio.vercel.app)
[![Licence](https://img.shields.io/badge/licence-propriétaire-red.svg)](https://qovyn-studio.vercel.app/terms)

> **Qovyn Studio** est un IDE agentique de nouvelle génération, hautes performances, conçu pour le développement logiciel autonome. En exploitant des modèles d'IA de pointe et des flux de travail agentiques natifs, Qovyn transforme l'IDE d'un éditeur de texte en un véritable collaborateur autonome.

---

## 🚀 L'Avantage Agentique

Qovyn Studio est conçu pour les développeurs qui exigent une productivité maximale. Il va bien au-delà de l'autocomplétion pour offrir une expérience de développement complète.

* **🔄 Boucles d'Agent Autonomes** : Les agents peuvent planifier, exécuter et s'auto-critiquer sur des modifications complexes multi-fichiers.
* **🐙 Intégration GitHub Profonde** : Construire, commiter, lister les issues et ouvrir des Pull Requests directement depuis l'interface agent.
* **⚡ Modèles Frontière Gratuits** : Propulsé par **Puter.js**, donnant accès à des modèles haut de gamme sans abonnement.
* **🧠 Mémoire Hiérarchique** : Rétention des tâches à long terme et raisonnement contextuel.

---

## 💰 Pourquoi Qovyn bat les abonnements à \$20/mois

Le marché est saturé d'outils de codage IA à \$20/mois. Qovyn Studio vous donne plus pour moins cher — ou gratuitement.

| Fonctionnalité | Qovyn Studio | Claude Code / Codex |
|---|---|---|
| **Tarification** | Gratuit disponible — \$0 pour commencer | Minimum \$20/mois |
| **Modèles** | Votre propre clé API ou modèles Puter.js gratuits | Verrouillé sur leur modèle |
| **Repli fournisseur** | 18 fournisseurs en chaîne de repli automatique | Un seul fournisseur, point de défaillance unique |
| **Boucle agent** | Cycle autonome planifier → exécuter → vérifier avec auto-correction | Chat basique avec lecture/écriture de fichiers |
| **Instantanés fichiers** | Instantanés automatiques avant chaque mutation — restaurez toute modification | Pas de restauration intégrée |
| **Complétion intégrée** | Contextuelle, sans abonnement via la même chaîne de fournisseurs | Incluse, mais seulement avec abonnement |
| **Vue Diff** | Diff Monaco côte à côte pour chaque changement agent | Diffs textuels uniquement |
| **Bouclier de Confidentialité** | Exclusion auto des fichiers sensibles (.env, .pem) du contexte agent | Configuration manuelle requise |
| **Intégration Terminal** | Terminal PowerShell complet avec exécution de commandes | Accès terminal limité |

**En résumé** : Si vous avez déjà une clé API (OpenAI, Anthropic, Google, Groq, etc.), Qovyn ne vous coûte rien. Vous utilisez votre propre quota au prix coûtant — sans majoration mensuelle. Et si vous voulez commencer gratuitement, Puter.js vous donne accès aux modèles de pointe immédiatement.

---

## 🔧 Fonctionnalités essentielles

### Une vraie autonomie, pas seulement du chat

La boucle d'agent de Qovyn est structurellement différente d'un chatbot avec accès aux fichiers. Chaque tour suit un cycle discipliné :

1. **Réfléchir** — l'agent analyse la tâche et le contexte
2. **Agir** — une mutation par tour (écriture, édition, suppression, création) plus autant de lectures que nécessaire
3. **Vérifier** — le système liste automatiquement le répertoire parent après chaque mutation pour que l'agent confirme le résultat
4. **Répéter** — l'agent continue jusqu'à ce que tous les éléments du plan soient terminés ou qu'il ait besoin de clarification

Cela signifie que l'agent ne crée jamais trois fichiers à la fois en supposant la réussite. Il confirme chaque étape avant de continuer — comme un développeur senior qui révise son propre travail.

### Chaîne de repli de 18 fournisseurs

Qovyn ne vous enferme pas dans un seul modèle. Configurez plusieurs fournisseurs et le système cascade automatiquement en cas d'échec :

```
OpenAI → Anthropic → Google Gemini → Groq → OpenRouter → GitHub Models
→ Azure OpenAI → Together AI → DeepInfra → Cerebras → NVIDIA NIM
→ Fireworks AI → Mistral AI → OpenCode AI → Kimi → Z.ai
→ Wafer AI → Puter.js (gratuit)
```

Votre flux de travail ne s'arrête jamais parce qu'une API est indisponible.

### Instantanés de fichiers & restauration

Avant chaque mutation de fichier, Qovyn prend un instantané des fichiers concernés. Vous pouvez revenir à n'importe quel point dans la chronologie de l'agent — annulant les modifications fichier par fichier ou en bloc. Fini le "l'IA a cassé mon code et je ne peux pas le récupérer."

### Aperçu Diff pour chaque changement

Chaque écriture, édition ou remplacement effectué par l'agent peut être ouvert dans l'éditeur de diff côte à côte de Monaco. Vert pour les nouvelles lignes, rouge pour les supprimées — clair, visuel, immédiat.

### Terminal comme outil de première classe

L'agent exécute de vraies commandes PowerShell, pas des simulations. Il peut exécuter des builds, lancer des tests, installer des paquets, vérifier l'existence de fichiers et lire les sorties de commandes — tout dans la même boucle qui écrit votre code.

---

## 📥 Pour Commencer

Qovyn Studio est actuellement en **Accès Anticipé**.

1. **Téléchargement** : Obtenez la dernière version pour votre OS sur le [Site Officiel](https://qovyn-studio.vercel.app).
2. **Installation** :
   * **Windows** : Exécutez le `.exe`. Note : En tant que projet indie, vous pouvez voir un avertissement "SmartScreen". Cliquez sur *Plus d'infos* -> *Exécuter quand même*.
   * **macOS et Linux** : À venir.
3. **Connexion** : Liez votre compte GitHub pour activer les flux de travail PR autonomes.

### Premier lancement

Ouvrez l'application, passez en **Mode Agent**, et essayez :

```
Créez un composant navbar responsive avec HTML, CSS et un bouton de mode sombre
```

Regardez l'agent planifier les fichiers, les créer un par un, vérifier chaque étape et faire son rapport. Aucun abonnement à \$20 requis.

---

## 💬 Communauté & Commentaires

Ce dépôt est le hub dédié à la communauté Qovyn Studio. Bien que le moteur principal reste propriétaire, nous nous engageons à construire Qovyn ouvertement avec nos utilisateurs.

* **🐛 Rapports de Bugs** : Utilisez l'onglet [Issues](https://github.com/braeljr/qovyn-studio-feedback/issues) pour signaler des bugs reproductibles.
* **💡 Demandes de Fonctionnalités** : Vous avez une idée pour un nouvel outil agent ? Ouvrez une [Discussion](https://github.com/braeljr/qovyn-studio-feedback/discussions).
* **📖 Documentation** : Consultez notre [Docs](https://qovyn-studio.vercel.app/docs) pour la configuration avancée.

---

## 🛡️ Confidentialité & Sécurité

Qovyn Studio est conçu avec une architecture **Confidentialité d'Abord** :
* **Bouclier de Confidentialité** : Les fichiers sensibles (`.env`, `.pem`, etc.) sont automatiquement ignorés par l'agent IA.
* **Traitement Local** : L'indexation des fichiers et la synthèse du contexte se font entièrement sur votre machine locale.
* **Votre clé, votre coût** : Lorsque vous utilisez vos propres clés API, Qovyn ne facture rien — vous payez uniquement ce que votre fournisseur vous facture.

---

## 🗺️ Feuille de Route

* Versions natives macOS et Linux
* Contrôle de version agent avec chronologie visuelle des branches
* API de création d'outils personnalisés
* Mode collaboration d'équipe avec contextes d'agent partagés
* Mode extension VS Code

---

*Construit avec ❤️ par l'Équipe Qovyn Studio.*
