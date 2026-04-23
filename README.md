# 📊 DATASUS - Tabela Unificada SIGTAP

[![Sync Status](https://github.com/RenatoKR/SIGTAP/actions/workflows/sync-datasus.yml/badge.svg)](https://github.com/RenatoKR/SIGTAP/actions/workflows/sync-datasus.yml)
[![Última Atualização](https://img.shields.io/badge/última%20atualização-2026--04--23-blue)](https://github.com/RenatoKR/SIGTAP/commits/main)

Repositório automatizado com mirror dos arquivos da **Tabela Unificada do Sistema de Gerenciamento da Tabela de Procedimentos (SIGTAP)** do DATASUS.

## 📦 Tabelas Unificadas (Últimos 6 Meses)

> **Total:** 6 arquivos | **Tamanho:** 13M

| Arquivo | Período | Tamanho | Download |
|---------|---------|---------|----------|
| `TabelaUnificada_202604_v2604091415.zip` | Abril/2026 | 2.1M | [⬇️ Download](https://github.com/RenatoKR/SIGTAP/raw/main/tabelas/TabelaUnificada_202604_v2604091415.zip) |
| `TabelaUnificada_202603_v2603111027.zip` | Março/2026 | 2.1M | [⬇️ Download](https://github.com/RenatoKR/SIGTAP/raw/main/tabelas/TabelaUnificada_202603_v2603111027.zip) |
| `TabelaUnificada_202602_v2602261644.zip` | Fevereiro/2026 | 2.1M | [⬇️ Download](https://github.com/RenatoKR/SIGTAP/raw/main/tabelas/TabelaUnificada_202602_v2602261644.zip) |
| `TabelaUnificada_202601_v2602261640.zip` | Janeiro/2026 | 2.1M | [⬇️ Download](https://github.com/RenatoKR/SIGTAP/raw/main/tabelas/TabelaUnificada_202601_v2602261640.zip) |
| `TabelaUnificada_202512_v2602261637.zip` | Dezembro/2025 | 2.1M | [⬇️ Download](https://github.com/RenatoKR/SIGTAP/raw/main/tabelas/TabelaUnificada_202512_v2602261637.zip) |
| `TabelaUnificada_202511_v2602261636.zip` | Novembro/2025 | 2.1M | [⬇️ Download](https://github.com/RenatoKR/SIGTAP/raw/main/tabelas/TabelaUnificada_202511_v2602261636.zip) |

## 📄 Notas Técnicas

> **Total:** 220 documentos

Todas as notas técnicas disponíveis estão na pasta [`notastecnicas/`](./notastecnicas/)

### Últimas Notas

- [`nota_tecnica_cgsi_sigtap_2026_04.pdf`](https://github.com/RenatoKR/SIGTAP/blob/main/notastecnicas/nota_tecnica_cgsi_sigtap_2026_04.pdf)
- [`nota_tecnica_cgsi_sigtap_2026_03.pdf`](https://github.com/RenatoKR/SIGTAP/blob/main/notastecnicas/nota_tecnica_cgsi_sigtap_2026_03.pdf)
- [`nota_tecnica_cgsi_sigtap_2026_02.pdf`](https://github.com/RenatoKR/SIGTAP/blob/main/notastecnicas/nota_tecnica_cgsi_sigtap_2026_02.pdf)
- [`nota_tecnica_cgsi_sigtap_2026_01.pdf`](https://github.com/RenatoKR/SIGTAP/blob/main/notastecnicas/nota_tecnica_cgsi_sigtap_2026_01.pdf)
- [`nota_tecnica_cgsi_sigtap_2025_12.pdf`](https://github.com/RenatoKR/SIGTAP/blob/main/notastecnicas/nota_tecnica_cgsi_sigtap_2025_12.pdf)

## 📖 Sobre o SIGTAP

A Tabela Unificada do SIGTAP contém:
- Procedimentos médicos e odontológicos
- Medicamentos e OPM (Órteses, Próteses e Materiais Especiais)
- Valores de reembolso do SUS
- CID-10 e compatibilidades
- Habilitações e classificações

## 🔄 Atualização Automática

Este repositório é atualizado **diariamente às 5h (horário de Brasília)** via GitHub Actions.

**Fonte oficial:** [FTP DATASUS](ftp://ftp2.datasus.gov.br/pub/sistemas/tup/downloads/)

## 💻 Como Usar

### Download via wget/curl
```bash
# Última tabela disponível
wget https://github.com/RenatoKR/SIGTAP/raw/main/tabelas/TabelaUnificada_202601_v2601221740.zip
```

### Clone do repositório
```bash
git clone https://github.com/RenatoKR/SIGTAP.git
cd SIGTAP/tabelas
```

### GitHub API (programático)
```bash
curl -s https://api.github.com/repos/RenatoKR/SIGTAP/contents/tabelas | jq -r '.[].download_url'
```

## 📊 Estrutura dos Arquivos

```
SIGTAP/
├── tabelas/                    # Tabelas unificadas (6 mais recentes)
│   └── TabelaUnificada_*.zip
└── notastecnicas/              # Documentação técnica oficial
    └── *.pdf
```

## ⚖️ Licença e Dados Públicos

Os dados são de **domínio público** e mantidos pelo Ministério da Saúde do Brasil.
Este repositório apenas facilita o acesso aos arquivos oficiais.

---

<div align="center">

**🤖 Atualizado automaticamente** | Última execução: 2026-04-23 06:22:15 BRT

</div>
