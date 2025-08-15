# newayCI: teste de execução
CI: teste

Proteção de branch: teste
Proteção ok

## Objetivo
Organizar a base do projeto e definir o fluxo de contribuição.

## Estrutura
- `src/` – código-fonte


# 1) Criar estrutura mínima
mkdir -p src tests docs
echo "# Roadmap" > docs/PLAN.md
echo "// código entra aqui" > src/.keep
echo "// testes entram aqui" > tests/.keep

# 2) Atualizar o README com as seções básicas
cat >> README.md << 'EOF'

## Objetivo
Organizar a base do projeto e definir o fluxo de contribuição.

## Estrutura
- `src/` – código-fonte
- `tests/` – testes
- `docs/` – documentação

## Como contribuir
1. `git checkout -b feat/sua-feature`
2. Commits claros (Conventional Commits)
3. Abra um PR para `main`
