# README - Alterações no Projeto de Consultas Médicas

Modificações realizadas no projeto de gerenciamento de consultas médicas.

## 1. Mudanças na Estrutura da Consulta

A estrutura da consulta foi aprimorada para incluir mais detalhes sobre a consulta, exames, receitas e etc. As modificações incluem:

### **Detalhes da Consulta**
- **Tipo_Consulta**: Foi acrescentado um campo para diferenciar se a consulta é **Presencial** ou realizada via **Telemedicina**.

### **Avaliação do Médico**
- **Avaliacao_Medico**: Foi adicionado um campo para registrar a **Nota** (nota de 1 a 5) e **Comentários** sobre a consulta, permitindo uma avaliação detalhada do atendimento.

### **Exames Solicitados**
- **Exames**: Agora, é possível registrar múltiplos exames solicitados durante a consulta. Cada exame tem os seguintes campos:
  - **Nome**: Nome do exame solicitado.
  - **Data_Solicitacao**: Data em que o exame foi solicitado.
  - **Status**: Indica o status do exame (por exemplo, **Pendente** ou **Concluído**).

### **Receitas Médicas**
- **Receitas**: Registro de receitas prescritas, com informações sobre o **Nome do Medicamento**, **Dosagem** e **Duração** do tratamento.

### **Observações Médicas**
- **Observacoes**: Detalhamento das observações gerais sobre a consulta (exemplo: motivos de exames ou tratamentos recomendados).
- **Observacoes_Medico**: Foi adicionado campo específico para observações médicas após a consulta, com o exemplo "Aguardar resultados dos exames de Topografia Corneal", indicando a necessidade de um acompanhamento após o exame.

## 2. Informações sobre o Médico

- **Medico**: Incluído um novo bloco de informações sobre o médico responsável pela consulta:
  - **Nome**: Nome completo do médico.
  - **Especialidade**: Especialidade médica do profissional.
  - **CRM**: Número do CRM.
  - **Telefone e Email**: Informações para contato.
  - **Endereco**: Dados de endereço do consultório do médico.

## 3. Mudanças na Estrutura do Paciente

A estrutura de dados do paciente também foi modificada. As modificações incluem:

### **Detalhes do Paciente**
- **Telefone_Alternativo**: Adicionei um campo para um segundo número de telefone, permitindo mais opções de contato.
- **Endereco**: Alterado para incluir detalhes completos de endereço.

### **Convenio de Saúde**
- **Tipo_Plano**: Foi incluído o tipo de plano do convênio (exemplo: **Ambulatorial**).
- **Numero_Carteirinha**: Adicionado o número da carteirinha do convênio.

### **Contato de Emergência**
- **Contato_Emergencia**: Adicionamos um campo para registrar informações de contato de emergência do paciente, incluindo o nome e telefone da pessoa de contato.

### **Documentos Pessoais**
- **Documentos**: Foi incluído um campo para registrar documentos pessoais do paciente, como **CPF** e **RG**.

_________

Essas modificações tornam o sistema mais completo, permitindo um gerenciamento mais eficiente dos dados.
