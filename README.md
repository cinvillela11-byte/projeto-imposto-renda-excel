# 📊 Agregador de Dados para Imposto de Renda — Excel

Projeto desenvolvido como desafio prático para aplicar recursos do **Microsoft Excel** na criação de uma ferramenta de organização e consolidação de informações úteis à preparação da declaração de Imposto de Renda.

> **Importante:** este projeto é um organizador de dados para fins de estudo e documentação. Ele não substitui a declaração oficial, as regras da Receita Federal ou a orientação de um profissional habilitado.

## 🎯 Objetivo

Criar uma ferramenta simples, organizada e amigável para reunir informações que podem ser necessárias durante a preparação da declaração de Imposto de Renda, reduzindo a dispersão dos dados e facilitando a conferência.

## 🧰 Tecnologias e recursos utilizados

- Microsoft Excel
- Fórmulas e referências entre abas
- Validação de dados com listas suspensas
- Tabelas estruturadas
- Formatação condicional
- Hiperlinks para navegação
- Resumo automático com indicadores
- Gráfico de acompanhamento
- GitHub e Markdown para documentação

## 📁 Estrutura da planilha

### `MENU`
Página inicial do projeto, com instruções de utilização e links de navegação.

### `RESUMO`
Apresenta indicadores calculados automaticamente, como total de rendimentos, IR retido informado, total de pagamentos, quantidade de bens/direitos e quantidade de registros por categoria.

### `RENDIMENTOS`
Área para registrar fontes de renda, valores brutos, IR retido e valor líquido.

### `PAGAMENTOS`
Área para organização de pagamentos e despesas para conferência documental.

### `BENS_DIREITOS`
Área para catalogação de bens e direitos, com descrição, tipo, instituição/local, valores e documentação.

### `DEPENDENTES`
Cadastro organizado de dependentes para fins de conferência.

### `LISTAS`
Aba de apoio usada nas validações de dados. Fica oculta para manter a interface principal limpa.

## ⚙️ Funcionalidades

### Validação de dados
Listas suspensas padronizam categorias como tipo de rendimento, tipo de pagamento, tipo de bem/direito, tipo de dependente e status.

### Cálculos automáticos
Na aba `RENDIMENTOS`, o valor líquido é calculado automaticamente pela diferença entre valor bruto e IR retido informado.

A aba `RESUMO` consolida os dados por meio de funções como `SUM` e `COUNTIF`.

### Formatação condicional
Os status **Pendente** e **Revisar** recebem destaque visual para facilitar a identificação dos registros que precisam de atenção.

### Navegação
A planilha possui links internos para facilitar a movimentação entre o menu e as abas do projeto.

## 🖼️ Capturas de tela

Se desejar, adicione capturas ao repositório:

```text
images/
├── menu.png
├── resumo.png
├── rendimentos.png
├── pagamentos.png
└── bens_direitos.png
```

## 🚀 Como utilizar

1. Baixe `Projeto_Imposto_de_Renda.xlsx`.
2. Abra no Microsoft Excel.
3. Acesse `MENU`.
4. Consulte as instruções.
5. Preencha as abas de acordo com os documentos que deseja organizar.
6. Utilize as listas suspensas.
7. Confira `RESUMO`.
8. Revise registros marcados como **Pendente** ou **Revisar**.

## 🔒 Cuidados com dados pessoais

Como o repositório do desafio deve ser público, **não publique informações reais** como CPF, CNPJ, dados bancários, endereços, documentos pessoais ou informações financeiras particulares.

Para a demonstração no GitHub, utilize dados fictícios ou anonimizados.

## 📚 Aprendizados

Durante o desenvolvimento foram praticados conceitos de:

- organização de dados;
- criação de tabelas;
- validação de informações;
- funções de soma e contagem;
- referências entre planilhas;
- fórmulas;
- formatação condicional;
- interfaces simples;
- navegação por hiperlinks;
- documentação técnica em Markdown.

O projeto demonstra como uma planilha pode funcionar como uma ferramenta de controle e acompanhamento, e não apenas como um local de armazenamento de dados.

## 📌 Próximas melhorias

- filtros e segmentações;
- proteção de células com fórmulas;
- dashboard mais avançado;
- importação de dados;
- automatizações com VBA ou Office Scripts;
- validações adicionais;
- integração com outras fontes de dados;
- geração de relatórios.

## 👩‍💻 Autoria

Projeto desenvolvido para fins educacionais como parte de um desafio prático da **DIO**.

---

## 📦 Entrega

O repositório deve conter este `README.md`, o arquivo Excel e, opcionalmente, a pasta `images/` com capturas de tela do projeto.
