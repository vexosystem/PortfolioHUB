# PortfolioHUB

Portfólio acadêmico e pessoal de **Matheus Santos**, estudante do segundo semestre de **Análise e Desenvolvimento de Sistemas**.

Projeto inicial preparado para a etapa intermediária de **Bootcamp I**.

## Objetivo

Organizar projetos acadêmicos e pessoais, documentar o aprendizado e manter um histórico de alterações com Git e GitHub.

## Perfil e conexões

- [LinkedIn](https://www.linkedin.com/in/matheus-santos-060471341/)
- [GitHub](https://github.com/vexosystem)
- Endereço previsto após ativar o GitHub Pages: https://vexosystem.github.io/PortfolioHUB/

## Conhecimentos em desenvolvimento

UiPath, Power Automate, Java, JavaScript, TypeScript e Python. A página deste projeto utiliza HTML e CSS.

## Estrutura do repositório

```text
PortfolioHUB/
├── index.html                 # Página inicial
├── assets/
│   └── style.css              # Estilos e adaptação para celular
├── academicos/
│   ├── README.md              # Índice de projetos acadêmicos
│   └── portfolio/
│       └── README.md          # Documentação do projeto inicial
├── pessoais/
│   └── README.md              # Espaço para futuros projetos pessoais
└── docs/
    ├── planejamento.md        # Organização e próximos passos
    └── CHANGELOG.md           # Registro de versões
```

## Projeto acadêmico

### PortfolioHUB - versão inicial 1.0

Página estática com apresentação acadêmica, tecnologias em aprendizado, projeto inicial e links profissionais.

- [Documentação do projeto](academicos/portfolio/README.md)
- [Página inicial no código-fonte](index.html)

## Executar localmente

Abra `index.html` em um navegador. Não há dependências, instalação ou etapa de compilação.

Se tiver Python instalado, também pode executar na raiz:

```bash
python -m http.server 8000
```

Depois, acesse `http://localhost:8000`.

## Publicar no GitHub Pages

Em **Settings > Pages**, selecione **Deploy from a branch**, branch **main**, pasta **/(root)** e salve. Aguarde a publicação e confira o link informado pelo GitHub.

## Versionamento

O primeiro envio da página corresponde à versão `1.0`. Depois de publicá-la, uma melhoria deve ser registrada em um novo commit, com mensagem que descreva a alteração. O histórico do GitHub comprova as mudanças; o CHANGELOG apenas as descreve.

## Contribuições

Sugestões podem ser abertas em Issues. Para propor alterações, crie uma branch, explique a mudança em um pull request e aguarde a revisão. Não inclua senhas, tokens ou dados pessoais de terceiros.
