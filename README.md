# 🚀 SAP B1 UDF Manager - Official Releases & Downloads

Repositório oficial para distribuição e download dos executáveis compilados do **SAP B1 UDF Manager**.

---

## 📥 Como Baixar a Versão Mais Recente

Para baixar o aplicativo pronto para uso em ambiente Windows:

1. Acesse a área de **[Releases / Lançamentos](https://github.com/alissonramos22/B1UDFMANAGER-Releases/releases)**.
2. Baixe o executável da versão mais recente (ex: `SAP B1 UDF Manager 1.4.0.exe`).
3. O aplicativo é **Portable** — basta dar um duplo clique para iniciar, sem necessidade de instalação complexa ou privilégios de administrador.

---

## 📌 Principais Recursos do SAP B1 UDF Manager

- **🧩 Gestão Completa de UDOs (User-Defined Objects)**: Módulo totalmente redesenhado para gerenciar objetos *Master Data* e *Document*, tabelas filhas (*ChildTables*), colunas de busca/formulário e busca em tempo real de Menus Pai.
- **🔄 Replicação e Comparação Integrada de UDOs**: Comparador inteligente com replicação em cascata de UDOs (criação automática de UDTs pai/filhas, UDFs pertencentes e ativação do UDO no destino).
- **📤 Exportação de Metadados com Carrinho (Basket)**: Busca em árvore de tabelas nativas e UDTs com exportação em lote para **Excel (`.xlsx`)**, `.csv`, `.txt` e `.json`.
- **📥 Carga em Massa & Download de Modelos**: Upload de planilhas com visualização hierárquica em árvore (*Tree View*) e botões para download de modelos oficiais padronizados.
- **🏢 Licenciamento Corporativo por Domínio**: Validação segura por Código OTP de 6 a 8 dígitos via e-mail e gestão de limites de usuários ativos.
- **🔒 Isolamento Total de Dados (Multi-Tenant Local)**: Perfis de conexão, credenciais SAP e logs 100% isolados por conta de usuário na mesma máquina.
- **⚡ MultiButton com Presets Rápidos**: Criação manual imediata de campos (Texto, Numérico, Quantidade, Preço, Data, Memo) no Criador de Estruturas.
- **📊 Contador em Tempo Real no Comparador**: Leitura contínua bloco a bloco de UDTs/UDFs com card visual dinâmico.
- **☁️ Sincronização em Nuvem de Perfis (AES-256)**: Backup criptografado ponta a ponta de conexões no Supabase.
- **⚡ Resiliência Service Layer (Retry Interceptor)**: Re-tentativas automáticas contra erros transitórios 502/503/504 em instabilidades da Service Layer.
- **📑 Audit Log Técnico**: Registro e histórico de transações diretas e em cascata gravados no SAP B1 (`@SE_UDFMAN_LOGS`).

---

## 📋 Histórico de Lançamentos

| Versão | Data de Lançamento | Tipo | Destaques |
| :--- | :---: | :---: | :--- |
| **v1.4.0** | 23/08/2026 | **Estável** | Gestão Completa e Replicação em Cascata de UDOs, Exportação em Excel (.xlsx)/CSV com Carrinho (Basket), Carga em Massa via Árvore (Tree View) e Modelos Oficiais, Licenciamento Corporativo por Domínio (OTP), Isolamento Multi-Tenant Local, MultiButton de Presets Rápidos, Contador em Tempo Real na Comparação e Backup em Nuvem AES-256. |
| **v1.3.4** | 10/08/2026 | Estável | Centralização modular no ReplicationService, Seleção inteligente Pai/Filhos no Comparador, Pré-criação de UDTs no destino, Tabela @SE_UDFMAN_LOGS em destinos, Eliminação em tempo real de itens sincronizados e Trava estrita de 15 dias em Licenças Trial. |
| **v1.3.3** | 07/08/2026 | Estável | Refatoração modular da Replicação, Gerenciador Unificado de Conexões, Detecção de Divergência de Vínculos/Descrição, Retry Automático Proxy 502/503/504, Replicação Encadeada de Dependências e Audit Log Completo. |
| **v1.3.2** | 03/08/2026 | Estável | Correções no filtro de busca anti-null, ajuste na criação de UDFs em UDTs existentes, normalização de prefixo @ e escopo de EditSize. |
| **v1.3.1** | 30/07/2026 | Estável | Auto-criação de UDTs no Destino, Suporte a UDOs, Filtro em Tempo Real, Seleção em Árvore, Alocação Dinâmica de Portas e Splash Screen 0-100%. |
| **v1.3.0** | 24/07/2026 | Estável | Licenciamento Supabase, Trava por Dispositivo, Tolerância Offline 48h e Atualizações Automáticas. |
| **v1.2.1** | 23/07/2026 | Estável | Melhorias no comparador de replicação e logs de auditoria. |
| **v1.0.0** | 20/07/2026 | Inicial | Lançamento oficial da ferramenta de metadados SAP Business One. |

---

## 🛠️ Requisitos de Sistema

- **Sistema Operacional**: Windows 10 / 11 ou Windows Server 2016+ (64-bit).
- **Conectividade**: Conexão com o SAP Business One Service Layer (HANA / SQL) via HTTPS/HTTP.
- **Licença**: Conta de licença válida Somar Exp.

---

## 📬 Suporte e Contato

Desenvolvido por **Somar Exp**.  
Em caso de dúvidas, relatar problemas ou solicitar novas licenças:
- **Suporte**: Entre em contato com a equipe Somar Exp.
