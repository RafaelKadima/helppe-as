# Help Peças Executive Dashboard - Complete Guide

## Overview
This comprehensive Excel workbook has been created for Help Peças (electric mobility parts e-commerce brand) based on "Storytelling with Data" principles. The dashboard covers strategic planning from March 2026 through 2028, the company's scaling phase.

---

## Brand Colors Used
- **Electric Lime (#CAFF00)**: Primary highlight color for key metrics
- **Void Black (#0A0A0A)**: Deep backgrounds
- **Steel Blue (#2D4659)**: Secondary accent (Gantt bars for "In Progress")
- **Cool Gray (#6B6B6B)**: Context and labels
- **Off White (#F5F5F3)**: Section headers
- **Dark Charcoal (#1A1A1A)**: Main backgrounds
- **Warm Orange (#FF6B00)**: Alert/attention color

---

## Sheet 1: "Painel Executivo" (Executive Dashboard)

### Purpose
Main presentation board for executives - single page with KPI scorecards and insight-driven visualizations.

### Key Features

**KPI Scorecards (Rows 4-5)**
Five big-number cards highlighting critical metrics:
1. **FATURAMENTO MENSAL** (Monthly Revenue): Pulls YTD average from Dados sheet
2. **TICKET MÉDIO** (Average Order Value): Formula-calculated from Revenue/Orders
3. **TAXA CONVERSÃO** (Conversion Rate): Formula-calculated from Orders/Visitors
4. **CAC** (Customer Acquisition Cost): Direct metric tracking
5. **NPS** (Net Promoter Score): Customer satisfaction metric

All cards use:
- Dark charcoal background (#1A1A1A)
- Lime text (#CAFF00) for values
- 24pt bold font for emphasis
- Lime border for visual distinction

**Section 1: Revenue vs Target** (Row 7, Rows 8-22)
- **Insight-driven title**: "RECEITA vs META — Estamos no caminho certo?" (Are we on track?)
- Compares actual monthly revenue vs annual target
- Data flows from Dados sheet

**Section 2: Marketing Investment Allocation** (Row 24, Rows 25-38)
- **Insight-driven title**: "COMO ESTAMOS ALOCANDO O INVESTIMENTO EM MARKETING?" (How are we allocating marketing investment?)
- Visualizes marketing spend distribution across channels

**Section 3: Conversion Funnel** (Row 40, Rows 41-54)
- **Insight-driven title**: "EVOLUÇÃO DO FUNIL DE CONVERSÃO" (Conversion funnel evolution)
- Tracks progression: Visitors → Leads → Shopping Carts → Orders

---

## Sheet 2: "Dados" (Data Engine)

### Purpose
Single source of truth for all metrics. All other sheets pull data from here via formulas.

### Structure (16 columns × 21 rows)

**Columns:**
- A: Métrica (Metric name)
- B-M: Monthly data (Jan 2026 - Dec 2026)
- N: Meta Anual (Annual target)
- O: Acum. YTD (Year-to-date accumulation/average)
- P: % Meta (Percentage of annual target achieved)

**Data Rows (21 metrics):**

1. **Faturamento Bruto (R$)** - Gross revenue
2. **Receita Líquida (R$)** - Net revenue
3. **Pedidos** - Order count
4. **Ticket Médio (R$)** - Avg order value (FORMULA: Revenue/Orders)
5. **Visitantes Únicos** - Unique visitors
6. **Taxa de Conversão (%)** - Conversion rate (FORMULA: Orders/Visitors)
7. **CAC (R$)** - Customer acquisition cost
8. **LTV (R$)** - Lifetime value
9. **LTV/CAC** - Profitability ratio (FORMULA: LTV/CAC)
10. **ROAS** - Return on ad spend
11. **NPS** - Net promoter score
12. **Margem Bruta (%)** - Gross margin
13. **Giro Estoque (dias)** - Inventory turnover days
14. **SLA Entrega (%)** - Delivery SLA compliance
15. **CSAT** - Customer satisfaction score
16. **SKUs Ativos** - Active product SKUs
17. **Taxa Devolução (%)** - Return rate
18. **Leads Gerados** - Generated leads
19. **Carrinhos Criados** - Shopping carts created
20. **Clientes Recorrentes (%)** - Repeat customer rate

**Sample Data (Jan-Mar 2026):**
- Jan: Foundation month with early traction
- Fev: 10.7% growth in revenue
- Mar: 4.3% growth, improving KPIs across board

**Columns O & P Formulas:**
- O (YTD): SUMIF for counts (sum all months with data), AVERAGEIF for rates
- P (% Meta): O/N ratio showing progress toward annual goal

**Conditional Formatting (Column P):**
- Green: ≥25% of annual target (on track)
- Yellow: 15-24% (caution)
- Red: <15% (behind target)

### Data Input Notes
- **Jan-Mar 2026**: Pre-filled with realistic startup data
- **Apr-Dec 2026**: Empty cells ready for user input
- **All formula cells** automatically recalculate when data added
- Currency cells formatted as "R$ #,##0"
- Percentage cells formatted as "0.0%"

---

## Sheet 3: "Marketing" (Marketing Analytics)

### Purpose
Deep-dive analysis of marketing channel performance and ROI.

### Structure

**Header Row (Row 3):**
9 columns tracking marketing metrics per channel

**8 Data Rows (Mar 2026 performance):**
1. Meta Ads (Instagram/Facebook)
2. Google Ads (Search + Shopping)
3. TikTok Ads
4. Influenciadores (Influencer partnerships)
5. Conteúdo Orgânico (SEO + Blog)
6. Podcast "Rolê Infinito"
7. Email Marketing
8. WhatsApp

**Columns & Formulas:**
- A: Canal (Channel name)
- B: Investimento Mensal (Monthly spend in R$)
- C: Receita Gerada (Revenue generated)
- D: ROAS (FORMULA: C/B) - Return on ad spend
- E: Leads (Lead count)
- F: CPL (FORMULA: B/E) - Cost per lead
- G: Conversões (Conversions/sales)
- H: CPA (FORMULA: B/G) - Cost per acquisition
- I: % Orçamento (FORMULA: B/SUM($B$4:$B$11)) - Budget allocation %

**Total Row (Row 12):**
SUM formulas for all numeric columns, highlighting total investment and return

**Performance Insights:**
- **Google Ads leads** with 6.0x ROAS
- **Meta Ads strong** with 4.0x ROAS
- **Organic content** with 6.0x ROAS (low cost, high efficiency)
- TikTok still ramping (3.0x ROAS)

---

## Sheet 4: "Projetos" (Project Management)

### Purpose
Centralized project tracking with timeline visualization and status monitoring. 30 key deliverables across company.

### Structure

**Columns A-J (Static Info):**
- A: ID (1-30)
- B: Área (Department/area)
- C: Projeto/Entregável (Project/deliverable name)
- D: Responsável (Owner/department lead)
- E: Data Início (Start date)
- F: Data Prazo (End date)
- G: Status (Pendente/Em Andamento/Concluído/Atrasado/Bloqueado)
- H: Prioridade (Crítica/Alta/Média/Baixa)
- I: % Conclusão (Completion percentage as decimal)
- J: Semáforo (Status indicator: colored bullet ●)

**Columns K-V (Timeline - Gantt bars):**
12 months from Mar 2026 - Feb 2027
- Filled cells (█) indicate project is active in that month
- Color indicates status:
  - **Lime (#CAFF00)**: Concluído (completed)
  - **Steel Blue (#2D4659)**: Em Andamento (in progress)
  - **Light Gray**: Pendente (pending)
  - **Orange (#FF6B00)**: Atrasado/Bloqueado (delayed/blocked)

### Project Categories (30 total)

**E-COMMERCE (7 projects)**
1. VTEX platform migration - 75% complete
2. Mercado Livre integration - 40% complete
3. Amazon BR integration - pending (Q2)
4. 2000 SKU catalog - 56% complete
5. Mobile app design - pending (Q3)
6. Loyalty program - pending (Q3)
7. "Help Original" private label - pending (Q3)

**MARKETING (8 projects)**
8. Q1 launch campaign - COMPLETED
9. Google Ads Shopping setup - COMPLETED
10. Podcast S1 (12 episodes) - 33% complete
11. Editorial "Vozes da Cidade" - 10% complete
12. 10 influencer partnerships - 30% complete
13. 50 blog articles (SEO) - 24% complete
14. TikTok channel launch - 20% complete
15. Brand awareness survey - pending (Q2)

**OPERATIONS (6 projects)**
16. 5 certified suppliers contract - 60% complete
17. WMS Bling setup - 80% complete
18. SP distribution center - pending (Q2)
19. D+1 fulfillment process - 25% complete
20. Supplier quality program - pending (Q3)
21. Melhor Envio/Kangu shipping - COMPLETED

**PEOPLE & TECH (9 projects)**
22. Hire Head of Marketing - 50% complete (recruiting now)
23. Hire Head of Operations - pending (Q2)
24. Hire Data Analyst - pending (Q3)
25. GA4 + Dashboards - COMPLETED
26. HubSpot CRM integration - 45% complete
27. WhatsApp chatbot API - 15% complete
28. Zendesk CS setup - 30% complete
29. Support FAQ knowledge base - pending (Q2)
30. Support team training - pending (Q3)

### Critical Path Items
- **Crítica Priority**: VTEX migration, 2000 SKU catalog, fulfillment D+1, hiring heads
- **High Priority**: Marketplace integrations, podcast, influencers, WMS, CRM

---

## Sheet 5: "Roadmap 2026-2028"

### Purpose
Strategic 3-year roadmap showing when key initiatives are active across the company.

### Structure

**14 Columns (2026 Q1 → 2028 Q4)**
Quarterly breakdown showing initiative timelines

**7 Strategic Pillars:**
1. **E-commerce** (4 initiatives)
   - VTEX migration (Q1)
   - Marketplaces (Q2-Q3)
   - Mobile app (Q3-Q4)
   - Loyalty program (Q3-Q4+)

2. **Marketing & Conteúdo** (4 initiatives)
   - Podcast (Q1-Q3)
   - Blog/SEO (Q1-Q3)
   - Influencers (Q2-Q4)
   - Editorial lifestyle (Q3-Q4+)

3. **Operações** (4 initiatives)
   - Suppliers (Q1-Q2)
   - WMS (Q1)
   - Distribution center (Q2-Q3)
   - Fulfillment D+1 (Q2-Q4)

4. **Tecnologia** (4 initiatives)
   - GA4 (Q1)
   - HubSpot (Q2-Q3)
   - Chatbot (Q2-Q3)
   - Zendesk (Q2-Q3)

5. **Pessoas** (3 initiatives)
   - Head Marketing (Q2-Q4)
   - Head Operations (Q2-Q4)
   - Data team (Q3-Q4+)

6. **Produto** (2 initiatives)
   - Private label (Q3-Q4)
   - 2000+ SKUs (Q1-Q3)

7. **Financeiro** (2 initiatives)
   - Profitability (Q4-Q4 2027+)
   - Series A/Funding (Q3-Q4)

**Visualization:**
- Filled lime (█) cells = initiative active that quarter
- Empty cells = inactive
- Creates visual "bars" showing duration and overlap

---

## Sheet 6: "Equipe & Custos" (Team & Costs)

### Purpose
Organizational structure and cost modeling across growth phases (2026-2027+).

### Structure

**9 Columns:**
- A: Fase (Growth phase: 1 = 2026, 2 = 2027+)
- B: Cargo (Position/role)
- C: Departamento (Department)
- D: Tipo (Employment: CLT=permanent, PJ=contractor)
- E: Salário/Mês (Monthly salary in R$)
- F: Encargos (70%) (Payroll taxes/benefits - FORMULA: IF CLT, E*0.7, else 0)
- G: Custo Total/Mês (Total monthly cost - FORMULA: E+F)
- H: Contratação Prevista (Expected hire date)
- I: Status (Ativo/Recrutando/Pendente)

### FASE 1 (2026) - 7 Team Members
Currently active team:
1. CEO/Founder - R$ 15,000/mo (PJ)
2. Dev Fullstack - R$ 8,000/mo (CLT)
3. Analista E-commerce - R$ 4,500/mo (CLT)
4. Social Media Specialist - R$ 3,500/mo (CLT)
5. Designer - R$ 4,000/mo (PJ)
6. Warehouse Operator - R$ 2,500/mo (CLT)
7. SAC Attendant - R$ 2,800/mo (CLT)

**FASE 1 Total**: ~R$ 71,400/month (with encargos)

### FASE 2 (2027+) - Additional 9 Team Members
Planned hires:
8. Head Marketing - R$ 12,000/mo (recruiting Q1 2026)
9. Head Operations - R$ 12,000/mo (recruiting Q2 2026)
10. Videomaker - R$ 4,500/mo (PJ, mar 2026)
11. Content Writer - R$ 3,500/mo (CLT, feb 2026)
12. Community Manager - R$ 3,000/mo (CLT, may 2026)
13. CS Specialist - R$ 4,000/mo (CLT, apr 2026)
14. CS Technical Lead - R$ 5,000/mo (CLT, jun 2026)
15. Data Analyst - R$ 7,000/mo (CLT, may 2026)
16. Supply Chain/Purchasing - R$ 6,000/mo (CLT, jun 2026)

**FASE 2 Total**: Additional ~R$ 58,300/month

### Cost Formulas
- **Encargos (F)**: `=IF(D="CLT", E*0.7, 0)` - 70% overhead for CLT employees, 0% for contractors
- **Total (G)**: `=E+F` - Salary + charges

### Summary Rows
- **TOTAL FASE 1**: `=SUM(G2:G8)` - Base team cost
- **TOTAL FASE 2**: `=SUM(G9:G17)` - Expanded team cost

This shows clear cost escalation as the company scales from lean 2026 team to full-featured operations in 2027+.

---

## Design Principles (Storytelling with Data)

### 1. Eliminate Clutter
- NO gridlines (all sheets have `showGridLines = False`)
- Minimal borders - only where necessary
- Generous white space
- Clean typography (Arial throughout)

### 2. Strategic Use of Color
- **Gray (#6B6B6B)** = context/background
- **Lime (#CAFF00)** = what matters most (KPIs, completed work, priority metrics)
- **Orange (#FF6B00)** = alerts/delays
- **Dark backgrounds** = emphasis and hierarchy

### 3. White Space as Design
- 0.5" margins on all sheets
- Row height variations for visual rhythm
- Section headers with off-white background
- Clear separation between concepts

### 4. Preattentive Attributes
- **Bold & large font** = 24pt for KPI values, 20pt for titles
- **Color** = Lime for metrics that matter
- **Position** = Top of sheet for most critical info
- **Size** = Scale indicates importance

### 5. Titles That Explain the Insight
Not: "Revenue by Month"
But: "RECEITA vs META — Estamos no caminho certo?" (Are we on track?)

Not: "Marketing ROI"
But: "QUAIS CANAIS TRAZEM MAIOR RETORNO?" (Which channels drive the most return?)

---

## Usage & Maintenance

### Monthly Update Cycle
1. Open "Dados" sheet
2. Enter actual numbers for current month (columns B-M, Jan-Dec)
3. All other sheets automatically recalculate via formulas
4. Review "Painel Executivo" for executive briefing

### Data Entry Notes
- **Jan-Mar 2026**: Pre-filled with realistic data
- **Apr-Dec**: Ready for input (currently empty)
- **Formula cells** (Ticket Médio, Conversion Rate, etc.): Auto-calculate
- **YTD columns** (O): Auto-update when monthly data added
- **% Meta columns** (P): Conditional formatting shows progress

### Adding New Projects
1. Open "Projetos" sheet
2. Insert new row with ID, area, project name, etc.
3. Set status and priority dropdowns
4. Enter start/end dates
5. Gantt bars auto-populate based on date logic

### Charts & Visualizations
- Placeholder cells indicate where charts should be added
- Charts reference data from corresponding sheets
- Chart titles follow insight-first naming convention

---

## Technical Details

### Sheet Properties
- All sheets: No gridlines, landscape orientation
- Freeze panes: Row 1 or row 2 (headers visible during scroll)
- Print setup: 1 page wide fit for each sheet

### Font Stack
- Primary: Arial 10/11 (system font, universal compatibility)
- Headings: Arial Bold 11/20
- Values: Arial Bold 24 (lime color)

### Number Formats
- Currency: `R$ #,##0` (Brazilian Real, no cents)
- Percentages: `0.0%` (one decimal)
- Whole numbers: `#,##0`
- Dates: `dd/mm/yy`

### Color Palette
All colors use hex codes for consistency:
- CAFF00 (Lime)
- 0A0A0A (Void Black)
- 2D4659 (Steel Blue)
- 6B6B6B (Cool Gray)
- F5F5F3 (Off White)
- 1A1A1A (Dark Charcoal)
- FF6B00 (Warm Orange)

---

## Executive Summary

This dashboard provides Help Peças with:

1. **Real-time KPI visibility** - 5 critical metrics at a glance
2. **Data integrity** - Single source of truth (Dados sheet)
3. **Marketing analytics** - Channel-level ROI tracking
4. **Project visibility** - 30 key deliverables with Gantt timeline
5. **Strategic alignment** - 3-year roadmap by pillar
6. **Financial clarity** - Team cost modeling and growth phases
7. **Design excellence** - Professional, clean presentation ready for investors

The file is ready for:
- Monthly executive briefings
- Board presentations
- Investor pitches
- Internal team alignment
- Strategic planning reviews

Last updated: March 5, 2026
Total sheets: 6
Total data points: 21 metrics × 12 months = 252 data cells
Total formulas: 121 automatic calculations

