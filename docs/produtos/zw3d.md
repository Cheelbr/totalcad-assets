# ZW3D — Base de Produto

> Fonte: material ZWSOFT MFG Solution GTM · Jun/26
> Arquivo em construção — adicionar mais informações conforme material for recebido.

---

## O que é

ZW3D é a plataforma integrada de CAD/CAM 3D da ZWSOFT para manufatura. Diferente do ZWCAD MFG (foco em documentação técnica 2D), o ZW3D cobre o ciclo completo de desenvolvimento de produto: modelagem 3D, simulação, usinagem e gestão de dados.

**Posicionamento:** "Model-based CAx Integrated R&D Management Platform"

---

## Hierarquia de SKUs

| SKU | Conteúdo principal |
|-----|-------------------|
| **ZW3D Lite** | 2D&3D Sketch · Solid Modeling · Surface Modeling · Direct Edit · Assembly · Drawing Sheet · Data Translator · PMI |
| **ZW3D Standard** | Lite + Weld · Sheet Metal · Structure · Point Cloud · Simulation · Piping/Tubing · Harness · ECAD · Assembly Simulation · Motion |
| **ZW3D Professional** | Standard + Mold · Electrode · Drill · Turning · 2X Mill · 3X Mill · CAM Simulation · Assembly Simulation |
| **ZW3D Premium** | Professional + 4-5X Mill · High-speed Roughing · Machine Simulation · MotorWizard · Structural · Metas · e mais |

### Módulos adicionais disponíveis
PARTsolutions · JT · Translator_2D · Keyshot · ZWTeammate · 4-5X Mill · Volumill · Machine Simulation · Structural · Metas · MotorWizard

### Serviços de conversão
Creo Conversion · SolidWorks Conversion

---

## Para quem é

### Foco principal
**Maquinário & Equipamentos** (General & Specialized Machinery Equipment)

### Segmentos secundários
Injection Mold · Household Appliance · Consumer Electronics

### Range ótimo de performance
- Componentes até **50K** (eficiência plena até 5K, design fluido até 20K)
- Features entre **100–500** com poucos fillets e draft features
- Superfícies com requisitos **G0–G2** (não G3/Class-A)
- Módulos de indústria: Sheet Metal · Steel Structure · Molds · Piping · Harness

### Fora do range ideal
- Componentes >100K (aeronáutica, naval, automotivo pesado)
- Peças fundidas estruturalmente complexas (history steps >1K)
- Superfícies G3/Class-A (aviação, carroceria automotiva)

---

## Mercados-alvo detalhados

| Segmento | Subsetores |
|----------|------------|
| **Robôs Industriais, Máquinas-Ferramenta e Impressoras 3D** | Machine Tools · Industrial Robots · Industrial 3D Printers · AGVs |
| **Maquinário de Manufatura Especializado** | Automated Manufacturing Machinery · Conveyors · IE Engineering Services · Vending Machines |
| **Maquinário Pesado Móvel** | Agricultural Machinery · Construction & Mining Machinery · Industrial Trucks · Overhead Cranes |
| **Equipamentos de Pressão** | Boiler Equipment · Pressure Vessel · Dust Removal · Desulfurization Equipment |
| **Energia e Fluidos** | Electric Motors · Fluid Equipment · Oil & Gas · Heating and Cooling · Bearings |
| **Moldes** | Metal Parts · Sheet Metal · Cutting Tools · Molds and Dies · Plastic Products |

---

## Valor central (Core Value)

- Conecta todo o processo de desenvolvimento de produto baseado em modelos 3D
- Sistema de gestão de dados de produto profundamente integrado para customização e inovação
- Incorpora IA para padronização, parametrização, serialização e modularização

**Propósito:** Drive digital transformation in product development. Enable a future-ready information management system.

---

## Prioridades de R&D (diferenciais técnicos)

- **Proven & Standard:** produto e plataforma altamente padronizados e modulares
- **Openness:** API e SDK para desenvolvimento secundário
- **Platform Approach:** soluções CAx digitais integradas em plataforma

---

## ZWTeammate (módulo PLM/PDM integrado)

Produto complementar ao ZW3D para gestão de produto:

| Pilar | Funcionalidades |
|-------|----------------|
| **Data Integrity** | Gestão de documentos, desenhos e specs ao longo do desenvolvimento · Controle de versão com rastreamento de mudanças |
| **Co-design** | CAD integration no ZW3D · Online sharing de dados 3D em tempo real · Comunicação via issues e emails |
| **Design Reuse & Knowledge Management** | Reutilização de designs maduros e peças padrão · Base de conhecimento centralizada da equipe |

Fluxo: Create Design Team → Planning → Create & Submit Design → Evaluate → Data Release (EC Released Vault)

---

## Cases de sucesso

### Case 1 — Taiyuan Boiler Group
**Objetivo:** transição de 2D para design 3D digital completo
**Duração da parceria:** 3 anos com ZWSOFT

**Desafios:**
- Alta maturidade do mercado, concorrência intensa e margens baixas — necessidade de inovar
- Sistema de design dependia de ferramentas 2D; precisavam migrar para 3D completo
- Grande volume de desenhos com processo de revisão 2D ineficiente e sujeito a erros
- Gestão de dados rudimentar com silos de informação
- Falta de acumulação estruturada de experiência e conhecimento

**Solução implantada (ZW3D + ZWTeammate):**
- Concept Design: Model Iteration com SolidWorks & Creo → ZW3D
- Detailed Design: Structural Design (sistema paramétrico + bibliotecas padrão) · Steel Structure · Assembly Design · Piping & Harness
- Simulation: estrutural e fluido
- Manufacturing: usinagem 2-5 eixos
- Gestão: ZWTeammate como PLM/PDM · ZW Cloud para revisão e aprovação colaborativa

**Resultados:**
- Padrões de design unificados com templates de peças, atributos e desenhos
- Biblioteca de peças padrão corporativa: juntas, abraçadeiras, espaçadores, componentes de suspensão
- Geração automática de desenhos de engenharia (projeção, anotação e tabelas em batch)
- Modelagem e montagem automáticas: engenheiro informa parâmetros principais → sistema gera

---

### Case 2 — Welltec Machinery
**Objetivo:** transformação digital para acelerar inovação de produto
**Produto:** maquinário de injeção (injection molding machines)

**Desafios:**
- Ciclos de entrega curtos com tempo de design e produção apertado
- Múltiplas séries de produto com muitos designs repetitivos
- Arquivos digitais copiados manualmente entre processos
- Padrões de design inconsistentes entre equipes
- Dificuldade de manter continuidade de dados históricos

**Resultados mensuráveis:**

| Tipo de desenho | Método | Antes | Depois |
|-----------------|--------|-------|--------|
| Header (150 peças) + geração de desenho | 2D Drawing | 5–10 dias | — |
| Header (150 peças) + geração de desenho | 3D Design | 3–5 dias | — |
| Header (150 peças) + geração de desenho | Custom Dev Tools | — | **0,5–1 dia** |
| Membrane wall (50 peças) + geração de desenho | 2D Drawing | 1–2 dias | — |
| Membrane wall (50 peças) + geração de desenho | Custom Dev Tools | — | **0,5 dia** |

**Indicadores de resultado:**
- **+200%** de eficiência em componentes core (drum, header, serpentine tube, membrane wall, heat exchanger)
- **+60%** de eficiência geral de projeto
- **+400%** de eficiência de novos funcionários
- Eliminação de silos de dados entre softwares
- Gestão de dados ao longo de todo o ciclo de vida
- Geração de montagens e desenhos com um clique

---

## O que NÃO está incluso / Limitações

- Para documentação técnica 2D de manufatura: ver **ZWCAD MFG** (produto complementar)
- Performance reduzida em projetos com >100K componentes
- Não indicado para superfícies G3/Class-A (aeronáutica, carroceria automotiva)
- Preços **sob consulta** — nunca publicar valores sem brief atualizado

---

## Concorrentes

- SolidWorks (Dassault Systèmes) — principal referência de mercado
- Creo (PTC)
- Inventor (Autodesk)
- Ponto de venda ZW3D: licença perpétua + CAD+CAM integrado em um único produto

---

## Tags para campanhas

`manufatura` `CAD-3D` `CAM` `simulação` `moldes` `maquinário` `migração-SolidWorks` `migração-AutoCAD-Mechanical` `PLM` `ZWTeammate` `licenca-perpetua` `digital-transformation`
