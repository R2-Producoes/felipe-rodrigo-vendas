# Felipe & Rodrigo — Contexto Completo para Página de Vendas
> Produção: R2 Entretenimento | Documento de referência para criação de copy, design e estratégia

---

## 1. Quem São

Felipe & Rodrigo são uma dupla sertaneja da nova geração, formada por dois compositores que já escreviam hits para grandes nomes antes de se tornarem artistas. Antes de subir aos palcos, eram os compositores por trás de sucessos de **Henrique & Juliano**, **Gusttavo Lima** e **Luan Santana**.

A consolidação como dupla veio com **"Gosta de Rua"**: Top 1 nas plataformas digitais, indicada ao **Prêmio Multishow** e eleita a **música mais tocada do Brasil em 2024**.

---

## 2. Números (Stats Atualizados)

| Métrica | Valor |
|--------|-------|
| Streams totais | **+2 BI** |
| Posição Spotify Brasil | **TOP 1** |
| Views no YouTube | **+1 BI** |
| Ouvintes mensais no Spotify | **9,2 MI** |

---

## 3. Hits Principais

| Música | Streams | Destaque |
|--------|---------|----------|
| Gosta de Rua | +308 mi | Mais tocada do Brasil em 2024 · Prêmio Multishow · Top 1 |
| Caos de Alguém | +125 mi | — |
| Ignora | +110 mi | — |

**Spotify Artist ID:** `7gZu6kPnY9enEi5FvgTO4F`

**Spotify Track IDs:**
- Gosta de Rua: `1cIS13bqNfZcTs8LSK8r0a`
- Caos de Alguém: `6zxthXT7GUBX83vRmQiN3x`
- Ignora: `7dNXSf4lS30n1lBfFavQK5`

---

## 4. Discografia / Projetos Audiovisuais

| Projeto | Ano | Streams | Destaque |
|---------|-----|---------|----------|
| No Sentimento | 2022/2023 | +360 mi | — |
| Questão de Tempo | 2024 | +728 mi | Inclui "Gosta de Rua" |
| Nossa Cara | 2025 | +301 mi | Top 5 Spotify |
| Velhos Hábitos | 2025/2026 | +243 mi | #4 álbum mais ouvido no Spotify · Gravado no Brasil e em Nashville (EUA), berço do country |

**Capas disponíveis em:** `assets/images/` (ver arquivos CAPA_*.png — precisam ser adicionadas se necessário)

---

## 5. Evento — DVD "No Sentimento em Brasília"

| Item | Detalhe |
|------|---------|
| Nome do evento | DVD No Sentimento em Brasília |
| Data | **26 de setembro de 2026** |
| Local | **Na Praia Parque — Brasília/DF** |
| Produção | R2 Entretenimento |
| CTA principal | "Quero receber o link exclusivo de pré-venda" |

---

## 6. Identidade Visual

### Paleta de Cores
| Token | Hex | Uso |
|-------|-----|-----|
| Background | `#0d0606` | Fundo geral (vinho-escuro quase preto) |
| Primary | `#e11d2a` | Vermelho da marca — CTAs, destaques, glow |
| Wine | `#5a0e14` | Superfícies médias, bordas |
| Wine Dark | `#3b0a0e` | Fundos de seção |
| Card | `#140909` | Cards, formulário |
| Foreground | `#f5f0ee` | Texto principal |
| Muted FG | `#b8a8a8` | Texto secundário |

### Gradientes
```
Hero:     linear-gradient(165deg, #5a0e14 0%, #240608 48%, #0d0606 100%)
Wine:     linear-gradient(180deg, #3b0a0e 0%, #0d0606 100%)
Wine Rev: linear-gradient(180deg, #0d0606 0%, #3b0a0e 100%)
Primary:  linear-gradient(135deg, #e11d2a 0%, #8a0f17 100%)
```

### Tipografia
- **Título/Poster:** Anton (uppercase, line-height 0.92)
- **Corpo:** Inter
- **Label de seção:** `text-sm font-bold uppercase tracking-[0.2em] text-primary`

### Sombras
```
Card:  0 20px 60px -20px rgba(0,0,0,0.8)
Glow:  0 0 48px rgba(225,29,42,0.35)
Text:  0 0 24px rgba(225,29,42,0.55)
```

---

## 7. Assets Disponíveis

### Imagens (`assets/images/`)

| Arquivo | Descrição | Uso sugerido |
|---------|-----------|-------------|
| `foto-dupla.png` | Foto dos dois artistas no palco/show, fundo escuro | Hero desktop |
| `foto-dupla-mobile.jpg` | Retrato dos dois artistas (portrait, fundo claro/composite) | Hero mobile — sem corte, rostos visíveis |
| `felioe_rodrigo_png.png` | Foto dupla, enquadramento mais fechado | Seção "Quem são eles" / About |
| `felipe-rodrigo-hero.png` | Foto alternativa hero | Backup / variação de hero |
| `LOGO_FER_BRANCO.png` | Logo oficial Felipe & Rodrigo (branco) | Header, footer, watermarks |
| `FOTOS_-_DVD_Velhos_Habitos__15_.png` | Show ao vivo — DVD Velhos Hábitos | Galeria |
| `FOTOS_-_DVD_Velhos_Habitos__28_.png` | Palco — DVD Velhos Hábitos | Galeria |
| `FOTOS_-_DVD_Velhos_Habitos__32_.png` | Bastidores — DVD Velhos Hábitos | Galeria |
| `FOTOS_-_DVD_Velhos_Habitos__33_.png` | Cena do DVD | Galeria |
| `FOTOS_-_DVD_Velhos_Habitos__34_.png` | Cena do DVD | Galeria |
| `FOTOS_-_DVD_Velhos_Habitos__36_.png` | Gravação DVD | Galeria |
| `FOTOS_-_DVD_Velhos_Habitos__50_.png` | Performance | Galeria |
| `FOTOS_-_DVD_Velhos_Habitos__60_.png` | DVD ao vivo | Galeria |
| `FOTOS_-_DVD_Velhos_Habitos__63_.png` | Cena do DVD | Galeria |

### Documentos (`assets/docs/`)

| Arquivo | Descrição |
|---------|-----------|
| `Felipe & Rodrigo _ Meta Ads _ Pixel de Acompanhamento de Conversões.pdf` | Pixel Meta Ads — ID `1201585150507432` |

---

## 8. Infraestrutura Técnica (LP Atual)

| Item | Valor |
|------|-------|
| Stack | TanStack Start + React 19 + Vite + Tailwind CSS v4 + TypeScript |
| Deploy | Vercel (team: R2-Producoes) |
| Domínio | `felipe-rodrigo.r2.com.vc` |
| Repo GitHub | `R2-Producoes/felipe-rodrigo-lp` |
| Webhook leads (n8n) | `https://n8n-editor.r2.konnhub.com/webhook/16b559ef-81df-43f0-9ea7-eff48fa898da` |
| Meta Pixel ID | `1201585150507432` |

### Formulário de Lead (campos coletados)
- Nome completo *(obrigatório)*
- WhatsApp / Telefone *(obrigatório)*
- E-mail *(obrigatório)*
- CPF *(opcional)*
- Cidade / Estado *(opcional)*

---

## 9. Copy Referência (LP Atual)

### Hero
```
DVD No Sentimento em Brasília
Felipe & Rodrigo
Na Praia Parque
26/09/2026
[CTA] Quero receber o link exclusivo de pré-venda
[CTA secundário] Ouvir os Hits
```

### Seção "Quem são eles"
```
Os hits já eram deles antes mesmo do palco

Felipe & Rodrigo estão entre os maiores nomes da nova geração do sertanejo.
Antes de subir aos palcos, já eram compositores por trás de hits de
Henrique & Juliano, Gusttavo Lima e Luan Santana.

A consolidação veio com "Gosta de Rua": Top 1 das plataformas, indicada
ao Prêmio Multishow e a música mais tocada do Brasil em 2024.
```

### Seção de Hits
```
A trilha que você já canta
As músicas que você já conhece

Aperte o play. Essas são as músicas que tocam em todo lugar — e todas são de Felipe & Rodrigo.
```

### Formulário
```
Garanta sua participação
Cadastre-se para o DVD No Sentimento

Preencha o formulário e garanta seu cadastro para participar da gravação do
DVD No Sentimento em Brasília de Felipe & Rodrigo — 26/09/2026 · Na Praia Parque.

[botão] Quero receber o link exclusivo de pré-venda

[sucesso] Cadastro realizado!
Em breve você recebe informações sobre sua participação no DVD No Sentimento em Brasília.
```

---

## 10. Estrutura de Seções da LP Atual (ordem)

1. **Header** — Logo + nav (Hits, A Dupla, CTA)
2. **Hero** — Foto de fundo + título do evento + CTAs
3. **Stats** — +2 BI streams · TOP 1 Spotify · +1 BI views YouTube · 9,2 MI ouvintes
4. **About** — Quem são, biografia, foto
5. **Hits** — Player Spotify embed (artista + 3 hits)
6. **Projects** — 4 projetos/DVDs com capa e stats
7. **Gallery** — 6 fotos do DVD Velhos Hábitos
8. **ContactForm** — Formulário de lead
9. **Footer** — Logo

---

*Documento gerado em 2026-06-30 por R2 Entretenimento para uso interno.*
