# desafio-controle-declaracao-imposto-de-renda

# 📊 Controlador de Imposto de Renda no Excel

Projeto desenvolvido como parte do Desafio Prático da **DIO (Digital Innovation One)**, com o objetivo de criar uma ferramenta prática e organizada no Microsoft Excel para centralizar e validar dados essenciais à Declaração de Imposto de Renda de Pessoa Física (IRPF).

---

## 🛠️ Funcionalidades do Projeto

A folha de cálculo foi estruturada em 4 módulos/separadores principais:

1. **`TITULAR`**: Cadastro completo dos dados do contribuinte (Nome, CPF, Título de Eleitor, Endereço, Cônjuge e Dependentes) com validação de dados em campos de seleção (Sim/Não).
2. **`INFORMES`**: Agregador de rendimentos bancários com soma automática dos valores cadastrados (`=SUM(...)`) e identificação de anexos dos comprovantes.
3. **`NOTAS`**: Histórico e controlo de entradas mensais de receitas (Data, Categoria e Valor) com lista suspensa (Dropdown) para seleção rápida de categoria (`HOLERITE`, `CNPJ`, `FREELANCER`).
4. **`BANCOS`**: Tabela de apoio com a lista oficial e códigos das principais instituições financeiras.

---

## 📁 Estrutura do Repositório

```text
.
├── Desafio DIO - Controlador de Imposto de Renda.xlsx  # Ficheiro principal do Excel
└── README.md                                           # Documentação do projeto
