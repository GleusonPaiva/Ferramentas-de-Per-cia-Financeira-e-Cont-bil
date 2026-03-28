# 📁 Template de Perícia Judicial (Estratégia "Cofre")

Este repositório foi configurado para garantir a **segurança total de dados judiciais**. Seguindo as normas de perícia digital e a estratégia de "Cofre", nunca enviamos dados reais para nuvem.

## 🛡️ Regras de Segurança

1.  **Arquivos Ignorados**: O arquivo `.gitignore` está configurado para bloquear automaticamente qualquer arquivo das extensões `.xlsx`, `.pdf`, `.docx` e `.csv`.
2.  **Dados Reais**: Nunca coloque arquivos reais diretamente na raiz. Utilize a pasta `/dados/` ou `/processos/`. Elas estão bloqueadas para o Git.
3.  **Mock Data (Dados Fictícios)**: Para demonstrar o funcionamento de scripts, utilize sempre o arquivo `modelo_dados.csv` (ou similares) com nomes e valores genéricos.
4.  **Variáveis de Ambiente**: Se o seu script precisar de caminhos de pasta específicos da sua máquina, use um arquivo `.env` (baseado no `.env.example`). O arquivo `.env` também está bloqueado para o Git.

---
> [!IMPORTANT]
> A segurança dos dados do processo é responsabilidade direta do perito. Verifique sempre o `status` do seu repositório antes de realizar um `push`.
