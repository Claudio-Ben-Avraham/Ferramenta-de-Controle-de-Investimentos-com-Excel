# Simulador de Investimentos em Fundos Imobiliários com Excel

Este projeto propõe uma ferramenta prática para simulação de investimentos em fundos imobiliários (FIIs) utilizando os recursos do Excel. O objetivo é ajudar investidores a tomarem decisões mais informadas, automatizando cálculos financeiros complexos e oferecendo uma visão clara do potencial retorno dos seus investimentos.

---

## Objetivo

Desenvolver uma planilha Excel que permita ao usuário simular diferentes cenários de investimento em FIIs, calculando automaticamente:

- Valor total investido ao longo do tempo.
- Patrimônio acumulado considerando o preço das cotas.
- Dividendos mensais recebidos e acumulados.
- Projeção de rendimento com base em dados históricos ou estimativas.

---

## Conceitos de Excel Aplicados

Para garantir que a planilha seja prática, intuitiva e automatizada, aplicaremos os seguintes conceitos e funcionalidades do Excel:

- **Fórmulas Dinâmicas:** para calcular valores acumulados, médias e projeções automáticas.
- **Referências Relativas e Absolutas:** para facilitar a replicação de fórmulas ao longo da tabela.
- **Função SOMA, MULTIPLICAÇÃO, PROCV, SE:** para cálculos financeiros e lógica condicional.
- **Tabela Dinâmica:** para organizar dados e facilitar análises.
- **Gráficos Dinâmicos:** para visualizar evolução do patrimônio e dividendos.
- **Validação de Dados:** para evitar entradas inválidas e garantir a qualidade da informação.
- **Formatação Condicional:** para destacar alertas ou metas alcançadas.
- **Macros (opcional):** para automatizar tarefas repetitivas, como atualização de preços ou exportação de relatórios.

---

## Estrutura da Planilha

1. **Entrada de Dados do Usuário:**

   - Valor inicial do investimento.
   - Data e valor das aplicações mensais.
   - Preço da cota do fundo (atual e histórico).
   - Taxa de dividendos mensal estimada ou histórica.
   - Outros custos (taxas administrativas, corretagem, impostos).

2. **Cálculo Automático:**

   - Total investido (somatório dos aportes).
   - Número de cotas adquiridas (com base no preço da cota).
   - Patrimônio acumulado (cotas x preço da cota atual).
   - Dividendos mensais recebidos (número de cotas x taxa de dividendos).
   - Dividendos acumulados ao longo do tempo.

3. **Visualização e Análise:**

   - Gráficos de evolução do patrimônio e dos dividendos.
   - Indicadores chave como retorno percentual, dividend yield anualizado.
   - Cenários de simulação (ex.: variação do preço da cota, mudanças na taxa de dividendos).

---

## Como Construir a Planilha Passo a Passo

1. **Configurar os Inputs:**  
   Crie áreas específicas para o usuário inserir os dados do investimento e parâmetros de simulação. Use validação para evitar erros.

2. **Implementar Fórmulas:**  
   Calcule o número de cotas compradas em cada aporte, acumule o total investido e o patrimônio ao longo do tempo. Utilize funções condicionais para atualizar dados mês a mês.

3. **Automatizar Dividendos:**  
   Calcule os dividendos mensais com base no número de cotas e taxa de dividendos, acumulando os valores para análise futura.

4. **Criar Gráficos:**  
   Visualize a evolução do patrimônio e dividendos para facilitar a interpretação dos dados.

5. **Testar e Ajustar:**  
   Verifique a planilha com diferentes cenários para garantir que os cálculos estão corretos e a experiência do usuário seja fluida.

---

## Benefícios para o Usuário

- **Decisões mais informadas:** Entenda como seus aportes, preço das cotas e dividendos impactam seu patrimônio.  
- **Facilidade e agilidade:** Automatização reduz erros e economiza tempo no cálculo manual.  
- **Visualização clara:** Gráficos e indicadores facilitam a análise do desempenho do investimento.  
- **Simulação de cenários:** Teste diferentes hipóteses antes de investir.

---

## Próximos Passos

- Expandir a planilha para incluir múltiplos fundos e diversificação.  
- Integrar dados automáticos de cotações e dividendos via APIs (com uso de VBA ou Power Query).  
- Desenvolver dashboards interativos para acompanhamento em tempo real.

---

## Conclusão

Usar o Excel como ferramenta para simulação de investimentos em fundos imobiliários é uma forma poderosa e acessível para investidores acompanharem e planejarem seus aportes. Através da combinação de funcionalidades do Excel com conceitos financeiros, é possível criar uma solução prática, eficiente e que gera valor real para o usuário.
