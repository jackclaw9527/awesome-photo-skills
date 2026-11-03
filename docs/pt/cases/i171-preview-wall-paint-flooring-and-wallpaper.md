# Pré-visualização de pintura, piso e papel de parede · Pré-visualização da seleção de pintura de parede e material de piso

[中文](../../../README.md) · [English](../../../README.en.md) · [Português](../../../README.pt.md) · [Español](../../../README.es.md) · [Français](../../../README.fr.md) · [Deutsch](../../../README.de.md) · [عربي](../../../README.ar.md) · [русский](../../../README.ru.md) · [日本語](../../../README.ja.md) · [हिंदी](../../../README.hi.md)


Substitua as superfícies especificadas da sala usando uma amostra fornecida ou uma descrição precisa de cor e material.

Visualize efeitos de pintura de parede, piso e papel de parede. Usado para seleção de materiais de decoração.

[Copiar prompt](#public-prompt) · [ é produzido por dearsketch / Experimente online](https://dearsketch.com/pt/intent/i171-preview-wall-paint-flooring-and-wallpaper.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i171_cta) · [Voltar ao tópico / Coleção](../guides/spaces.md)

## Material de referência e direção do resultado

<table>
<thead><tr><th width="50%">Material de referência</th><th width="50%">Exemplo de resultados</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>fotos internas</strong><br><img src="../../../assets/cases/i171-before-1.webp" alt="Visualização da seleção de pintura de parede e material de piso - material de referência 1" width="320"></p>
<p><strong>Modelo de material de destino</strong><br><img src="../../../assets/cases/i171-before-2.webp" alt="Visualização da seleção de pintura de parede e material de piso - material de referência 2" width="320"></p></td><td valign="top"><a href="https://dearsketch.com/pt/intent/i171-preview-wall-paint-flooring-and-wallpaper.html?utm_source=github&amp;utm_medium=case&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i171_image"><img src="../../../assets/cases/i171-after.webp" alt="Visualização da seleção de pintura de parede e material de piso - resultados de exemplo" width="320"></a></td></tr></tbody>
</table>

Os materiais de referência e resultados são usados ​​para ilustrar a direção visual. O modelo público não é a instrução de geração original para as imagens que o acompanham e não há garantia de reprodução dos mesmos resultados.

## O que preparar/Insumos

| Material | Tipo / Tipo | Quantidade / Quantidade | Condição/Requisito |
| --- | --- | --- | --- |
| fotos internas | Foto/Imagem | 1 peça | Obrigatório / Obrigatório |
| Modelo de material de destino | Foto/Imagem | 0–1 imagem; texto exato ou dados de cores também podem ser usados | Condicional: Quando você precisa reproduzir texturas específicas ou amostras de produtos |
| Substitua a superfície pela cor/material alvo | Personagem/Texto | 1 porção | Obrigatório / Obrigatório |

Apenas uma imagem é gerada por vez.

## Manter e alterar/Editar resumo

- **Preservar / 保留：** Mantenha a estrutura da sala, a lógica de iluminação, o posicionamento dos objetos e as superfícies não desejadas.
- **Alterar / 改变：** Altere apenas paredes, pisos ou áreas de papel de parede nomeadas.

## Public prompt

**Modelo público recém-editado · Recém-criado · Não testado em geração.** Substitua os parâmetros de colchetes e anexe os materiais necessários na ferramenta que suporta edição de imagens; entradas opcionais e condicionais são preparadas conforme tabela acima. Este modelo não foi usado para gerar os exemplos nesta página.

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

[Faça online com seus próprios materiais / Faça online](https://dearsketch.com/pt/intent/i171-preview-wall-paint-flooring-and-wallpaper.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i171_after-prompt) · [Deixe o agente ajudá-lo a organizar / Use a habilidade](../quickstart.md#agent-skill)

## Confira os principais pontos/revisão

Os produtos especificados devem fornecer amostras ou informações precisas sobre cores; a imagem da tela não pode garantir a mesma diferença de cor do produto real.

Compare com uma amostra quando existir e avise que as telas não podem garantir a cor real do material.

Direção do resultado: visualização dos efeitos do material. Quando for necessário texto exato, arquivos transparentes, vetores ou entrega impressa, verifique o arquivo real; os recursos e taxas disponíveis estão sujeitos à descrição do site.

## Casos relacionados/Tarefas relacionadas

- [Transforme uma foto de casa em uma aquarela ou uma lembrança de arte · Pintura residencial comemorativa em aquarela ](./i030-turn-a-house-photo-into-a-watercolor-or-line-art-keepsake.md#public-prompt)
- [Visualizar diferentes estilos de interiores em uma foto de quarto · Visualização de estilo de decoração de quarto](./i169-preview-different-interior-styles-in-a-room-photo.md#public-prompt)
- [Crie um conceito de reforma de paisagem a partir de uma foto de quintal · Renovação de paisagem de quintal ](./i178-create-a-landscape-makeover-concept-from-a-yard-photo.md#public-prompt)

## Referência de histórico de requisitos

- [LightXTodas as ferramentas](https://www.lightxeditor.com/all-tools/all-tools/)
- [Conceito do Adobe Home](https://www.adobe.com/products/firefly/features/ai-room-design/home-design.html)

Esses links servem apenas para auxiliar na compreensão do propósito e não são prova da origem ou autorização das imagens desta página.

Para o escopo de uso de imagens e materiais, consulte a descrição do conteúdo [ ](../content-policy.md). [Veja todos os 50 modelos ](../prompts.md).
