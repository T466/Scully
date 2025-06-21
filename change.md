# 📑 CHANGELOG – Scully CLI

Todas as mudanças importantes neste projeto serão documentadas neste arquivo.

O formato segue as convenções de [Keep a Changelog](https://keepachangelog.com/pt-BR/1.0.0/) e as versões seguem [SemVer](https://semver.org/lang/pt-BR/).

---

## [1.9.2] – 2025-06-10

### Adicionado
- Suporte à flag `-v` para exibir a versão atual da CLI
- Variável de ambiente `SCULLY_INVENTORY` para definir inventário padrão
- Parsing por grupo no inventário com sintaxe `[grupo]`
- Novo fluxo de execução por inventário com `-i` para ambientes (ex: `inventory-prd`)
- Novo modelo de logo e identidade visual da ferramenta

### Corrigido
- Erro ao executar grupos como se fossem hosts
- Falha ao passar argumentos com espaços no módulo `shell.sh`
- Limpeza de link simbólico com verificação via `-L` antes do `rm`

### Melhorado
- Estrutura de módulos organizada e padronizada
- Saídas com feedback visual (✅ / ❌) para cada host
- Ajuda integrada mais clara e contextualizada com exemplos reais

---

## [1.9.1] – *não publicado oficialmente*
> Versão intermediária para testes internos. Recursos integrados na 1.9.2.

---

## [1.9.0] – *não publicado oficialmente*
> Primeiro release funcional com execução em massa por IP ou grupo, módulo `ping.sh`, `file.sh`, `service.sh` e suporte básico a inventário único.

---

## 📦 Distribuição

No momento, apenas o pacote `.tar.gz` está disponível via GitHub:
- [scully-1.9.2.tar.gz](https://raw.githubusercontent.com/T466/Scully/main/scully-1.9.2.tar.gz)

---

## 📌 Próximo

- Empacotamento `.rpm`
- Execução paralela com logs por host
- Integração opcional com Zabbix Agent
- Suporte a inventário remoto (via URL ou API)

---

