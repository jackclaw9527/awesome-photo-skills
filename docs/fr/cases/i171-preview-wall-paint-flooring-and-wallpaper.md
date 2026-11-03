# Aperçu de la peinture, du revêtement de sol et du papier peint · Aperçu de la sélection de la peinture murale et des matériaux de sol

[中文](../../../README.md) · [English](../../../README.en.md) · [Português](../../../README.pt.md) · [Español](../../../README.es.md) · [Français](../../../README.fr.md) · [Deutsch](../../../README.de.md) · [عربي](../../../README.ar.md) · [русский](../../../README.ru.md) · [日本語](../../../README.ja.md) · [हिंदी](../../../README.hi.md)


Remplacez les surfaces spécifiées de la pièce en utilisant soit un échantillon fourni, soit une description précise de la couleur et du matériau.

Prévisualisez les effets de la peinture murale, du sol et du papier peint. Utilisé pour la sélection des matériaux de décoration.

[Copier l'invite](#public-prompt) · [ est produit par dearsketch / Essayez en ligne](https://dearsketch.com/fr/intent/i171-preview-wall-paint-flooring-and-wallpaper.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i171_cta) · [RRetour au sujet / Collection](../guides/spaces.md)

## Matériel de référence et orientation des résultats

<table>
<thead><tr><th width="50%">Matériel de référence</th><th width="50%">Exemple de résultats</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>photos d'intérieur</strong><br><img src="../../../assets/cases/i171-before-1.webp" alt="Aperçu de la sélection de la peinture murale et des matériaux de sol - matériel de référence 1" width="320"></p>
<p><strong>Modèle de matériau cible</strong><br><img src="../../../assets/cases/i171-before-2.webp" alt="Aperçu de la sélection de la peinture murale et des matériaux de sol - matériel de référence 2" width="320"></p></td><td valign="top"><a href="https://dearsketch.com/fr/intent/i171-preview-wall-paint-flooring-and-wallpaper.html?utm_source=github&amp;utm_medium=case&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i171_image"><img src="../../../assets/cases/i171-after.webp" alt="Aperçu de la sélection de la peinture murale et du matériau du sol - exemples de résultats" width="320"></a></td></tr></tbody>
</table>

Les matériaux de référence et les résultats sont utilisés pour illustrer la direction visuelle. Le modèle public ne constitue pas l'instruction de génération originale pour les images qui l'accompagnent, et la reproduction des mêmes résultats n'est pas garantie.

## Que préparer/Intrants

| Matériel | Type / Type | Quantité / Quantité | Condition / Exigence |
| --- | --- | --- | --- |
| photos d'intérieur | Photo/Image | 1 pièce | Obligatoire / Obligatoire |
| Modèle de matériau cible | Photo/Image | 0 à 1 image ; du texte exact ou des données de couleur peuvent également être utilisés | Conditionnel : lorsque vous devez reproduire des textures ou des échantillons de produits spécifiques |
| Remplacer la surface par la couleur/le matériau cible | Caractère / Texte | 1 portion | Obligatoire / Obligatoire |

Une seule image est générée à la fois.

## Conserver et modifier / Brief d'édition

- **Préserver / 保留：** Conservez la structure de la pièce, la logique d'éclairage, le placement des objets et les surfaces non ciblées.
- **Modifier / 改变：** Modifiez uniquement les zones nommées des murs, du sol ou du papier peint.

## Public prompt

**Modèle public récemment modifié · Nouvellement rédigé · Non testé par génération.** Remplacez les paramètres entre crochets et joignez les matériaux requis dans l'outil qui prend en charge l'édition d'images ; les entrées facultatives et conditionnelles sont préparées selon le tableau ci-dessus. Ce modèle n'a pas été utilisé pour générer les exemples sur cette page.

```text
Create one material preview from [INTERIOR PHOTO].
Choose one target branch: use [TARGET MATERIAL OR COLOR SAMPLE] when matching a specific texture or product, or use [ACCURATE COLOR AND MATERIAL DESCRIPTION] when no sample exists.
Apply the chosen [PAINT / FLOORING / WALLPAPER] only to [EXACT SURFACES TO REPLACE].
Preserve doors, windows, trim, furniture, room geometry, camera angle, and all untargeted surfaces.
When a sample is supplied, retain its dominant color, pattern scale, grain direction, and finish as closely as possible.
Respect corners, occlusion, seams, perspective, reflections, and existing light falloff.
Do not recolor furnishings, skin, artwork, or adjacent surfaces.
Do not invent named-product availability, dimensions, finish, or performance claims.
Treat the preview as an approximation; verify physical samples and measured quantities before purchase or installation.
Deliver one edited material-preview image only.
```

[Mettez-le en ligne avec votre propre matériel / Mettez-le en ligne](https://dearsketch.com/fr/intent/i171-preview-wall-paint-flooring-and-wallpaper.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i171_after-prompt) · [Laissez l'agent vous aider à l'organiser / Utilisez la compétence](../quickstart.md#agent-skill)

## Vérifier les points clés/Revue

Les produits spécifiés doivent fournir des échantillons ou des informations précises sur les couleurs ; l'image de l'écran ne peut pas garantir la même différence de couleur que le produit réel.

Comparez avec un échantillon lorsqu'il en existe et prévenez que les écrans ne peuvent pas garantir la vraie couleur du matériau.

Direction du résultat : aperçu des effets de matière. Lorsque du texte exact, des fichiers transparents, des vecteurs ou une livraison imprimée sont requis, vérifiez le fichier réel ; les fonctionnalités disponibles et les frais sont sujets à la description du site Web.

## Cas connexes / Tâches connexes

- [Transformez une photo de maison en un souvenir d'aquarelle ou de dessin au trait · Peinture commémorative à l'aquarelle résidentielle ](./i030-turn-a-house-photo-into-a-watercolor-or-line-art-keepsake.md#public-prompt)
- [Aperçu des différents styles d'intérieur dans une photo de pièce · Aperçu du style de décoration de la pièce](./i169-preview-different-interior-styles-in-a-room-photo.md#public-prompt)
- [Créez un concept de relooking paysager à partir d'une photo de cour · Rénovation paysagère de cour ](./i178-create-a-landscape-makeover-concept-from-a-yard-photo.md#public-prompt)

## Référence de base des exigences

- [LightXTous les outils](https://www.lightxeditor.com/all-tools/all-tools/)
- [Adobe Home Concept](https://www.adobe.com/products/firefly/features/ai-room-design/home-design.html)

Ces liens sont uniquement destinés à aider à comprendre le but et ne constituent pas une preuve de la source ou de l'autorisation des images présentes sur cette page.

Pour connaître le champ d'utilisation des images et du matériel, voir la description du contenu de [ ](../content-policy.md). [Voir les 50 modèles ](../prompts.md).
