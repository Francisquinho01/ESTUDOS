# ESTUDOS

Trilha de estudos de Francisco Oliveira Silva, organizada por origem e área.
Cada pasta é um **submódulo** que aponta para o repositório original, com todo o histórico preservado. Clique na pasta para abrir o projeto.

```
ESTUDOS/
├── EBAC/                 Curso Full Stack / Front-end — ago a set de 2024
│   ├── Frontend/         33 exercícios em ordem: HTML → CSS → JS/DOM → jQuery →
│   │                     Bootstrap → Sass/Gulp/Parcel → Ajax → Vue → React →
│   │                     CSS-in-JS → Redux → TypeScript → testes
│   ├── Backend/          (o curso não teve módulo de backend)
│   └── Outros/           Git, JavaScript OO, Babel, TypeScript, Cypress e referências
└── Faculdade/            Engenharia de Computação — Inatel (repositórios privados)
```

## Como clonar com os projetos

```bash
git clone --recurse-submodules https://github.com/Francisquinho01/ESTUDOS.git
# atualizar todos para o último commit de cada projeto
git submodule update --remote
```

## Observações
- Os nomes das pastas seguem a ordem das aulas. O nome do repositório original continua o mesmo.
- `Outros/referencia-fork-react` é um fork do repositório oficial do React, usado como material de consulta.
- Os sistemas reais e os produtos ficam em outros espaços (privados).
