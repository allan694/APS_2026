# SGA-JA – Sistema de Gestão Ambiental (ONG Jovens Ambientalistas)

> Trabalho de Atividades Práticas Supervisionadas (APS) desenvolvido para o curso de **Ciência da Computação** da **Universidade Paulista (UNIP)**.

---

## Sobre o Projeto

Este repositório contém a documentação completa, especificações de requisitos, modelagem UML e protótipos de interface do sistema **SGA-JA** (Sistema de Gestão Ambiental – Jovens Ambientalistas). 

O trabalho simula a atuação profissional de Engenharia de Software no desenvolvimento do escopo de produto para uma organização sem fins lucrativos fictícia: a **ONG Jovens Ambientalistas**. A entidade acolhe jovens em vulnerabilidade social, oferece formação profissionalizante por meio de professores ex-alunos e comercializa brinquedos sustentáveis para os mercados nacional e internacional.

---

## Identificação do Autor

* **Instituição:** Universidade Paulista – UNIP
* **Curso:** Bacharelado em Ciências da Computação
* **Aluno:** Allan Alexandre Stanley de Oliveira
* **RA:** C5090A8
* **Ano:** 2026

---

## Escopo do Sistema (SGA-JA)

O sistema proposto foi projetado como uma aplicação web responsiva para integrar e substituir controles manuais e planilhas dispersas, organizando-se em módulos essenciais:

1. **Módulo de Jovens:** Cadastro, acompanhamento escolar/formativo e controle de remuneração vinculada à produção.
2. **Módulo de Professores:** Cadastro, alocação de turmas/oficinas e controle de horas/remuneração.
3. **Módulo de Produtos e Estoque:** Gestão de matérias-primas (plástico reciclado, madeira de reflorestamento), controle de estoque com alerta de níveis mínimos e ordens de fabricação.
4. **Módulo Comercial & Vendas:** Cadastro de clientes corporativos (B2B/B2C), registro de vendas no mercado interno e suporte à exportação (BRL e USD).
5. **Módulo Financeiro:** Controle de fluxo de caixa, despesas operacionais (incluindo pagamento de bolsas aos jovens), receitas e prestação de contas.
6. **Segurança & Governança:** Autenticação baseada em perfis (RBAC), suporte a 2FA para perfis administrativos e conformidade com a LGPD (Lei nº 13.709/2018).

---

## Modelagem do Sistema

O projeto contempla especificações formais de requisitos e diagramas comportamentais e estruturais:

* **32 Requisitos Funcionais (RF01 a RF32)**
* **15 Requisitos Não Funcionais (RNF01 a RNF15)**
* **Modelagem UML:**
  * **Diagrama de Casos de Uso:** Mapeamento de 12 casos de uso entre 6 perfis de atores.
  * **Diagrama de Classes:** 18 entidades do domínio, com métodos de negócio, atributos e multiplicidades detalhadas.

*(Os diagramas foram modelados em sintaxe Mermaid e estão disponíveis tanto no relatório quanto nos arquivos do repositório.*

---

## Protótipos de Interface

O projeto conta com protótipos navegáveis de média fidelidade criados em **HTML5 e CSS3 puros** (sem frameworks ou dependências externas), seguindo a identidade visual padrão da ONG (azul `#1e5f9e` e verde `#2e7d32`):

| Arquivo | Descrição da Interface |
|---|---|
| `prototipo_1_login.html` | Tela de autenticação centralizada, recuperação de acesso e aviso LGPD. |
| `prototipo_2_dashboard.html` | Painel gerencial com KPIs operacionais, gráficos de vendas/formação e extrato financeiro. |
| `prototipo_3_cadastro_jovem.html` | Formulário setorizado (dados pessoais, documentos, endereço, dados escolares) e histórico recente. |
| `prototipo_4_estoque.html` | Tabela dinâmica de SKUs, sinalizadores visuais de estoque crítico e histórico de movimentações. |

> **Como visualizar os protótipos:** Basta clonar o repositório ou baixar os arquivos e abri-los diretamente em qualquer navegador moderno (Chrome, Firefox, Edge, etc.).

---

## Estrutura de Diretórios

```text
├── arquivos/
│   ├── documentos/
│   │   ├── Allan_Alexandre_APS_Engenharia_Requisitos.pdf   # Relatório final formatado
│   │   └── diagramas/                                     # Imagens UML renderizadas
│   │       ├── caso_de_uso.png
│   │       └── diagrama_classes.png
│   ├── prototipos/
│   │   ├── prototipo_1_login.html                         # Interface de Login
│   │   ├── prototipo_2_dashboard.html                     # Dashboard principal
│   │   ├── prototipo_3_cadastro_jovem.html                # Formulário de Jovens
│   │   └── prototipo_4_estoque.html                       # Controle de Estoque
│   └── texto/
│       └── trabalho_completo.docx                         # Arquivo editável do texto final
├── video/
│   └── apresentacao_sga_ja.mp4                            # Vídeo da apresentação da APS
├── LICENSE                                                # Licença do projeto
└── README.md                                              # Documentação principal do repositório
