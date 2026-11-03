# Aperçu virtuel des lunettes · Aperçu de l'essayage des lunettes

[中文](../../../README.md) · [English](../../../README.en.md) · [Português](../../../README.pt.md) · [Español](../../../README.es.md) · [Français](../../../README.fr.md) · [Deutsch](../../../README.de.md) · [عربي](../../../README.ar.md) · [русский](../../../README.ru.md) · [日本語](../../../README.ja.md) · [हिंदी](../../../README.hi.md)


Placez un produit exact ou un concept de lunettes décrit sur un portrait de face.

Essayez virtuellement des lunettes. utilisé dans les décisions d’achat.

[Copier l'invite](#public-prompt) · [ est produit par dearsketch / Essayez en ligne](https://dearsketch.com/fr/intent/i036-virtually-try-on-glasses.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i036_cta) · [RRetour au sujet / Collection](../guides/people.md)

## Matériel de référence et orientation des résultats

<table>
<thead><tr><th width="50%">Matériel de référence</th><th width="50%">Exemple de résultats</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>Photo frontale de la personne</strong><br><img src="../../../assets/cases/i036-before-1.webp" alt="Aperçu de l'essai de lunettes — matériel de référence 1" width="320"></p>
<p><strong>Image du produit des lunettes Target</strong><br><img src="../../../assets/cases/i036-before-2.webp" alt="Aperçu de l'essai de lunettes — matériel de référence 2" width="320"></p></td><td valign="top"><a href="https://dearsketch.com/fr/intent/i036-virtually-try-on-glasses.html?utm_source=github&amp;utm_medium=case&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i036_image"><img src="../../../assets/cases/i036-after.webp" alt="Aperçu de l'essayage des lunettes - exemples de résultats" width="320"></a></td></tr></tbody>
</table>

Les matériaux de référence et les résultats sont utilisés pour illustrer la direction visuelle. Le modèle public ne constitue pas l'instruction de génération originale pour les images qui l'accompagnent, et la reproduction des mêmes résultats n'est pas garantie.

## Que préparer/Intrants

| Matériel | Type / Type | Quantité / Quantité | Condition / Exigence |
| --- | --- | --- | --- |
| Photo frontale de la personne | Photo/Image | 1 pièce | Obligatoire / Obligatoire |
| Description du matériau ou du style des lunettes cibles | Photo/Image | 1 pièce | Conditionnel/Conditionnel : requis pour un essai exact du produit ; seuls les styles de concept peuvent être décrits avec du texte |

Une seule image est générée à la fois.

## Conserver et modifier / Brief d'édition

- **Préserver / 保留：** Conservez l'identité, la forme du visage, la peau, les yeux et les détails de la monture fournis pour la branche choisie.
- **Modifier / 改变：** Modifiez uniquement le placement de la monture, l'apparence des lentilles et l'intégration minimale de l'éclairage.

## Public prompt

**Modèle public récemment modifié · Nouvellement rédigé · Non testé par génération.** Remplacez les paramètres entre crochets et joignez les matériaux requis dans l'outil qui prend en charge l'édition d'images ; les entrées facultatives et conditionnelles sont préparées selon le tableau ci-dessus. Ce modèle n'a pas été utilisé pour générer les exemples sur cette page.

```text
Create one eyewear preview using [FRONT-FACING PERSON PHOTO].
Choose one eyewear branch: use [EYEWEAR PRODUCT IMAGE] for an exact product, or [FRAME STYLE DESCRIPTION] for a concept; do not require both.
Preserve the person’s identity, face shape, eyes, eyebrows, skin tone, hair, and expression.
For the product-image branch, preserve the frame silhouette, color, material, bridge, and temple design exactly.
For the description branch, create only the described frame characteristics without implying a real product match.
Align the frame to the eyes, nose bridge, ears, head angle, and camera perspective.
Render [CLEAR / TINTED / PRESCRIPTION-LIKE] lenses with plausible reflections.
Do not reshape the face or claim exact sizing, optical correction, comfort, or real-world fit.
Keep the original portrait background unless [BACKGROUND CHANGE] is requested.
Deliver one preview image only.
```

[Mettez-le en ligne avec votre propre matériel / Mettez-le en ligne](https://dearsketch.com/fr/intent/i036-virtually-try-on-glasses.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i036_after-prompt) · [Laissez l'agent vous aider à l'organiser / Utilisez la compétence](../quickstart.md#agent-skill)

## Vérifier les points clés/Revue

Si vous souhaitez essayer un produit spécifique, fournissez la photo de style correspondante ; l'image générée ne peut pas prouver la taille réelle et le confort de port.

Vérifiez le pont, les branches, la perspective et notez que l'ajustement et le confort restent non vérifiés.

Sens du résultat : tableau d'essayage des lunettes. Lorsque du texte exact, des fichiers transparents, des vecteurs ou une livraison imprimée sont requis, vérifiez le fichier réel ; les fonctionnalités disponibles et les frais sont sujets à la description du site Web.

## Cas connexes / Tâches connexes

- [Créer une photo professionnelle LinkedIn à partir d'un selfie · Selfie vers une photo professionnelle ](./i001-create-a-professional-linkedin-headshot-from-a-selfie.md#public-prompt)
- [Remplacez les vêtements décontractés par une tenue professionnelle · ](./i015-replace-casual-clothing-with-professional-attire.md#public-prompt)
- [Transformez-vous en portrait royal, vintage ou historique · Portrait royal et vintage ](./i052-turn-yourself-into-a-royal-vintage-or-historical-portrait.md#public-prompt)

## Référence de base des exigences

- [Outil IA Picsart](https://picsart.com/ai/)

Ces liens sont uniquement destinés à aider à comprendre le but et ne constituent pas une preuve de la source ou de l'autorisation des images présentes sur cette page.

Pour connaître le champ d'utilisation des images et du matériel, voir la description du contenu de [ ](../content-policy.md). [Voir les 50 modèles ](../prompts.md).
