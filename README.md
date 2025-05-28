# Golang Project Template

Template b?sico para projetos Go, incluindo estrutura recomendada, IaC, documenta??o e exemplos.

## Estrutura sugerida

```
.
??? cmd/                # Entrypoints dos bin?rios do projeto
??? pkg/                # Pacotes reutiliz?veis
??? internal/           # C?digo privado ao projeto
??? api/                # Defini??es de API (OpenAPI/Protobuf)
??? configs/            # Arquivos de configura??o
??? scripts/            # Scripts utilit?rios
??? build/              # Arquivos de build e CI
??? deployments/        # Manifests de deploy (K8s, Docker Compose)
??? iac/                # Infraestrutura como c?digo (Terraform, etc)
??? docs/               # Documenta??o
??? tests/              # Testes automatizados
??? .gitignore
??? go.mod
```

## Recomenda??es
- Use `cmd/` para separar diferentes bin?rios.
- Coloque c?digo compartilhado em `pkg/` e c?digo privado em `internal/`.
- Mantenha documenta??o atualizada em `docs/`.
- Utilize `iac/` para scripts de infraestrutura (ex: Terraform, CloudFormation).
- Adote testes automatizados em `tests/`.
- Versione arquivos de configura??o em `configs/`.

## Exemplo de uso
```bash
git clone https://github.com/tiagonpsilva/golang_project_template.git
cd golang_project_template
# Edite o go.mod e comece seu projeto!
```
