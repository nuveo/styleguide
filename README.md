# styleguide
 Style guides for Nuveo-originated projects
 
## Analise de impacto em implementação

- Implementar recurso e/ou corrigir onde muda a API (ou forma que sera usado) o package
- Levantamento de todos os projetos internos que usa o package que esta sendo alterado
- Estimar complexidade de atualização
- Atualizar todos os softwares

## Go

### Pull Request

Quando sua atualização envolve atualização e/ou adicionar novo *package* devemos abrir 2 **PR**:
1. Modificação no software
1. vendor

Adicionar tudo do mesmo **PR** fica impossível fazer code review.

### Packages

Package deve ter nome no singular (não no plural)
