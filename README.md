# 📁 Ferramentas de Perícia Judicial Financeira e Contábil

> Automação com IA para resumo de processos, cálculos periciais, laudos e petições — com segurança total de dados judiciais (Estratégia "Cofre").

---

## 🧠 O que este projeto faz

Este repositório reúne ferramentas para **peritos judiciais financeiros e contábeis**, automatizando as etapas mais trabalhosas da perícia:

| Funcionalidade | Descrição |
|---|---|
| 📄 **Resumo de Processos** | Leitura e síntese automática de peças processuais com IA |
| 🧮 **Cálculos Periciais** | Correção monetária, juros, apuração de danos e diferenças |
| 📝 **Laudos Periciais** | Geração de minutas de laudos com base nos cálculos realizados |
| ⚖️ **Petições** | Auxílio na elaboração de petições técnicas e esclarecimentos |

---

## 🚀 Tecnologias

- **Python** — linguagem principal
- **Inteligência Artificial** — automação com agentes IA (Google Antigravity)
- **Variáveis de ambiente** — configuração segura via `.env`

---

## 📂 Estrutura do Projeto

```
/
├── .agente/               # Agentes e habilidades de IA
│   └── habilidades/
├── dados/                 # Dados fictícios para testes (NUNCA dados reais)
├── processos/             # Pasta bloqueada para o Git (dados locais)
├── .env.exemplo           # Modelo de variáveis de ambiente
├── .gitignore             # Bloqueio automático de arquivos sensíveis
└── README.md
```

---

## ⚙️ Como usar

### 1. Clone o repositório
```bash
git clone https://github.com/GleusonPaiva/Ferramentas-de-Per-cia-Financeira-e-Cont-bil.git
cd Ferramentas-de-Per-cia-Financeira-e-Cont-bil
```

### 2. Configure o ambiente
```bash
cp .env.exemplo .env
# Edite o .env com os caminhos da sua máquina
```

### 3. Instale as dependências
```bash
pip install -r requirements.txt
```

---

## 🛡️ Segurança — Estratégia "Cofre"

A segurança dos dados judiciais é prioridade absoluta:

- **`.gitignore` configurado** para bloquear automaticamente `.xlsx`, `.pdf`, `.docx` e `.csv`
- **Dados reais** nunca vão para a nuvem — use sempre a pasta `/dados/` com dados fictícios
- **Variáveis sensíveis** ficam no `.env` local, nunca commitadas
- **Mock Data** disponível em `modelo_dados.csv` para testes e demonstrações

> [!IMPORTANT]
> A segurança dos dados do processo é responsabilidade direta do perito. Verifique sempre o `status` do seu repositório antes de realizar um `push`.

---

## 👤 Autor

**Gleuson Paiva** — Perito Judicial Financeiro e Contábil  
[![GitHub](https://img.shields.io/badge/GitHub-GleusonPaiva-181717?logo=github)](https://github.com/GleusonPaiva)

---

## 📄 Licença

Este projeto está sob licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
