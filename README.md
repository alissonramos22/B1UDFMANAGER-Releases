# 🚀 SAP B1 UDF Manager - Official Releases & Downloads

Repositório oficial para distribuição e download dos executáveis compilados do **SAP B1 UDF Manager**.

---

## 📥 Como Baixar a Versão Mais Recente

Para baixar o aplicativo pronto para uso em ambiente Windows:

1. Acesse a área de **[Releases / Lançamentos](https://github.com/alissonramos22/B1UDFMANAGER-Releases/releases)**.
2. Baixe o executável da versão mais recente (ex: `SAP B1 UDF Manager 1.6.0.exe`).
3. O aplicativo é **Portable** — basta dar um duplo clique para iniciar, sem necessidade de instalação complexa ou privilégios de administrador.

---

## 📌 Principais Recursos do SAP B1 UDF Manager

- **🏛️ Super Aba Governança SAP (Consultas Formatadas, Layouts Crystal & Configurações SAP)**: Suíte completa para auditoria e replicação de Consultas Formatadas (`OQCN`/`OUQR`/`CSHS` com Monaco Diff Editor), comparação de Layouts Crystal Reports (`ReportLayoutsService`/`RTYP`/`RDOC`) e diagnóstico de Parametrizações SAP B1 (`OADM`, `NNM1`, Determinação Contábil Multi-Exercício `OACP` + `OGAR` e Motor Fiscal `OSTC`/`OSTA`/`OWHT`/`OVTG`).
- **☁️ Metadados Dinâmicos & Deduplicação Inteligente por Clusters (Supabase)**: Catálogo dinâmico na nuvem para Objetos de Sistema (`sap_system_objects`) e Famílias de Tabelas Similares (`sap_table_clusters` para Marketing Docs e Logs `A***`) com cache local versionado, fallback offline, consolidação visual e replicação pela tabela canônica sem falsos-positivos.
- **⏱️ Controle Inteligente de Sessão da Service Layer (30 Minutos) & Lembrete Preventivo**: Monitoramento em janela deslizante do token `B1SESSION` (`sapSessionManager`) com contador regressivo em tempo real, alerta amarelo aos 5 minutos restantes e validação preventiva antes de iniciar comparações ou replicações.
- **📋 Duplicação Rápida de Perfis de Conexão & Normalização Global (`DIFF_ONLY`)**: Clonagem em 1 clique de conexões Service Layer e Banco de Dados SQL/HANA, filtro inicial padrão de divergências (`DIFF_ONLY`) e padronização global de badges de status e relatórios (`📄 Exportar PDF`, `📊 Exportar Excel (.xlsx)`, `📥 Exportar JSON`).
- **🔀 Comparador DDL & Merge Git-Like (SQL Server & SAP HANA)**: Comparação visual lado a lado (*Monaco Diff Editor*) de Stored Procedures, Functions e Views entre bancos de dados com suporte a tela cheia (*Recolher Lista*), filtro por LIKE e modo de proteção *Manter Destino*.
- **🏷️ Motor de Governança & Lastro DDL (Audit Header Cumulativo)**: Injeção cirúrgica de cabeçalhos de auditoria estruturados diretamente no código-fonte compilado no destino, preservando uma pilha cronológica de até 10 revisões históricas.
- **🛡️ Guardrails de Segurança DDL & Desafio CAPTCHA**: Bloqueio incondicional (*Hard Block*) de comandos catastróficos (`DROP DATABASE`, `DROP SCHEMA`, `SHUTDOWN`) e desafio interativo por CAPTCHA alfanumérico + Flag de Backup obrigatório para comandos críticos (`DROP TABLE`, `TRUNCATE`).
- **🕵️ Motor de Desofuscação contra Evasão SQL**: Decodificação em tempo real de comandos ocultos em ASCII (`CHAR/NCHAR/CHR`), literais Hexadecimais (`0x...`), concatenações contíguas e SQL Dinâmico (`EXEC / EXECUTE IMMEDIATE` no T-SQL e SAP HANA SQLScript).
- **🗄️ Auditoria Trilateral & Rollback Inteligente**: Gravação integral dos 3 estados do código (*Origem*, *Destino Anterior* e *MERGED Aplicado*) com visualizador Diff 3-Way e restauro com revisão comparativa lado a lado.
- **🧩 Gestão Completa de UDOs (User-Defined Objects)**: Criação, edição, mapeamento de tabelas filhas (*ChildTables*), colunas de busca/formulário e busca em tempo real de Menus Pai.
- **🔄 Replicação e Comparação Integrada de UDOs**: Replicação em cascata de UDOs (criação automática de UDTs pai/filhas, UDFs pertencentes e ativação do UDO no destino).
- **📤 Exportação de Metadados com Carrinho (Basket)**: Busca em árvore de tabelas nativas e UDTs com exportação em lote para **Excel (`.xlsx`)**, `.csv`, `.txt` e `.json`.
- **📥 Carga em Massa & Download de Modelos**: Upload de planilhas com visualização hierárquica em árvore (*Tree View*) e botões para download de modelos oficiais padronizados.
- **🏢 Licenciamento Corporativo por Domínio**: Validação segura por Código OTP de 6 a 8 dígitos via e-mail e gestão de limites de usuários ativos.
- **🔒 Isolamento Total de Dados (Multi-Tenant Local)**: Perfis de conexão, credenciais SAP e logs 100% isolados por conta de usuário na mesma máquina.
- **⚡ MultiButton com Presets Rápidos**: Criação manual imediata de campos (Texto, Numérico, Quantidade, Preço, Data, Memo) no Criador de Estruturas.
- **☁️ Sincronização em Nuvem de Perfis (AES-256)**: Backup criptografado ponta a ponta de conexões no Supabase.
- **📑 Audit Log Técnico**: Registro e histórico de transações diretas e em cascata gravados no SAP B1 (`@SE_UDFMAN_LOGS`).

---

## 📋 Histórico de Lançamentos

| Versão | Data de Lançamento | Tipo | Destaques |
| :--- | :---: | :---: | :--- |
| **v1.6.0** | 30/10/2026 | **Estável** | Super Aba Governança SAP (Comparador & Replicador de Consultas Formatadas OQCN/OUQR/CSHS, Comparador de Layouts Crystal Reports RTYP/RDOC e Comparador de Configurações SAP OADM/NNM1/OSTC + Determinação Contábil Multi-Exercício OACP/OGAR), Dinamização de Objetos de Sistema (`sap_system_objects`) e Clusters de Tabelas Similares (`sap_table_clusters`) no Supabase com Deduplicação Visual e Replicação Canônica sem Falso-Positivos, Controle Inteligente de Sessão da Service Layer de 30 min (`sapSessionManager`) com Lembrete Preventivo de Relogin, Duplicação Rápida de Perfis de Conexão e Normalização Global de UI, Filtros (`DIFF_ONLY`) e Exportações. |
| **v1.5.2** | 09/09/2026 | Estável | Comparador DDL & Merge Git-Like (Wizard 3 Etapas para SQL Server e SAP HANA), Injeção de Lastro DDL com Histórico Cumulativo de Revisões, Guardrails de Segurança com Hard Block e Desafio CAPTCHA + Flag de Backup, Motor de Desofuscação contra Evasão SQL (ASCII, Hex 0x..., Dynamic SQL), Auditoria Trilateral dos 3 Estados (Diff 3-Way), Rollback com Revisão Comparativa e Padronização de Modais Críticos com AppModal. |
| **v1.4.0** | 23/08/2026 | Estável | Gestão Completa e Replicação em Cascata de UDOs, Exportação em Excel (.xlsx)/CSV com Carrinho (Basket), Carga em Massa via Árvore (Tree View) e Modelos Oficiais, Licenciamento Corporativo por Domínio (OTP), Isolamento Multi-Tenant Local, MultiButton de Presets Rápidos, Contador em Tempo Real na Comparação e Backup em Nuvem AES-256. |
| **v1.3.4** | 10/08/2026 | Estável | Centralização modular no ReplicationService, Seleção inteligente Pai/Filhos no Comparador, Pré-criação de UDTs no destino, Tabela @SE_UDFMAN_LOGS em destinos, Eliminação em tempo real de itens sincronizados e Trava estrita de 15 dias em Licenças Trial. |
| **v1.3.3** | 07/08/2026 | Estável | Refatoração modular da Replicação, Gerenciador Unificado de Conexões, Detecção de Divergência de Vínculos/Descrição, Retry Automático Proxy 502/503/504, Replicação Encadeada de Dependências e Audit Log Completo. |
| **v1.3.2** | 03/08/2026 | Estável | Correções no filtro de busca anti-null, ajuste na criação de UDFs em UDTs existentes, normalização de prefixo @ e escopo de EditSize. |
| **v1.3.1** | 30/07/2026 | Estável | Auto-criação de UDTs no destino, Suporte a UDOs, Filtro em Tempo Real, Seleção em Árvore, Alocação Dinâmica de Portas e Splash Screen 0-100%. |
| **v1.3.0** | 24/07/2026 | Estável | Licenciamento Supabase, Trava por Dispositivo, Tolerância Offline 48h e Atualizações Automáticas. |
| **v1.2.1** | 23/07/2026 | Estável | Melhorias no comparador de replicação e logs de auditoria. |
| **v1.0.0** | 20/07/2026 | Inicial | Lançamento oficial da ferramenta de metadados SAP Business One. |

---

## 🛠️ Requisitos de Sistema

- **Sistema Operacional**: Windows 10 / 11 ou Windows Server 2016+ (64-bit).
- **Conectividade**:
  - Conexão com o SAP Business One Service Layer (HANA / SQL) via HTTPS/HTTP.
  - Conexão direta TCP/IP com Microsoft SQL Server (Porta 1433) ou SAP HANA (Porta 30015) para o Comparador DDL.
- **Licença**: Conta de licença válida Somar Exp.

---

## 📬 Suporte e Contato

Desenvolvido por **Somar Exp**.  
Em caso de dúvidas, relatar problemas ou solicitar novas licenças:
- **Suporte**: Entre em contato com a equipe Somar Exp.
