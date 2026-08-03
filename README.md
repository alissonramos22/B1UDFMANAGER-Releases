# 🚀 SAP B1 UDF Manager - Official Releases & Downloads

Repositório oficial para distribuição e download dos executáveis compilados do **SAP B1 UDF Manager**.

---

## 📥 Como Baixar a Versão Mais Recente

Para baixar o aplicativo pronto para uso em ambiente Windows:

1. Acesse a área de **[Releases / Lançamentos](https://github.com/alissonramos22/B1UDFMANAGER-Releases/releases)**.
2. Baixe o executável da versão mais recente (ex: `SAP B1 UDF Manager 1.3.1-hf1.exe`).
3. O aplicativo é **Portable** — basta dar um duplo clique para iniciar, sem necessidade de instalação complexa ou privilégios de administrador.

---

## 📌 Principais Recursos do SAP B1 UDF Manager

- **🛠️ Criador e Importador de Metadados**: Criação de Tabelas de Usuário (UDT) e Campos Customizados (UDF) com suporte a Valores Válidos, Tabelas do Sistema e Objetos de Usuário (UDO).
- **🔄 Replicação Multi-Base Inteligente**: Comparação de metadados em tempo real entre bases de dados (*Homologação ➔ Produção*), criação automática de UDTs no destino, filtro por palavra-chave e interrupção em 1 clique.
- **🌳 Seleção Hierárquica em Árvore**: Controle bidirecional de seleção de tabelas e campos na comparação (Pai/Filhos).
- **⚡ Alocação Dinâmica de Portas Livres**: Sistema inteligente de Proxy que detecta e aloca automaticamente a próxima porta livre (`3000 -> 3001`), evitando conflitos no cliente.
- **🎨 Splash Screen Interativa & Trava de Instância Única**: Tela de carregamento com progresso de `0%` a `100%` e trava de processo único (`Single Instance Lock`) que foca a janela ativa.
- **📑 Audit Log Técnico**: Registro e histórico completo de transações formatado em PDF (A4 Retrato) para auditorias.
- **🛡️ Licenciamento & Sessão Única**: Controle de acesso via Supabase Auth por dispositivo único com tolerância offline de até 48 horas.
- **🤖 Treinamento Guiado Interativo**: Tour dinâmico que ensina a utilizar cada recurso direto na interface.

---

## 📋 Histórico de Lançamentos

| Versão | Data de Lançamento | Tipo | Destaques |
| :--- | :---: | :---: | :--- |
| **v1.3.1-hf1** | 03/08/2026 | **Estável / Hotfix** | Correções no filtro de busca anti-null, ajuste na criação de UDFs em UDTs existentes, normalização de prefixo @ e escopo de EditSize. |
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
