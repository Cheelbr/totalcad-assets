# Template de Brief — Campanha TotalCAD

> Use este template para briefar o Claude (ou qualquer criativo) antes de criar uma nova campanha.
> Preencha TODOS os campos abaixo. O Claude não consulta campanhas anteriores para valores comerciais.

---

## ⚠️ REGRA CRÍTICA — LEIA ANTES DE CONTINUAR

**NUNCA reutilize valores comerciais de campanhas anteriores.**

Os campos abaixo DEVEM ser fornecidos frescos em cada novo brief:

- `% de desconto` — sempre muda
- `Condições de parcelamento` — sempre muda
- `Preço cheio e preço com desconto` — sempre muda
- `Validade da oferta` — sempre muda
- `Bônus e gifts incluídos` — sempre muda

O Claude **não memoriza preços**. Se estes campos vierem em branco, o Claude vai perguntar antes de escrever qualquer peça.

---

## 1. Identificação

| Campo | Valor |
|---|---|
| **Slug da campanha** | `produto-descricao-mmAA` (ex: `chaos-25off-mai26`) |
| **Produto(s)** | |
| **Janela promocional** | DD/MM/AAAA → DD/MM/AAAA |
| **Audiências** | (lista de pipelines ou segmentos) |
| **Responsável comercial** | |
| **Responsável de marketing** | |

---

## 2. Oferta comercial (preencher SEMPRE — nunca reaproveitar)

| Campo | Valor |
|---|---|
| **Desconto (%)** | _obrigatório_ |
| **Preço cheio (R$)** | _obrigatório_ |
| **Preço com desconto (R$)** | _obrigatório_ |
| **Parcelamento** | ex: 10x sem juros |
| **Validade** | DD/MM/AAAA |
| **Bônus / gifts** | ex: Veras AI grátis por 1 ano |
| **Condições especiais** | ex: válido só via proposta TotalCAD, não no site |

---

## 3. Produto

### O que está incluso
- 

### O que NÃO está incluso (importante para o vendedor não prometer)
- 

### Limitações técnicas relevantes
- 

### SKUs relacionados (upgrades, alternativas)
| SKU | Diferença |
|---|---|
| | |

---

## 4. Audiências

### Audiência 1 — [nome]

| Campo | Valor |
|---|---|
| **Pipeline / segmento CRM** | |
| **Dores principais** | |
| **Sinais de fit (quando esse lead é o certo)** | |
| **Canal preferencial** | Email / WhatsApp / Ligação |

### Audiência 2 — [nome]

| Campo | Valor |
|---|---|
| **Pipeline / segmento CRM** | |
| **Dores principais** | |
| **Sinais de fit** | |
| **Canal preferencial** | |

---

## 5. Conceito da campanha

| Campo | Valor |
|---|---|
| **Slogan / tema central** | |
| **Tom da comunicação** | ex: urgência + autoridade / próximo + consultivo |
| **O que NÃO falar** | ex: não citar preço por escrito antes de qualificar |
| **Concorrente alvo implícito** | ex: IAs genéricas (Freepik, Midjourney) |

---

## 6. Cases e provas sociais disponíveis

- 

---

## 7. Peças solicitadas

- [ ] Playbook (roteiro de vendas para o time comercial)
- [ ] Email E1 — [audiência] (abertura)
- [ ] Email E2 — [audiência] (last call)
- [ ] WhatsApp WA1 — [audiência] (quebra-gelo pós-email)
- [ ] WhatsApp WA2 — [audiência] (fechamento escassez)
- [ ] Landing Page — [audiência]
- [ ] Stories Instagram (3 frames)
- [ ] Carrossel Instagram (6 slides)
- [ ] Outro: ___

---

## 8. Integrações técnicas (Bitrix)

| Campo | Valor |
|---|---|
| **Pipeline ID Bitrix** | (preencher com ID do CEO) |
| **Variáveis de merge** | ex: `{nome}`, `{vendedor}`, `{dias_restantes}`, `{plano_atual}` |
| **Gatilho de disparo WA** | ex: open_email = true, D+1 |
| **Regra de pausa** | ex: se responder → pausar e atribuir ao SDR |
| **Janela de envio** | ex: 10h–18h BRT |

---

## 9. Links e recursos

| Recurso | URL / caminho |
|---|---|
| Landing Page (produção) | |
| Tabela de preços interna | vault `produtos/...` |
| Assets visuais | |
| Aprovação de co-branding necessária? | Sim / Não — [parceiro] |

---

## 10. Checklist antes de enviar ao Claude

- [ ] Desconto % preenchido
- [ ] Preço cheio e com desconto preenchidos
- [ ] Parcelamento preenchido
- [ ] Validade preenchida
- [ ] Audiências descritas com dores e sinais de fit
- [ ] O que NÃO prometer está listado
- [ ] Peças solicitadas marcadas
