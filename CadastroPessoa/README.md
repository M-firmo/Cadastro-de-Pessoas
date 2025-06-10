# CadastroPessoa

Uma aplicação gráfica simples em Java usando **Swing** para realizar o **cadastro de pessoas físicas ou jurídicas**. Os dados não são armazenados em banco de dados, sendo apenas uma interface visual para fins de demonstração ou aprendizado.

## 📋 Funcionalidades

- Cadastro de dados pessoais como CPF/CNPJ, nome, RG, e-mail, telefone, endereço etc.
- Seleção do tipo de pessoa: Física ou Jurídica.
- Indicação se é Fornecedor via `JCheckBox`.
- Marcação de Situação: Ativo ou Inativo via `JRadioButton`.
- Botões de ação:
  - **Confirmar:** mostra mensagem de sucesso e limpa todos os campos.
  - **Excluir:** limpa todos os campos do formulário.
  - **Limpar:** também limpa todos os campos do formulário.

## 🖼️ Interface

A interface é construída com `JLabel`, `JTextField`, `JComboBox`, `JCheckBox`, `JRadioButton` e `JButton`. Os componentes são posicionados manualmente usando `null layout` e `setBounds()`.

## 🧠 Tecnologias Usadas

- Java SE
- Java Swing (para GUI)
- IDE recomendada: IntelliJ IDEA ou Eclipse

## 🚀 Como Executar

1. Clone ou baixe este repositório.
2. Compile e execute o arquivo `CadastroPessoa.java`:

```bash
javac CadastroPessoa.java
java CadastroPessoa
