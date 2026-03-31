---
title: "Product Brief Distillate: zbt-learning"
type: llm-distillate
source: "product-brief-zbt-learning.md"
created: "2026-03-30"
purpose: "Contexto condensado para PRD e próximas fases"
---

## Referência de mercado (público)

- Brasil Paralelo combina streaming com **Núcleo de Formação**: dezenas de cursos gravados, professores, áreas como história, filosofia, política, artes; planos por faixa de preço; menção pública a **materiais em PDF** e **garantia de reembolso em 7 dias** em materiais de assinatura — útil como **benchmark de oferta e empacotamento**, não como template de posicionamento.

## Intenção do usuário

- Produto desejado: **plataforma de treinamentos online**.
- Inspiração explícita: **parecido com o portal de treinamentos da Brasil Paralelo** (experiência de catálogo + membro + cursos).

## Requisitos implícitos / hints

- Vídeo on-demand como núcleo.
- Catálogo e páginas de curso com estrutura de módulos/aulas.
- Modelo comercial compatível com **assinatura em níveis** e/ou pacotes (validar com negócio).
- Área logada com progresso e acesso a materiais complementares.
- Idioma e mercado: **Brasil** (LGPD, CDC, expectativa de transparência de planos).

## Cenários de usuário (detalhados)

- Aluno descobre curso no catálogo → lê benefícios e grade → assina ou compra → assiste no player → retoma depois no mesmo ponto → baixa ou acessa PDF se o curso oferecer.
- Operador publica novo módulo ou atualiza aula → alunos existentes veem atualização sem quebra de acesso.

## Ideias adjacentes (não decididas; não reabrir sem alinhamento)

- **B2B / corporativo**: licenças em lote, relatório de progresso para RH.
- **Certificados** com identificação do aluno (validar fraude e custo).
- **Comunidade** (fórum, Discord embutido): alto custo de moderação na V1.
- **App nativo com offline**: depois de validar web e retenção.

## Premissas a validar

- Nicho e proposta de valor única (o brief trata a **plataforma** como neutra).
- Fonte de conteúdo (próprio vs parceiros) e pipeline de produção.
- Precificação e política de reembolso com apoio jurídico.

## Riscos (revisão cética)

- Dependência de **pipeline de conteúdo** para manter assinatura.
- **Aquisição paga** com CAC alto em nicho saturado.
- Escopo “igual ao referência” sem priorização leva a V1 eterna.

## Perguntas abertas

- Público-alvo primário (B2C massa, comunidade fechada, corporativo)?
- Apenas assinatura, apenas cursos avulsos, ou híbrido no lançamento?
- Integração de pagamento preferida (gateway, Pix recorrente, etc.)?
- Hospedagem de vídeo (própria vs Vimeo/Wowza/Mux etc.)?

## Sinais de escopo

- **In (direção MVP):** catálogo, curso, player, progresso, auth, planos/pagamento, área do aluno, materiais por curso, admin mínimo.
- **Out (até nova decisão):** multi-tenant marketplace, DRM avançado, live complexo, comunidade pesada.

## Rejeitado nesta sessão

- Nada formalmente rejeitado pelo usuário; evitar tratar “cópia de marca/conteúdo BP” como objetivo — referência é **experiência e modelo de negócio**, não clone editorial.
