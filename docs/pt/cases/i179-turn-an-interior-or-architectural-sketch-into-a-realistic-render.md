# Renderização de esboço em espaço realista · Convertendo esboços arquitetônicos em efeitos realistas

[中文](../../../README.md) · [English](../../../README.en.md) · [Português](../../../README.pt.md) · [Español](../../../README.es.md) · [Français](../../../README.fr.md) · [Deutsch](../../../README.de.md) · [عربي](../../../README.ar.md) · [русский](../../../README.ru.md) · [日本語](../../../README.ja.md) · [हिंदी](../../../README.hi.md)


Renderize um desenho arquitetônico ou de linhas internas fornecido sem alterar a estrutura pretendida.

Transforme esboços interiores ou arquitetônicos em representações realistas. Usado para comunicação com o cliente e revisão do programa.

[Copiar prompt](#public-prompt) · [ é produzido por dearsketch / Experimente online](https://dearsketch.com/pt/intent/i179-turn-an-interior-or-architectural-sketch-into-a-realistic-render.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i179_cta) · [Voltar ao tópico / Coleção](../guides/spaces.md)

## Material de referência e direção do resultado

<table>
<thead><tr><th width="50%">Material de referência</th><th width="50%">Exemplo de resultados</th></tr></thead>
<tbody><tr><td valign="top"><p><strong>Esboços de interiores ou arquitetura/wireframes CAD</strong><br><img src="../../../assets/cases/i179-before-1.webp" alt="Esboço arquitetônico convertido em efeito realista - material de referência 1" width="320"></p></td><td valign="top"><a href="https://dearsketch.com/pt/intent/i179-turn-an-interior-or-architectural-sketch-into-a-realistic-render.html?utm_source=github&amp;utm_medium=case&amp;utm_campaign=dearsketch-public-cases&amp;utm_content=i179_image"><img src="../../../assets/cases/i179-after.webp" alt="Esboço arquitetônico para efeito realista - exemplo de resultados" width="320"></a></td></tr></tbody>
</table>

Os materiais de referência e resultados são usados ​​para ilustrar a direção visual. O modelo público não é a instrução de geração original para as imagens que o acompanham e não há garantia de reprodução dos mesmos resultados.

## O que preparar/Insumos

| Material | Tipo / Tipo | Quantidade / Quantidade | Condição/Requisito |
| --- | --- | --- | --- |
| Esboços de interiores ou arquitetura/wireframes CAD | Foto/Imagem | 1 peça | Obrigatório / Obrigatório |
| Uso do espaço e significado do esboço | Personagem/Texto | 1 porção | Obrigatório / Obrigatório |

Apenas uma imagem é gerada por vez.

## Manter e alterar/Editar resumo

- **Preservar / 保留：** Mantenha aberturas, geometria, relações de layout e enquadramento da câmera.
- **Alterar / 改变：** Alterar materiais, iluminação, móveis, paisagem e atmosfera.

## Public prompt

**Modelo público recém-editado · Recém-criado · Não testado em geração.** Substitua os parâmetros de colchetes e anexe os materiais necessários na ferramenta que suporta edição de imagens; entradas opcionais e condicionais são preparadas conforme tabela acima. Este modelo não foi usado para gerar os exemplos nesta página.

```text
Create one realistic rendering from [ARCHITECTURAL OR INTERIOR SKETCH / CAD VIEW].
Interpret the space as [SPACE USE] according to [SKETCH LEGEND OR EXPLANATION].
Preserve all indicated walls, openings, levels, roof lines, built forms, and camera framing.
Apply [MATERIALS], [COLOR PALETTE], [LIGHTING], and [ENVIRONMENT].
Add only the furniture, fixtures, landscape, or people listed in [ADD LIST].
Keep perspective, scale, structural relationships, shadows, and material transitions coherent.
Do not erase ambiguous source lines; resolve uncertainty conservatively or flag it.
Do not claim engineering accuracy, measured dimensions, buildability, or code compliance.
The source drawing remains authoritative when the rendering conflicts with it.
Deliver one realistic concept rendering only.
```

[Faça online com seus próprios materiais / Faça online](https://dearsketch.com/pt/intent/i179-turn-an-interior-or-architectural-sketch-into-a-realistic-render.html?utm_source=github&utm_medium=case&utm_campaign=dearsketch-public-cases&utm_content=i179_after-prompt) · [Deixe o agente ajudá-lo a organizar / Use a habilidade](../quickstart.md#agent-skill)

## Confira os principais pontos/revisão

Verifique a relação entre aberturas e estruturas no esboço e não trate a representação visual como uma verificação de engenharia.

Compare a renderização com as linhas de origem e não a trate como validação de engenharia.

Direção do resultado: renderização de espaço realista. Quando for necessário texto exato, arquivos transparentes, vetores ou entrega impressa, verifique o arquivo real; os recursos e taxas disponíveis estão sujeitos à descrição do site.

## Casos relacionados/Tarefas relacionadas

- [Transforme uma foto de casa em uma aquarela ou uma lembrança de arte · Pintura residencial comemorativa em aquarela ](./i030-turn-a-house-photo-into-a-watercolor-or-line-art-keepsake.md#public-prompt)
- [Visualizar diferentes estilos de interiores em uma foto de quarto · Visualização de estilo de decoração de quarto](./i169-preview-different-interior-styles-in-a-room-photo.md#public-prompt)
- [Crie um conceito de reforma de paisagem a partir de uma foto de quintal · Renovação de paisagem de quintal ](./i178-create-a-landscape-makeover-concept-from-a-yard-photo.md#public-prompt)

## Referência de histórico de requisitos

- [Esboço OpenArt para imagem ](https://openart.ai/generator/sketch/)
- [Ageração de construção Adobe ](https://www.adobe.com/products/firefly/features/ai-architecture-generator.html)

Esses links servem apenas para auxiliar na compreensão do propósito e não são prova da origem ou autorização das imagens desta página.

Para o escopo de uso de imagens e materiais, consulte a descrição do conteúdo [ ](../content-policy.md). [Veja todos os 50 modelos ](../prompts.md).
