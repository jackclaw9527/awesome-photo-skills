# Démarrage rapide · Sélectionnez un étui, changez les matériaux et créez une image

[中文](../../README.md) · [English](../../README.en.md) · [Português](../../README.pt.md) · [Español](../../README.es.md) · [Français](../../README.fr.md) · [Deutsch](../../README.de.md) · [عربي](../../README.ar.md) · [русский](../../README.ru.md) · [日本語](../../README.ja.md) · [हिंदी](../../README.hi.md)


## Copier une invite

1. Sélectionnez des tâches dans les modèles [50 ](./prompts.md) et ouvrez la page du cas.
2. Préparez les entrées requises dans le tableau des matériaux pour confirmer si les matériaux conditionnels s'appliquent à vous.
3. Copiez Public prompt et remplacez le contenu entre crochets. Lorsque vous avez besoin d'éditer une image, attachez l'image correspondante à votre outil ; le texte ne peut pas remplacer l’image jointe réelle.
4. Produisez un résultat à la fois et acceptez-le selon les points de contrôle de ce cas.

Choisissez un modèle, joignez les matériaux requis dans votre outil d'image, remplissez ses espaces réservés et examinez le résultat. Ce sont de nouveaux public prompt, des reproductions non testées des images de démonstration.

## Agent Skill

Skill est chargé de convertir « Qu'est-ce que je veux faire » en une liste de saisie claire, en conservant les points clés et les mots d'invite complets, et n'appelle pas l'interface de paiement par défaut. Il contient sa propre référence de 50 modèles et ne s'appuie pas sur l'intégralité de la bibliothèque une fois installée.

### Codex

Utilisez le programme d'installation intégré dans Codex pour donner le répertoire de compétences de cet entrepôt :

```text
$skill-installer install the photo-editing skill from
https://github.com/jackclaw9527/awesome-photo-skills/tree/main/skills/photo-editing
```

Vous pouvez également télécharger ou cloner l'entrepôt et placer le dossier `skills/photo-editing` complet sous `.agents/skills/` du projet cible ; s'il existe une compétence portant le même nom, comparez d'abord le contenu.

Utilisez ensuite :

```text
$photo-editing 把我的自拍做成自然的职业头像。
先告诉我需要哪些素材，再给我可复制的提示词。
```

Exemple en anglais :

```text
Use $photo-editing to prepare a clean product listing image.
Keep the exact product, tell me what to attach and return a complete prompt.
```

Le catalogue de compétences et l'utilisation de l'installateur sont basés sur la documentation officielle [ OpenAI](https://learn.chatgpt.com/docs/build-skills). Pour les autres outils prenant en charge les Agent Skill, veuillez installer l'intégralité du dossier conformément aux règles de leur répertoire de compétences respectives.

## Faites-le sur dearsketch

Si vous ne souhaitez pas organiser vous-même les mots-clés, vous pouvez ouvrir directement la tâche correspondante et fournir votre propre matériel selon les exigences du site Web :

| But | Tâche directe |
| --- | --- |
| Selfie → Portrait professionnel / Portrait professionnel | [Start](https://dearsketch.com/fr/intent/i001-create-a-professional-linkedin-headshot-from-a-selfie.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i001_headshot) |
| Photos d'animaux → Portrait artistique / Portrait d'animaux | [Start](https://dearsketch.com/fr/intent/i026-turn-a-pet-photo-into-a-custom-portrait.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i026_pet) |
| Photo du produit → Image du produit sur fond blanc | [Start](https://dearsketch.com/fr/intent/i065-turn-an-ordinary-product-photo-into-a-white-background-listing-image.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i065_product) |
| Photos de la pièce → Aperçu de la décoration / Refonte de la pièce | [Start](https://dearsketch.com/fr/intent/i169-preview-different-interior-styles-in-a-room-photo.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i169_room) |

Le site Web maintient son propre processus de production ; Les compétences publiques ne vous obligent pas à remettre votre compte de site Web ou votre clé de service, et n'incluent pas de quota de génération gratuit. Les fonctions et les frais disponibles sont soumis à la description alors en vigueur sur le site Web.
