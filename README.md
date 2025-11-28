# IARA — TCC CLEYTON


**IARA — Aplicação de Inteligência Artificial e Automação de Processos no contexto do FGTS Digital**


Este repositório contém material de apresentação do TCC: arquitetura, trechos de `docker-compose`, instruções de acesso e roteiro de demonstração.


> **Importante:** este repositório não é um pacote para execução automática — é apenas para mostrar como o sistema está organizado, como acessar os serviços (N8N, Chatwoot e Evolution API) e para guiar a demonstração durante a defesa.


## O que tem aqui
- `stack/` — arquivos `docker-compose` separados (N8N, Evolution API, Chatwoot) prontos para importar no Portainer.
- `env/.env.example` — variáveis usadas como referência (NÃO comitar senhas reais).
- `docs/` — documentação para apresentação e deploy manual.


## Como usar (apresentação)
1. Abra o Portainer/Servidor onde a stack está rodando.
2. Mostre os containers no Portainer (N8N, Chatwoot, Evolution API)
3. Acesse os endpoints configurados (ex.: N8N editor, Chatwoot painel de conversas, Evolution API).
4. Demonstre um fluxo simples no N8N, uma conversa no Chatwoot conectada ao bot e uma chamada à Evolution API.


## Contato do projeto
- Bot / contato de demonstração: +55 49 9828-6960
