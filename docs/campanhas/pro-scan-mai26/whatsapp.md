# WhatsApp — SketchUp Pro Scan · Maio 2026

**Campanha:** Pro Scan · "Pare de passar a limpo. Comece a projetar."
**Janela:** 12/05 → 31/05/2026
**Variáveis Bitrix:** `{nome}`, `{empresa}`, `{plano_atual}`, `{mes_renovacao}`, `{dias_restantes}`

> ⚠️ **Valores comerciais (% desconto, parcelamento, validade):** não estão fixados nestas mensagens propositalmente. Sempre preencher via merge tag ou briefar o copywriter com os valores da janela atual antes de disparar.

---

## WA1-novos — Quebra-gelo SAAS Novos

**Audiência:** SAAS Novos (arquiteto de reforma/retrofit que ainda passa levantamento a limpo na trena)
**Quando disparar:** D+1 após abertura do E1-novos (gatilho: `open_email = true`)
**Frameworks:** Loss aversion · Cialdini compromisso · Storytelling 3 atos (vilão = trena) · BJ Fogg prompt no momento certo
**Tom:** descontraído, vendedor experiente que já viu essa cena mil vezes — sem acentos (consistência na sequência)

### Mensagens

**Msg 1 (D+1 às 10:00)**
> Oi {nome}, posso te fazer uma pergunta meio chata? Voce ja passou levantamento a limpo de madrugada, com trena e caderneta, e descobriu no dia seguinte que faltou medir um pe-direito?

**Msg 2 (D+1 às 14:00)**
> Te mandei um material que mostra como arquiteto deixa de revisitar obra e passa a modelar direto sobre o real escaneado. Da uma olhada: https://LINK DA LP

**Msg 3 (D+2 às 10:00)**
> Se fizer sentido pro seu fluxo, posso te mostrar em 15min como funciona na pratica. Bate hoje ou amanha?

### Notas de deploy (Bitrix)
- Pipeline: SAAS Novos (ID pendente CEO)
- Disparar apenas para contatos com `opt_in_whatsapp = true` e `is_opted_out = false`
- Variáveis renderizadas via merge tag Bitrix
- Link único na Msg 2 — LP novos
- Janela de envio: 10h–18h BRT
- Se responder em qualquer Msg → pausar sequência e atribuir ao SDR

---

## WA2-novos — Fechamento SAAS Novos (escassez)

**Audiência:** SAAS Novos que receberam WA1 + E2 e ainda não agendaram
**Quando disparar:** D+14 (última semana do desconto)
**Frameworks:** Escassez (Cialdini) · Loss aversion · Hick's Law (1 CTA só) · BJ Fogg habilidade fácil (20min)
**Tom:** direto, sem rodeio — sem acentos (consistência com WA1)

### Mensagens

**Msg 1 (D+14 às 10:00)**
> {nome}, faltam {dias_restantes} dias do desconto no SketchUp Pro Scan. Depois de 31/05 volta o preco cheio.

**Msg 2 (D+15 às 11:00)**
> 20min essa semana pra te mostrar o que muda no seu fluxo? Manda um horario que eu encaixo: https://totalcad.com.br/sketchup-pro-scan

### Notas de deploy (Bitrix)
- Pipeline: SAAS Novos (ID pendente CEO)
- `{dias_restantes}` = cálculo automático (31/05 − data_envio)
- Disparar apenas para leads que **abriram WA1** ou **clicaram E2** e ainda não agendaram
- Link único na Msg 2 — mesma LP de novos (CTA agenda)
- Janela de envio: 10h–17h BRT
- Se não responder até D+18 → sequência encerra, lead volta pra nurture base

---

## WA1-upgrade — Lembrete SAAS Upgrade/Upsell

**Audiência:** Cliente atual SketchUp Pro/Go com renovação chegando
**Quando disparar:** D+1 após abertura do E1-upgrade (gatilho: `open_email = true`)
**Frameworks:** Afinidade (cliente conhecido) · Anchoring por paridade (mesmo orçamento, mais ferramenta) · Curiosidade · Reciprocidade
**Tom:** confidente, cliente conhecido — com acentuação completa (consistência na sequência)

### Mensagens

**Msg 1 (D+1 às 10:00)**
> Oi {nome}, tudo bem? Sua renovação do {plano_atual} está marcada pra {mes_renovacao} — quis te avisar antes da janela do desconto fechar.

**Msg 2 (D+1 às 15:00)**
> Com a promoção, você mantém o investimento que já faz no SketchUp e leva muito mais: a próxima renovação pode incluir o Scan Essentials e te economizar horas por projeto. Mesmo SketchUp que você já usa, agora com a nuvem de pontos dentro.

**Msg 3 (D+2 às 10:00)**
> Dá uma olhada aqui: https://totalcad.com.br/sketchup-pro-scan-upgrade — se fizer sentido, fala com o seu consultor TotalCAD e a gente te mostra as condições.

### Notas de deploy (Bitrix)
- Pipeline: SAAS Upgrade/Upsell (ID pendente CEO)
- `{plano_atual}` = campo CRM (SketchUp Pro / SketchUp Go)
- `{mes_renovacao}` = data de renovação prevista no CRM
- Disparar apenas para clientes com `renovacao_prevista` dentro de 90 dias E `opt_in_whatsapp = true`
- Link único na Msg 3 — LP upgrade dedicada
- Janela de envio: 10h–18h BRT
- Se cliente responder → SDR farmer assume, sequência pausa

---

## WA2-upgrade — Última semana SAAS Upgrade/Upsell

**Audiência:** Cliente atual Pro/Go que recebeu WA1 + E2 e ainda não decidiu upgrade
**Quando disparar:** D+14 (última semana do desconto)
**Frameworks:** Escassez (Cialdini) · Loss aversion · Anchoring por paridade · BJ Fogg habilidade fácil
**Tom:** direto, próximo, sem pressão agressiva — com acentuação completa (consistência com WA1-upgrade)

### Mensagens

**Msg 1 (D+14 às 10:00)**
> {nome}, é a última semana do desconto no Pro Scan. Com a promoção, você mantém o investimento que já faz no {plano_atual} e leva o Scan Essentials junto na próxima renovação — horas economizadas em todo projeto de reforma.

**Msg 2 (D+15 às 11:00)**
> Fala com o seu consultor TotalCAD e veja as condições: https://totalcad.com.br/sketchup-pro-scan-upgrade

### Notas de deploy (Bitrix)
- Pipeline: SAAS Upgrade/Upsell (ID pendente CEO)
- Disparar apenas para quem **abriu WA1-upgrade** ou **clicou E2-upgrade** e ainda não agendou
- Link único na Msg 2 — LP upgrade com âncora pra agenda
- Janela de envio: 10h–17h BRT
- Após encerramento da janela: sequência se encerra automaticamente (escassez expirou)
- Se cliente responde → SDR farmer assume imediatamente (não deixar esfriar na última semana)
