# MSFilesA

Projeto de skills do Claude Code para criacao de documentos (Word, Excel, PowerPoint e PDF).

## Requisitos

- **Node.js** (v18+) - https://nodejs.org/
- **Python** (3.8+) - https://python.org/
- **Claude Code** - https://claude.com/claude-code

## Instalacao

### Windows

```cmd
install-windows.bat
```

### Linux/macOS

```bash
chmod +x install-linux.sh
./install-linux.sh
```

## Como Usar

1. Abra o terminal na pasta do projeto
2. Execute `claude` para iniciar o Claude Code
3. Solicite a criacao de documentos:

**Exemplos de comandos:**

```
Crie um documento Word com um relatorio de vendas
Crie uma planilha Excel com dados financeiros
Crie uma apresentacao PowerPoint sobre o projeto
Crie um PDF com o contrato
```

## Estrutura do Projeto

```
MSFilesA/
â”œâ”€â”€ .claude/
â”‚   â””â”€â”€ skills/          # Skills do Claude (docx, xlsx, pptx, pdf)
â”œâ”€â”€ assets/              # Imagens e recursos
â”œâ”€â”€ out/                 # Arquivos gerados
â”œâ”€â”€ scripts/             # Scripts de geracao
â”‚   â”œâ”€â”€ generate.docx.py
â”‚   â”œâ”€â”€ generate.xlsx.js
â”‚   â”œâ”€â”€ generate.pptx.js
â”‚   â””â”€â”€ generate.pdf.py
â”œâ”€â”€ install-windows.bat  # Instalador Windows
â”œâ”€â”€ install-linux.sh     # Instalador Linux
â””â”€â”€ package.json
```

## Skills Disponiveis

| Skill | Descricao |
|-------|-----------|
| docx  | Criar/editar documentos Word |
| xlsx  | Criar/editar planilhas Excel |
| pptx  | Criar/editar apresentacoes PowerPoint |
| pdf   | Criar/manipular arquivos PDF |

## Suporte

Para reportar problemas: https://github.com/inematds/MSFilesA/issues

---

Projeto adaptado da comunidade INEMA TDS - Marca Arckhe