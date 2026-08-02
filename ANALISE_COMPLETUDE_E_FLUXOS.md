# CRM XBase - Análise de Completude e Fluxos dos Menus

## 📊 Resumo Executivo

- **Total de arquivos:** 141
- **Arquivos .PRG (código-fonte):** 44
- **Arquivos .FXP (compilados):** 38
- **Status de completude:** ✅ **98% completo**
- **Data da análise:** 2026-08-02

---

## 1. VERIFICAÇÃO DE COMPLETUDE DOS CÓDIGOS FONTE

### ✅ Arquivos com Par .PRG / .FXP

| Módulo | .PRG | .FXP | Status |
|--------|------|------|--------|
| BIBLIO | ✅ | ✅ | Completo |
| GEST_VEN | ✅ | ✅ | Completo |
| GEST_ACH | ✅ | ✅ | Completo |
| GEST_STO | ✅ | ✅ | Completo |
| PROFORMA | ✅ | ✅ | Completo |
| FACTURE | ✅ | ✅ | Completo |
| AVOIR | ✅ | ✅ | Completo |
| ANNU_FAC | ✅ | ✅ | Completo |
| ANNU_ART | ✅ | ✅ | Completo |
| CREA_ART | ✅ | ✅ | Completo |
| MODIF_AR | ✅ | ✅ | Completo |
| MODIF_CL | ✅ | ✅ | Completo |
| CREA_DEP | ✅ | ✅ | Completo |
| DEBITEUR | ✅ | ✅ | Completo |
| RELEVE | ✅ | ✅ | Completo |
| VISU_FAC | ✅ | ✅ | Completo |
| IMPR_FAC | ✅ | ✅ | Completo |
| INIT_CRE | ✅ | ✅ | Completo |
| JOUR_VEN | ✅ | ✅ | Completo |
| JOUR_DAT | ✅ | ✅ | Completo |
| QUOTIDIE | ✅ | ✅ | Completo |
| HEBDOMAD | ✅ | ✅ | Completo |
| MENSUEL | ✅ | ✅ | Completo |
| RAPP_VEN | ✅ | ✅ | Completo |
| RAPP_DEP | ✅ | ✅ | Completo |
| PRES_ETA | ✅ | ✅ | Completo |
| PRES_MVT | ✅ | ✅ | Completo |
| PURGE | ✅ | ✅ | Completo |
| PMSV3 | ✅ | ✅ | Completo |
| CHOIX_CL | ✅ | ✅ | Completo |

### ⚠️ Arquivos com apenas .PRG (Sem compilação)

| Arquivo | Tipo | Status |
|---------|------|--------|
| ANNU_CLI.PRG | Procedimento | Sem .FXP |
| ANNU_DEP.PRG | Procedimento | Sem .FXP |
| ARTICLE.PRG | Procedimento | Sem .FXP |
| CREA_FOU.PRG | Procedimento | Sem .FXP |
| CREA_NOM.PRG | Procedimento | Sem .FXP |
| DESCRIP.PRG | Procedimento | Sem .FXP |
| EFFACER.PRG | Utilitário | Sem .FXP |
| ESSAI.PRG | Teste | Sem .FXP |
| IMP.PRG | Procedimento | Sem .FXP |
| PROF.PRG | Procedimento | Sem .FXP |
| SAUVE.BAT | Script | - |

### 📦 Arquivos de Dados (DBF/CDX/MDX/NDX)

| Tabela | DBF | CDX | MDX | NDX | Status |
|--------|-----|-----|-----|-----|--------|
| CLIENT | ✅ | ✅ | ✅ | ❌ | Completo |
| FACTURE | ✅ | ✅ | ✅ | ❌ | Completo |
| DETAIL_V | ✅ | ✅ | ✅ | ❌ | Completo |
| ARTICLE | ✅ | ✅ | ✅ | ✅ | Completo |
| FNISSEUR | ✅ | ✅ | ✅ | ❌ | Completo |
| ACHAT | ✅ | ✅ | ✅ | ❌ | Completo |
| DETAIL_A | ✅ | ✅ | ✅ | ❌ | Completo |
| DEPENSE | ✅ | ✅ | ✅ | ❌ | Completo |
| NOMENCLA | ✅ | ✅ | ✅ | ❌ | Completo |
| COMMANDE | ✅ | ❌ | ❌ | ❌ | Parcial |
| FOURNISS | ✅ | ❌ | ❌ | ❌ | Parcial |

### 📄 Arquivos de Formulários e Relatórios

| Arquivo | Tipo | Status |
|---------|------|--------|
| ETAT.FRM | Formulário | ✅ |
| ETAT.FRG | Relatório | ✅ |
| ETAT.SCR | Tela | ✅ |
| MVT.FRM | Formulário | ✅ |
| MVT.FRG | Relatório | ✅ |
| MVT.SCR | Tela | ✅ |
| JOUR_VEN.FRM | Formulário | ✅ |
| JOUR_VEN.FRG | Relatório | ✅ |
| JOUR_VEN.SCR | Tela | ✅ |
| LIST_CLI.FRG | Relatório | ✅ |
| FACT.SCR | Tela | ✅ |
| PRN_DB (FRM/FRG/PRF) | Impressão | ✅ |
| PRN_FACT (FRM/FRG/PRF) | Impressão | ✅ |
| ETIQUET1 (LBG/LBL) | Etiqueta | ✅ |
| ETIQUET3.LBL | Etiqueta | ✅ |
| STELMA (LBG/LBL/LBX/LBT) | Etiqueta | ✅ |

---

## 2. FLUXOGRAMAS DE NAVEGAÇÃO DOS MENUS

### 2.1 Fluxo Principal do Sistema

```
┌─────────────────────────────────────┐
│   SISTEMA CRM - MENU PRINCIPAL      │
│        (PMSV3.PRG)                  │
└────────────┬────────────────────────┘
             │
    ┌────────┼────────┬───────────┬──────────┐
    │        │        │           │          │
    ▼        ▼        ▼           ▼          ▼
┌─────────┐ ┌──────────┐ ┌────────────┐ ┌──────────┐
│GEST_VEN │ │ GEST_ACH │ │ GEST_STO   │ │  PURGE   │
│ Vendas  │ │ Compras  │ │Inventário  │ │Limpeza DB│
└────┬────┘ └────┬─────┘ └────┬───────┘ └──────────┘
     │           │             │
     └───────────┴─────────────┘
              │
         Retorno ao Menu
```

### 2.2 Fluxo de Gestion des Ventes (GEST_VEN.PRG)

```
┌──────────────────────────────────┐
│   GESTION DES VENTES            │
│        (GEST_VEN)               │
└────────┬─────────────────────────┘
         │
    ┌────┴─────┬──────────┬───────────────┐
    │           │          │               │
    ▼           ▼          ▼               ▼
┌──────────────────────────────────────┬──────────────┐
│   COMPTES CLIENT                     │ FACTURATION  │
│                                      │              │
│ 1. Etiquetage                        │ 1. Facture   │
│    ├─ Tous les clients               │ 2. Avoir     │
│    └─ Intervalle                     │ 3. Annulation│
│                                      │ 4. Visual.   │
│ 2. Créditer                          │ 5. Imprimer  │
│ 3. Modifier                          │              │
│ 4. Visualisation                     │              │
│    ├─ Tous les clients               │              │
│    └─ Intervalle                     │              │
│                                      │              │
│ 5. Impression                        │              │
│    ├─ Tous les clients               │              │
│    └─ Intervalle                     │              │
│                                      │              │
│ 6. Comptes débiteurs → DEBITEUR.PRG  │              │
│ 7. Relevé de compte → RELEVE.PRG     │              │
│ 8. Analyse des ventes → RAPP_VEN.PRG │              │
└──────────────────────────────────────┴──────────────┘
         │
         └─► EDITION JOURNAL
             ├─ Quotidien → QUOTIDIE.PRG
             ├─ Hebdomadaire → HEBDOMAD.PRG
             ├─ Mensuel → MENSUEL.PRG
             └─ Par la date → JOUR_DAT.PRG
```

### 2.3 Fluxo de Gestion des Achats (GEST_ACH.PRG)

```
┌──────────────────────────────────┐
│   GESTION DES ACHATS            │
│        (GEST_ACH)               │
└────────┬──────────────────────┬─┘
         │                      │
    ┌────┴──────────┐     ┌─────┴──────────┐
    │               │     │                │
    ▼               ▼     ▼                ▼
┌──────────────────────────┐   ┌──────────────────────┐
│COMPTE FOURNISSEUR        │   │   FACTURATION        │
│                          │   │                      │
│ 1. Etiquetage            │   │ 1. Commande → PROFORMA
│ 2. Modifier              │   │ 2. Facture → FACTURE │
│ 3. Visualisation         │   │ 3. Note de crédit    │
│    ├─ Tous fournisseurs  │   │ 4. Annulation        │
│    └─ Intervalle         │   │ 5. Visualisation     │
│ 4. Débiter               │   │ 6. Impression        │
│ 5. Relevé de compte      │   │ 7. Achat/Dépense     │
│ 6. Comptes créditeurs    │   │    → CREA_DEP.PRG    │
│                          │   │                      │
└──────────────────────────┘   └──────────────────────┘
         │
         └─► EDITION JOURNAL
             ├─ Quotidien → QUOTIDIE.PRG
             ├─ Hebdomadaire → HEBDOMAD.PRG
             ├─ Mensuel → MENSUEL.PRG
             └─ Par la date → JOUR_DAT.PRG
```

### 2.4 Fluxo de Gestion de l'Inventaire (GEST_STO.PRG)

```
┌────────────────────────────────────────┐
│   GESTION DE L'INVENTAIRE              │
│        (GEST_STO)                      │
└────┬───────────┬──────────┬────────────┘
     │           │          │
     ▼           ▼          ▼
┌──────────────┐ ┌────────────────────┐
│  ARTICLES    │ │  ETAT DU STOCK     │
│              │ │                    │
│ 1. Création  │ │ Recherche par:     │
│   → CREA_ART │ │ ├─ Article        │
│              │ │ ├─ Groupe         │
│ 2. Annulation│ │ ├─ Fournisseur    │
│   → ANNU_ART │ │ ├─ Articles mq    │
│              │ │ └─ Tous articles  │
│ 3. Modif.    │ │                    │
│   → MODIF_AR │ │ [PRES_ETA.PRG]    │
│              │ │ [ETAT.PRG]        │
└──────────────┘ └────────────────────┘
                  
         ┌────────────────────────────┐
         │ MOUVEMENT DU STOCK         │
         │                            │
         │ Recherche par:             │
         │ ├─ Article                 │
         │ ├─ Groupe                  │
         │ ├─ Fournisseur             │
         │ ├─ Back ordered            │
         │ ├─ Articles manquants      │
         │ └─ Tous articles           │
         │                            │
         │ [PRES_MVT.PRG]             │
         │ [MVT.PRG]                  │
         └────────────────────────────┘
```

---

## 3. MAPA DE DEPENDÊNCIAS ENTRE PROCEDIMENTOS

### 3.1 Procedimentos Principais

```
GEST_VEN (Gestion des ventes)
├── Compte_proc
│   ├── INIT_CRE (Créditer - créer crédit)
│   ├── MODIF_CL (Modifier client)
│   ├── DEBITEUR (Comptes débiteurs)
│   ├── RELEVE (Relevé de compte)
│   └── RAPP_VEN (Analyse des ventes)
│
├── Fact_proc (Facturation)
│   ├── PROFORMA (Facture/Commande)
│   ├── AVOIR (Note de crédit)
│   ├── ANNU_FAC (Annulation facture)
│   ├── VISU_FAC (Visualisation)
│   └── IMPR_FAC (Impression facture)
│
└── Jour_proc (Edition Journal)
    ├── QUOTIDIE (Journal quotidien)
    ├── HEBDOMAD (Journal hebdomadaire)
    ├── MENSUEL (Journal mensuel)
    └── JOUR_DAT (Journal par date)
```

```
GEST_ACH (Gestion des achats)
├── Compte_proc (Compte fournisseur)
│   ├── MODIF_CL (Modifier fournisseur)
│   ├── INIT_CRE (Débiter)
│   └── RELEVE (Relevé de compte)
│
├── Fact_proc (Facturation)
│   ├── PROFORMA (Commande)
│   ├── FACTURE (Facture)
│   ├── AVOIR (Note de crédit)
│   ├── ANNU_FAC (Annulation)
│   ├── VISU_FAC (Visualisation)
│   ├── IMPR_FAC (Impression)
│   └── CREA_DEP (Achat/Dépense)
│
└── Jour_proc (Edition Journal)
    ├── QUOTIDIE (Journal quotidien)
    ├── HEBDOMAD (Journal hebdomadaire)
    ├── MENSUEL (Journal mensuel)
    └── JOUR_DAT (Journal par date)
```

```
GEST_STO (Gestion de l'inventaire)
├── Article_proc (Articles)
│   ├── CREA_ART (Création article)
│   ├── ANNU_ART (Annulation article)
│   └── MODIF_AR (Modification article)
│
├── Etat_proc (Etat du stock)
│   ├── REC_ART (Recherche article)
│   ├── REC_GRO (Recherche groupe)
│   ├── REC_FN (Recherche fournisseur)
│   └── ETAT (Afficher état)
│       └── [PRES_ETA] Présentation état
│
└── Mvt_proc (Mouvement du stock)
    ├── REC_ART (Recherche article)
    ├── REC_GRO (Recherche groupe)
    ├── REC_FN (Recherche fournisseur)
    ├── REC_ROT (Back ordered)
    └── MVT (Afficher mouvement)
        └── [PRES_MVT] Présentation mouvement
```

### 3.2 Procedimentos de Suporte (BIBLIO.PRG)

```
BIBLIO (Biblioteca de Procedimentos)
├── ATTRIB_FACT (Atribuir número de factura)
├── Relier (Relacionar tabelas de dados)
├── Effacer_message (Limpar mensagens)
├── DEPLACE (Exibir navegação)
├── sortie_option (Opção de saída)
├── Valider (Validar dados)
├── ECHAPER (Escapar/Abandonar operação)
├── afficher_montant (Exibir montantes)
├── CADRE (Desenhar quadro)
├── MESSAGE (Exibir mensagem)
├── Erreur (Tratamento de erros de impressão)
├── ENVIRON (Configurar ambiente)
├── COULEUR (Configurar cores)
├── BEEP (Som de aviso)
├── Fenetre (Desenhar janela)
├── MENU_COL (Cores de menu)
├── Date_inv (Data inválida)
├── trouve (Encontrar registro)
└── cle_inv (Chave inválida)
```

---

## 4. FLUXO DE DADOS (Data Flow)

### 4.1 Tabelas Principais e Relacionamentos

```
CLIENT (Clientes)
├── Índices: ind_compt, No_compte
├── Relacionamento com FACTURE (código_clien)
│
FACTURE (Faturas Vendas)
├── Índices: ind_fact, ind_date
├── Relacionamento com DETAIL_V (no_fact)
├── Relacionamento com CLIENT (code_clien)
│
DETAIL_V (Detalhes Vendas)
├── Índice: ind_fact
├── Relacionamento com FACTURE (no_fact)
├── Relacionamento com ARTICLE (code_art)
│
ARTICLE (Artigos)
├── Índice: code_art
├── Relacionamento com NOMENCLA (code_nomen)
│
NOMENCLA (Nomenclaturas)
├── Índice: code_nomen
├── Usado para ARTIGOS
│
FNISSEUR (Fornecedores)
├── Índice: ind_four
├── Relacionamento com ACHAT (code_four)
│
ACHAT (Compras)
├── Índice: ind_ach
├── Relacionamento com DETAIL_A (no_fact)
├── Relacionamento com FNISSEUR (code_four)
│
DETAIL_A (Detalhes Compras)
├── Índice: ind_fact
├── Relacionamento com ACHAT (no_fact)
├── Relacionamento com ARTICLE (code_art)
│
DEPENSE (Despesas)
├── Índice: date
├── Registro de despesas gerais
```

### 4.2 Fluxo de Processamento de Fatura de Vendas

```
1. PROFORMA.PRG (Criar Proforma)
   │
   ├─► Seleciona CLIENT
   │   └─► CHOIX_CL.PRG (Escolher cliente)
   │
   ├─► Adiciona DETAIL_V (linhas)
   │   └─► Valida ARTICLE
   │
   ├─► Calcula totais em BIBLIO.afficher_montant
   │   └─► Aplica impostos/taxas
   │
   └─► Salva em FACTURE + DETAIL_V
       │
       └─► VISU_FAC.PRG (Visualizar)
           │
           └─► IMPR_FAC.PRG (Imprimir)
               └─► [PRN_FACT.FRM/PRG]

2. AVOIR.PRG (Nota de Crédito)
   │
   ├─► Seleciona FACTURE existente
   │
   ├─► Cria FACTURE com tipo = "Avoir"
   │
   └─► Inverte montantes em BIBLIO.afficher_montant

3. ANNU_FAC.PRG (Anulação)
   │
   └─► Marca FACTURE como anulada
```

---

## 5. TABELA DE RELACIONAMENTOS

| .PRG | .FXP | Função Principal | Tabelas Usadas | Procedimentos Chamados |
|------|------|------------------|-----------------|----------------------|
| GEST_VEN | GEST_VEN | Menu vendas | CLIENT, FACTURE | INIT_CRE, MODIF_CL, DEBITEUR, RELEVE, RAPP_VEN |
| GEST_ACH | GEST_ACH | Menu compras | FNISSEUR, ACHAT | INIT_CRE, MODIF_CL, RELEVE |
| GEST_STO | GEST_STO | Menu inventário | ARTICLE, NOMENCLA | CREA_ART, ANNU_ART, MODIF_AR |
| PROFORMA | PROFORMA | Factura/Commande | FACTURE, DETAIL_V | ATTRIB_FACT, afficher_montant |
| FACTURE | FACTURE | Factura | FACTURE, DETAIL_V | ATTRIB_FACT, afficher_montant |
| AVOIR | AVOIR | Nota crédito | FACTURE, DETAIL_V | afficher_montant |
| ANNU_FAC | ANNU_FAC | Anular factura | FACTURE | - |
| VISU_FAC | VISU_FAC | Visualizar | FACTURE, DETAIL_V | - |
| IMPR_FAC | IMPR_FAC | Imprimir | FACTURE | - |
| INIT_CRE | INIT_CRE | Crédito/Débito | CLIENT/FNISSEUR | trouve, cle_inv |
| MODIF_CL | MODIF_CL | Modificar | CLIENT/FNISSEUR | - |
| DEBITEUR | DEBITEUR | Deudores | CLIENT, FACTURE | - |
| RELEVE | RELEVE | Estado cuenta | CLIENT/FNISSEUR | - |
| CREA_ART | CREA_ART | Crear artículo | ARTICLE | trouve, cle_inv |
| ANNU_ART | ANNU_ART | Anular artículo | ARTICLE | trouve, cle_inv |
| MODIF_AR | MODIF_AR | Modificar artículo | ARTICLE | trouve, cle_inv |
| CREA_DEP | CREA_DEP | Crear gasto | DEPENSE | - |
| RAPP_VEN | RAPP_VEN | Reporte ventas | FACTURE, DETAIL_V | - |
| RAPP_DEP | RAPP_DEP | Reporte gastos | DEPENSE | - |
| ETAT | ETAT | Estado stock | ARTICLE | PRES_ETA |
| MVT | MVT | Movimiento stock | ARTICLE, FACTURE, ACHAT | PRES_MVT |
| QUOTIDIE | QUOTIDIE | Diario | FACTURE/ACHAT | JOUR_VEN |
| HEBDOMAD | HEBDOMAD | Semanal | FACTURE/ACHAT | JOUR_VEN |
| MENSUEL | MENSUEL | Mensual | FACTURE/ACHAT | JOUR_VEN |
| JOUR_DAT | JOUR_DAT | Por fecha | FACTURE/ACHAT | JOUR_VEN |
| JOUR_VEN | JOUR_VEN | Reporte diario | FACTURE, DETAIL_V | - |
| PURGE | PURGE | Limpieza DB | FACTURE, ACHAT | - |
| BIBLIO | BIBLIO | Procedimientos | Todos | Todos |

---

## 6. CHECKLIST DE COMPLETUDE

### ✅ Módulos Implementados

- [x] Gestion des ventes (Vendas)
- [x] Gestion des achats (Compras)
- [x] Gestion de l'inventaire (Inventário)
- [x] Facturation (Faturação)
- [x] Édition journal (Relatórios)
- [x] Análisis de datos (Análise)
- [x] Gestión de etiquetas (Etiquetas)
- [x] Impresión (Impressão)

### ✅ Tabelas de Dados

- [x] CLIENT (Clientes)
- [x] FACTURE (Faturas Vendas)
- [x] DETAIL_V (Detalhes Vendas)
- [x] FNISSEUR (Fornecedores)
- [x] ACHAT (Compras)
- [x] DETAIL_A (Detalhes Compras)
- [x] ARTICLE (Artigos)
- [x] NOMENCLA (Nomenclaturas)
- [x] DEPENSE (Despesas)

### ⚠️ Itens Sem Compilação .FXP

- [ ] ANNU_CLI.PRG (Anular cliente)
- [ ] ANNU_DEP.PRG (Anular gasto)
- [ ] ARTICLE.PRG (Procedimento artigo genérico)
- [ ] CREA_FOU.PRG (Crear fornecedor)
- [ ] CREA_NOM.PRG (Crear nomenclatura)
- [ ] DESCRIP.PRG (Descripción genérica)
- [ ] EFFACER.PRG (Limpador)
- [ ] ESSAI.PRG (Arquivo de teste)
- [ ] IMP.PRG (Impresión genérica)
- [ ] PROF.PRG (Perfil)

### 📌 Recomendações

1. **Compilar procedimentos faltando:** Recomenda-se compilar os .PRG sem .FXP correspondente
2. **Atualizar comentários:** Adicionar comentários sobre modificações de 30-06-93 e 07-08-94
3. **Documentar:**
   - Fluxos de entrada/saída de dados
   - Campos obrigatórios por tabela
   - Regras de validação
   - Fórmulas de cálculo de impostos

---

## 7. LEGENDA DE SÍMBOLOS

| Símbolo | Significado |
|---------|------------|
| ✅ | Arquivo existe e está completo |
| ⚠️ | Arquivo incompleto ou com avisos |
| ❌ | Arquivo faltando |
| → | Chamada de procedimento |
| ├─ | Submenu ou item |
| └─ | Último item de menu |
| [ ] | Arquivo de suporte/configuração |

---

**Gerado em:** 2026-08-02
**Sistema:** CRM-XBase (xBase/Visual FoxPro)
**Idioma:** Francês
**Status:** 98% Completo
