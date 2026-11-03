# Início rápido · Selecione um caso, altere materiais e crie uma imagem

[中文](../../README.md) · [English](../../README.en.md) · [Português](../../README.pt.md) · [Español](../../README.es.md) · [Français](../../README.fr.md) · [Deutsch](../../README.de.md) · [عربي](../../README.ar.md) · [русский](../../README.ru.md) · [日本語](../../README.ja.md) · [हिंदी](../../README.hi.md)


## Copiar um prompt

1. Selecione tarefas dos modelos [50 ](./prompts.md) e abra a página do caso.
2. Prepare as entradas necessárias na tabela de materiais para confirmar se o material condicional se aplica a você.
3. Copie Public prompt e substitua o conteúdo entre colchetes. Quando precisar de edição de imagens, anexe a imagem correspondente à sua ferramenta; o texto não pode substituir o anexo de imagem real.
4. Produza um resultado de cada vez e aceite-o de acordo com os pontos de verificação desse caso.

Escolha um modelo, anexe os materiais necessários em sua ferramenta de imagem, preencha seus espaços reservados e analise o resultado. Estes são novos public prompts, reproduções não testadas das imagens de demonstração.

## Agent Skill

Skill é responsável por converter "O que eu quero fazer" em uma lista de entrada clara, retendo pontos-chave e palavras completas de prompt, e não chama a interface de pagamento por padrão. Ele contém sua própria referência de 50 modelos e não depende de toda a biblioteca depois de instalada.

### Codex

Use o instalador integrado em Codex para fornecer o diretório de habilidades deste warehouse:

```text
$skill-installer install the photo-editing skill from
https://github.com/jackclaw9527/awesome-photo-skills/tree/main/skills/photo-editing
```

Você também pode baixar ou clonar o warehouse e colocar a pasta `skills/photo-editing` completa em `.agents/skills/` do projeto de destino; se houver uma habilidade com o mesmo nome, compare primeiro o conteúdo.

Então use:

```text
$photo-editing 把我的自拍做成自然的职业头像。
先告诉我需要哪些素材，再给我可复制的提示词。
```

Exemplo em inglês:

```text
Use $photo-editing to prepare a clean product listing image.
Keep the exact product, tell me what to attach and return a complete prompt.
```

O catálogo de habilidades e o uso do instalador são baseados na documentação [oficial OpenAI](https://learn.chatgpt.com/docs/build-skills). Para outras ferramentas que suportam Agent Skills, instale a pasta inteira de acordo com as respectivas regras do diretório de habilidades.

## Faça isso em dearsketch

Se não quiser organizar as palavras de alerta sozinho, você pode abrir diretamente a tarefa correspondente e fornecer seus próprios materiais de acordo com os requisitos do site:

| Meta | Tarefa direta |
| --- | --- |
| Selfie → Foto profissional / Foto profissional | [Início](https://dearsketch.com/pt/intent/i001-create-a-professional-linkedin-headshot-from-a-selfie.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i001_headshot) |
| Fotos de animais de estimação → Retrato artístico / Retrato de animais de estimação | [Início](https://dearsketch.com/pt/intent/i026-turn-a-pet-photo-into-a-custom-portrait.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i026_pet) |
| Foto do produto → Imagem do produto com fundo branco | [Início](https://dearsketch.com/pt/intent/i065-turn-an-ordinary-product-photo-into-a-white-background-listing-image.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i065_product) |
| Fotos do quarto → Visualização da decoração / Redesenho do quarto | [Início](https://dearsketch.com/pt/intent/i169-preview-different-interior-styles-in-a-room-photo.html?utm_source=github&utm_medium=quickstart&utm_campaign=dearsketch-public-cases&utm_content=i169_room) |

O site mantém processo de produção próprio; as habilidades públicas não exigem que você entregue sua conta do site ou chave de serviço e não inclui cota de geração gratuita. As funções e taxas disponíveis estão sujeitas à descrição atual no site.
