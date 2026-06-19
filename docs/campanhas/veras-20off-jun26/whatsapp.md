# WhatsApp — Veras Pro 20% OFF · ICP Arquitetura · Jun/26

**Campanha:** Veras Pro 20% OFF
**Janela:** 11 → 30/06/2026
**ICP:** Arquitetura (arquitetos, escritórios, designers de interiores, urbanistas)
**Variáveis:** `{{nome}}` · `{{vendedor}}` · `{{cad}}` · `{{link_lp}}`

> `{{cad}}` = plataforma do contato no CRM (ex.: SketchUp, Revit, Rhino). Usar "seu CAD" se desconhecido.

> ⚠️ **Valores comerciais:** Desconto de 20%, créditos grátis (3.000 + 2.000) e prazo (30/jun) são desta janela específica. Sempre confirmar com o brief antes de disparar — não reutilizar de campanhas anteriores.

---

## Mensagem 1 · Reforço (meio da campanha)

**Quando enviar:** 18/jun · Horário comercial 9h–18h

```
{{nome}}, já usa IA no seu fluxo de projeto no {{cad}}?

A Chaos liberou 20% OFF no Veras Pro até 30/jun — IA que respeita seu projeto.

Pela TotalCAD inclui:
✅ 20% OFF no Veras Pro (anual)
✅ Créditos grátis para +300 renders em alta
✅ Suporte técnico nacional Premium
✅ Parcelamento boleto ou cartão
✅ NF e regularização da licença

Quer ver? {{link_lp}}
```

---

## Mensagem 2 · Last call

**Quando enviar:** 29/jun · Horário comercial 9h–18h

```
{{nome}}, a condição do Veras encerra amanhã (30/jun).

20% OFF + 3.000 créditos + 2.000 créditos grátis nessa oferta. Depois dessa janela, o desconto não está reprogramado.

Se quiser plantar a IA no seu fluxo de conceito ainda neste mês, é por aqui:
{{link_lp}}

Quer que eu garanta a condição pra você antes de fechar? É só me responder.
```

---

## Notas de execução

- **CTA único por mensagem:** link da LP de arquitetura via `{{link_lp}}`
- **Tom:** consultor de confiança, conversacional, escaneável. Frases curtas.
- **Sem preço** em R$/US$ — só desconto, créditos e prazo (regra Platinum Partner Chaos)
- **LGPD — opt-out:** rodapé padrão na 1ª mensagem: *"Para não receber mais mensagens da TotalCAD, responda SAIR."*
- Verificar `is_opted_out(identifier, 'whatsapp')` antes de incluir o contato
- Se cliente responder → pausar sequência e atribuir ao vendedor imediatamente
