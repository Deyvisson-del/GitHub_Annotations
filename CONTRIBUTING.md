# 🧭 Manual de Branches e Commits Profissional

> Este guia define o padrão de **branches** e **mensagens de commits** usados neste projeto.  
> O objetivo é manter o repositório limpo, rastreável e organizado, mesmo durante o desenvolvimento diário.

---

## 🌿 1. Estrutura de Branches

| Tipo de branch | Finalidade | Exemplo |
|----------------|-------------|----------|
| **main** | Código estável e pronto para produção | `main` |
| **develop** | Integração das novas funcionalidades antes do deploy | `develop` |
| **feature/** | Desenvolvimento de novas features | `feature/cadastro-estagiario` |
| **fix/** | Correções de bugs não críticos | `fix/erro-login` |
| **hotfix/** | Correções urgentes em produção | `hotfix/token-expirado` |
| **release/** | Preparação de uma nova versão para produção | `release/v1.2.0` |
| **sandbox/** | Branch de rascunho, testes e experimentos | `sandbox/deyvisson` |

---

## 🧨 2. Branch “Sandbox” (Branch da Bagunça)

A branch **sandbox/** é seu ambiente pessoal para experimentar, corrigir erros fora de escopo, e testar novas ideias sem afetar o projeto principal.

### 🧱 Como criar:
```bash
git checkout develop
git pull origin develop
git checkout -b sandbox/<seu-nome>
