# Projeto Exemplo - Git Flow

Repositório demonstra a implementação/uso do Git Flow.

## Sobre Git Flow

O Git Flow é uma estratégia de branching robusta que utiliza:

- `master/main`: código estável em produção
- `develop/dev`: branch de integração para desenvolvimento
- `feature/*`: desenvolvimento de novas funcionalidades
- `release/*`: preparação para releases
- `hotfix/*`: correções urgentes em produção
- `bugfix/*`: correções na develop/dev

## Workflow

1. Features são desenvolvidas em branches a partir da `develop/dev`
2. Releases são preparadas em branches específicas
3. Hotfixes são aplicados diretamente na `master/main` e sincronizados com `develop/dev`
4. Todo código é integrado via pull requests
