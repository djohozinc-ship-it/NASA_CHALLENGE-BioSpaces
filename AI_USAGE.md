# Déclaration d'utilisation de l'intelligence artificielle / Use of Artificial Intelligence

## Outils utilisés / Tools used

- **ChatGPT (OpenAI)** — assistant conversationnel d'IA générative.
- **Claude (Anthropic), via Claude Code** — assistant d'IA générative et de développement.

## Contribution des outils / What the tools did

**ChatGPT** a servi à :

- rédiger la majeure partie du code Python du projet, à partir des consignes de l'équipe (trois personnes), puis le corriger ;
- aider à intégrer un client de consultation des métadonnées et fichiers publics de la NASA OSDR ;
- suggérer des tests unitaires et leur automatisation avec GitHub Actions ;
- relire et structurer de la documentation technique, des références et des explications ;
- aider à identifier des erreurs potentielles et des améliorations de sécurité.

**Claude** a servi à :

- relire le code de détection et corriger deux faiblesses (écart-type de référence nul ou minuscule, tension artérielle basse non surveillée), avec des tests de non-régression ;
- renforcer le client NASA OSDR (certificats TLS, redirections, diagnostic réseau) ;
- réduire des ralentissements de l'interface (connexion SQLite partagée, chargement à la demande) ;
- corriger le formatage du README et rédiger les textes de soumission en anglais.

**English summary.** Most of the source code was drafted by generative AI assistants (ChatGPT and Claude) following the instructions of the team (three people);
AI was also used for tests, documentation and review.
No AI-generated images, video or audio are included in the project. The detection algorithm is a
documented statistical method (personal baseline, z-scores, persistence rule); its behaviour was measured
by the project's own simulation tests, not asserted by an AI tool. AI was not used to modify NASA branding.

## Responsabilité humaine / Human responsibility

L'utilisation de ces outils ne signifie pas que le code, les résultats ou les affirmations scientifiques sont automatiquement exacts. L'équipe du projet (trois personnes) reste chargée de :

- comprendre, examiner, tester et valider le code intégré ;
- vérifier les informations scientifiques dans les publications et dépôts officiels ;
- contrôler les licences, les conditions d'accès et la provenance des données ;
- distinguer clairement les données synthétiques des données de recherche réelles ;
- décider des fonctionnalités et de leur intégration dans BioSpace.
