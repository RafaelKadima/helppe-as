# Help Peças E-Commerce - Tracking Spreadsheet Guide

## File Location
```
/sessions/wizardly-laughing-euler/mnt/outputs/help-pecas-tracker.xlsx
```

## Brand Identity
- **Electric Lime:** #CAFF00 - Primary accent color for headers
- **Void Black:** #0A0A0A - Dark backgrounds
- **Steel Blue:** #2D4659 - Strategic planning sheets
- **Warm Orange:** #FF6B00 - Project tracking
- **Light Gray:** #F5F5F3 - Alternating row colors

## Sheet Overview

### 1. Dashboard KPIs (Tab Color: Electric Lime)
**Purpose:** Monthly KPI tracking for 2025

**Structure:**
- **Row 1:** Headers with black background (#0A0A0A) and lime text (#CAFF00)
- **Columns A-P:**
  - A: KPI Name
  - B-M: Monthly values (Jan-Dec 2025)
  - N: Meta Anual (annual target in blue text)
  - O: Realizado (calculated average of B:M)
  - P: % Atingido (formula: O/N with conditional formatting)

**18 KPIs Tracked:**
1. Faturamento Bruto (R$) - Target: 1,200,000
2. Receita Líquida (R$) - Target: 1,020,000
3. Ticket Médio (R$) - Target: 200
4. Pedidos/Mês - Target: 500
5. Visitantes Únicos/Mês - Target: 33,333
6. Taxa de Conversão (%) - Target: 0.015
7. CAC (R$) - Target: 80
8. LTV (R$) - Target: 600
9. LTV/CAC - Target: 0 (calculated)
10. ROAS - Target: 4
11. NPS - Target: 50
12. Taxa de Recompra (%) - Target: 0.15
13. Margem Bruta (%) - Target: 0.35
14. Giro de Estoque (dias) - Target: 30
15. SLA Entrega (% no prazo) - Target: 0.95
16. CSAT (1-5) - Target: 4.5
17. SKUs Ativos - Target: 500
18. Taxa de Devolução (%) - Target: 0.03

**Formatting:**
- Currency: R$ #,##0
- Percentage: 0.0%
- Numbers: #,##0
- Conditional Formatting on % Atingido:
  - Green: >=100% (on target)
  - Yellow: 70-99% (at risk)
  - Red: <70% (critical)

---

### 2. Metas 2025-2028 (Tab Color: Steel Blue)
**Purpose:** Multi-year financial projections and strategic planning

**Structure:**
- **Columns A-E:** Metric name, 2025, 2026, 2027, 2028
- **Formatting:** Blue text for input assumptions, black for calculated values

**13 Strategic Metrics:**
1. Faturamento Anual: 1.2M → 6M → 24M → 68M
2. Receita Líquida: 1.02M → 5.1M → 20.16M → 57.8M
3. Margem Bruta %: 35% → 38% → 42% → 45%
4. Lucro Bruto: 420K → 1.9M → 10.08M → 26.01M
5. Equipe: 6.5 → 15 → 30 → 60
6. Custo Folha Estimado: 65K → 150K → 300K → 600K
7. SKUs: 500 → 1,500 → 3,000 → 5,000
8. Clientes/Ano: 6K → 30K → 120K → 340K
9. Ticket Médio: 200 (stable)
10. CAC: 80 → 75 → 70 → 65
11. LTV: 600 → 700 → 800 → 900
12. LTV/CAC: 7.5 → 9.33 → 11.43 → 13.85
13. Market Share %: 0.5% → 2% → 6% → 15%

---

### 3. Entregáveis (Tab Color: Warm Orange)
**Purpose:** Project and deliverable tracking for first 6 months

**Structure:**
- **Columns:**
  - A: Área (Department)
  - B: Entregável (Project name)
  - C: Responsável (Owner)
  - D: Prazo (Deadline)
  - E: Status (Dropdown)
  - F: Prioridade (Dropdown)
  - G: Observações (Notes)

**Status Options:** Pendente, Em Andamento, Concluído, Atrasado
**Priority Options:** Alta, Média, Baixa

**27 Deliverables Across 6 Areas:**

**E-commerce (5):**
- Setup plataforma VTEX
- Integração pagamentos
- Cadastro 500 SKUs
- SEO técnico
- Integração Mercado Livre

**Marketing (6):**
- Setup Meta Ads
- Setup Google Ads
- Criação identidade social
- Lançamento podcast
- Calendário editorial 6 meses
- Parcerias influenciadores

**Operações (5):**
- Contrato fornecedores
- Setup WMS/ERP
- Definição curva ABC
- Processo fulfillment
- Contrato transportadoras

**Tech (4):**
- Setup analytics GA4
- Integração CRM
- Chatbot WhatsApp
- App mobile (design)

**Conteúdo (4):**
- Produção 30 posts iniciais
- Gravação 4 episódios podcast
- Shooting produtos (500 fotos)
- Criação blog

**CS (3):**
- Setup Zendesk
- Treinamento equipe SAC
- Base de conhecimento FAQ

---

### 4. Estrutura Operacional (Tab Color: Dark Gray)
**Purpose:** Organizational structure and hiring plan

**Structure:**
- **Columns:**
  - A: Fase (Phase)
  - B: Cargo (Position)
  - C: Departamento (Department)
  - D: Tipo (Employment type - CLT/PJ/Terceirizado)
  - E: Salário Estimado (R$)
  - F: Prioridade Contratação (Hiring priority)
  - G: Status (Hiring status)

**31 Roles Across 4 Phases:**

**Fase 1 - Lançamento (7 roles):**
- CEO/Founder (CLT) - R$ 5,000
- CTO/Tech Lead (CLT) - R$ 8,000
- E-commerce Manager (CLT) - R$ 5,000
- Operações Manager (CLT) - R$ 4,500
- Social Media Manager (PJ) - R$ 3,000
- Desenvolvedor Backend (PJ) - R$ 6,000
- Desenvolvedor Frontend (PJ) - R$ 5,500

**Fase 2 - Crescimento (8 roles):**
- CFO, Product Manager, SEM Specialist, SEO Specialist, Content Manager, CS Manager, Data Analyst, SAC Agents (2)

**Fase 3 - Expansão (8 roles):**
- VP Marketing, Growth Manager, Gerente Operações, Especialista Estoque, Product Designer, QA Engineer, Content Creator, Fotógrafo

**Fase 4 - Consolidação (8 roles):**
- VP Tech, Gerente Infraestrutura, DevOps Engineer, DBA, VP Operações, Gerente CS, SAC Agents (5), Contabilista

---

### 5. Estoque & Fornecedores (Tab Color: Void Black)
**Purpose:** Inventory management and supplier tracking

**Structure:**
- **Columns:**
  - A: SKU
  - B: Produto (Product)
  - C: Categoria (Category with dropdown)
  - D: Fornecedor (Supplier)
  - E: Custo Unitário (R$)
  - F: Preço Venda (R$)
  - G: Margem % (Formula: (Price-Cost)/Price)
  - H: Estoque Atual (Current stock)
  - I: Estoque Mínimo (Minimum stock)
  - J: Ponto Reposição (Reorder point)
  - K: Status (Formula: REPOR if stock<min, else OK)
  - L: Curva ABC (A/B/C classification)

**7 Product Categories:**
- Paralama
- Bateria
- Motor
- Pneu
- Freio
- Iluminação
- Acessório

**10 Sample Items:**
1. Bateria 48V 20Ah LiFePO4 (SKU001) - Bateria
2. Motor brushless 1000W (SKU002) - Motor
3. Pneu elétrico 8 polegadas (SKU003) - Pneu
4. Freio a disco hidráulico (SKU004) - Freio
5. Farol LED frontal (SKU005) - Iluminação
6. Guidão ajustável (SKU006) - Acessório
7. Paralama protetor (SKU007) - Paralama
8. Corrente de transmissão (SKU008) - Acessório
9. Controlador BLDC 48V (SKU009) - Acessório
10. Cinto de segurança (SKU010) - Acessório

---

## General Formatting

### Typography
- **Headers:** Arial 11pt, Bold, Black background (#0A0A0A), Lime text (#CAFF00)
- **Data rows:** Arial 10pt, alternating white/#F5F5F3 row colors

### Number Formats
- **Currency:** R$ #,##0
- **Percentage:** 0.0%
- **Numbers:** #,##0
- **Ratios:** 0.00

### Layout
- **Freeze Panes:** Row 1 frozen on all sheets for easy scrolling
- **Column Widths:** Auto-adjusted (minimum 12pt)
- **Print Area:** Set on all sheets

---

## How to Use

### Dashboard KPIs
1. Enter monthly values in columns B-M
2. The Realizado column automatically calculates monthly average
3. The % Atingido column shows performance vs. target
4. Use conditional formatting colors to identify issues at a glance

### Metas 2025-2028
1. Review multi-year growth trajectory
2. Update assumptions (blue text) as needed
3. Monitor growth rates and team expansion

### Entregáveis
1. Update status and progress on deliverables
2. Filter by status or priority to focus on current work
3. Use as project management dashboard

### Estrutura Operacional
1. Track hiring priorities and phases
2. Monitor team expansion plan
3. Update salary estimates and hiring status

### Estoque & Fornecedores
1. Monitor inventory levels
2. Margin column helps identify profitability
3. Status column alerts when items need reordering
4. Use ABC curve for inventory optimization

---

## File Size
- **Final size:** ~20 KB (optimized Excel format)
- **Format:** .xlsx (Excel 2007+)
- **Created:** 2025-03-05

---

Generated for Help Peças E-Commerce
Electric Mobility Parts Distribution Platform
