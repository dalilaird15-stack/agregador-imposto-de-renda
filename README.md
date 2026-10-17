# Agregador de Dados para Declaração de Imposto de Renda 🦁📊

**Autora:** Dalila Ramos

## 📝 Descrição do Projeto
Este projeto é uma ferramenta robusta desenvolvida no Excel para facilitar a organização e consolidação de informações essenciais para a Declaração do Imposto de Renda. O agregador permite o registro validado de receitas e despesas dedutíveis, garantindo a integridade dos dados e gerando um resumo financeiro automático.
Projeto desenvolvido como parte do desafio prático da plataforma DIO (Digital Innovation One).

## 🎯 Funcionalidades e Aprendizados Aplicados
- **Dashboard Visual e Fórmulas Avançadas:** A aba "Resumo" utiliza funções como `SOMA` e `SOMASE` para calcular automaticamente os totais de Saúde e Educação, apresentando os resultados em um Gráfico de Barras comparativo.
- **Validação de Dados:** Uso de listas suspensas (ex: categorias de despesas) para padronizar as entradas e evitar erros de digitação.
- **Formatação Condicional (Alertas):** Células ficam automaticamente vermelhas quando um valor financeiro é inserido, mas a coluna de "Comprovante" é deixada em branco, alertando o usuário.
- **Proteção de Planilha:** As células que contêm fórmulas matemáticas foram bloqueadas (🔒) para evitar edições acidentais, garantindo a segurança da ferramenta.
- **Integração com Python:** A estrutura base do arquivo `.xlsx` foi construída utilizando um script em linguagem **Python**, demonstrando conhecimentos em automação e geração de dados.

## 🚀 Como utilizar a ferramenta
1. Faça o download do arquivo `Agregador_Imposto_de_Renda_Completo.xlsx` disponível neste repositório.
2. Abra o arquivo no Microsoft Excel.
3. Registre suas fontes pagadoras na aba **Rendimentos** e seus recibos médicos/escolares na aba **Pagamentos**.
4. Acompanhe os totais consolidados em tempo real na aba **Resumo**.

## 📁 Estrutura do Repositório
- `/images`: Contém capturas de tela demonstrando o funcionamento dos menus, alertas visuais e do dashboard da planilha.
- `Agregador_Imposto_de_Renda_Completo.xlsx`: O arquivo principal do projeto pronto para uso.
- `gerar.py` *(opcional)*: Script utilizado para a geração estrutural da planilha.
