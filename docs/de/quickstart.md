# Schnellstart · Wählen Sie einen Fall aus, ändern Sie die Materialien und erstellen Sie ein Bild

[中文](../../README.md) · [English](../../README.en.md) · [Português](../../README.pt.md) · [Español](../../README.es.md) · [Français](../../README.fr.md) · [Deutsch](../../README.de.md) · [عربي](../../README.ar.md) · [русский](../../README.ru.md) · [日本語](../../README.ja.md) · [हिंदी](../../README.hi.md)


## Kopieren Sie eine Eingabeaufforderung

1. Wählen Sie Aufgaben aus den [50-Vorlagen ](./prompts.md) aus und öffnen Sie die Fallseite.
2. Bereiten Sie die erforderlichen Eingaben in der Materialtabelle vor, um zu bestätigen, ob das bedingte Material auf Sie zutrifft.
3. Kopieren Sie Public prompt und ersetzen Sie den Inhalt in eckigen Klammern. Wenn Sie eine Bildbearbeitung benötigen, hängen Sie das entsprechende Bild an Ihr Tool an. Der Text kann den eigentlichen Bildanhang nicht ersetzen.
4. Erstellen Sie jeweils ein Ergebnis und akzeptieren Sie es gemäß den Prüfpunkten für den jeweiligen Fall.

Wählen Sie eine Vorlage, fügen Sie die erforderlichen Materialien in Ihr Bildtool ein, füllen Sie die Platzhalter aus und überprüfen Sie das Ergebnis. Dabei handelt es sich um neue public prompts, nicht um getestete Reproduktionen der Demobilder.

## Agent Skill

Skill ist dafür verantwortlich, „Was möchte ich tun?“ in eine übersichtliche Eingabeliste umzuwandeln, wichtige Punkte und vollständige Eingabeaufforderungswörter beizubehalten und standardmäßig nicht die Zahlungsschnittstelle aufzurufen. Es enthält eine eigene Referenz von 50 Vorlagen und ist nach der Installation nicht auf die gesamte Bibliothek angewiesen.

### Codex

Verwenden Sie das integrierte Installationsprogramm in Codex, um das Skill-Verzeichnis dieses Warehouse anzugeben:

```text
$skill-installer install the photo-editing skill from
https://github.com/jackclaw9527/awesome-photo-skills/tree/main/skills/photo-editing
```

Sie können das Warehouse auch herunterladen oder klonen und den vollständigen Ordner `skills/photo-editing` unter `.agents/skills/` des Zielprojekts ablegen; Wenn es einen Skill mit demselben Namen gibt, vergleichen Sie zuerst den Inhalt.

Dann verwenden Sie:

```text
$photo-editing 把我的自拍做成自然的职业头像。
先告诉我需要哪些素材，再给我可复制的提示词。
```

Englisches Beispiel:

```text
Use $photo-editing to prepare a clean product listing image.
Keep the exact product, tell me what to attach and return a complete prompt.
```

Kompetenzkatalog und Nutzungsbasis des Installateurs [offiziell OpenAI Dokumentation](https://learn.chatgpt.com/docs/build-skills). Andere Unterstützung Agent Skills tools installieren Sie bitte den gesamten Ordner gemäß den Regeln des jeweiligen Skill-Verzeichnisses.

## Machen Sie es auf dearsketch

Wenn Sie die Aufforderungsworte nicht selbst organisieren möchten, können Sie direkt die entsprechende Aufgabe öffnen und Ihre eigenen Materialien gemäß den Anforderungen der Website bereitstellen:

| Ziel | Direkte Aufgabe |
| --- | --- |
| Selfie → Professioneller Kopfschuss / Professioneller Kopfschuss | [Start](https://dearsketch.com/de/intent/i001-create-a-professional-linkedin-headshot-from-a-selfie.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i001_headshot) |
| Haustierfotos → Künstlerisches Porträt / Haustierporträt | [Start](https://dearsketch.com/de/intent/i026-turn-a-pet-photo-into-a-custom-portrait.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i026_pet) |
| Produktfoto → Produktbild mit weißem Hintergrund | [Start](https://dearsketch.com/de/intent/i065-turn-an-ordinary-product-photo-into-a-white-background-listing-image.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i065_product) |
| Raumfotos → Dekorationsvorschau / Raumneugestaltung | [Start](https://dearsketch.com/de/intent/i169-preview-different-interior-styles-in-a-room-photo.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i169_room) |

Die Website unterhält einen eigenen Produktionsprozess; Public Skills erfordern nicht die Herausgabe Ihres Website-Kontos oder Serviceschlüssels und beinhalten kein Kontingent für die kostenlose Generierung. Verfügbare Funktionen und Gebühren unterliegen der jeweils aktuellen Beschreibung auf der Website.
