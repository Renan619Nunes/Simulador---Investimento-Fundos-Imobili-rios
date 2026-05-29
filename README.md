# Simulador---Investimento-Fundos-Imobili-rios
Este projeto apresenta um modelo estruturado de simulação financeira para auxiliar no planejamento e na alocação automatizada de ativos de Fundos Imobiliários. Todas as regras de negócio, tabelas de perfil e fórmulas matemáticas estão contidas no arquivo.

**Estrutura do Arquivo**
O arquivo esta dividido em duas abas principais que operam em conjunto:
     **1.**  Planilha1 (Painel de Simulação): Contém os blocos de configurações de renda, cálculo de investimento mensal, projeção de cenários futuros e o demonstrativo da carteira sugerida.
     **2.** Planilha2 (Matriz de Perfis): Base de dados oculta ou de suporte que define os percentuais de alocação de ativos com base no nível de risco selecionado.

**Instruções de Uso**
Para operar o simulador corretamente, siga as etapas descritas abaixo no preenchimento do painel principal (Planilha1):
   
**Passo 01 -** No bloco denominado CONFIGURACOES, insira os seus dados de base financeira:
      **- Salario:** Digite a sua renda mensal atual.
      **- Rendimento Carteira:** Defina a taxa percentual de rendimento estimada para a sua carteira base.
      **- Sugestão Investimento:** Opcionalmente, utilize este campo para registrar o valor ideal que gostaria de poupar de acordo com o seu planejamento financeiro pessoal.

**Passo 02 -** No bloco INVESTIMENTO MENSAL, configure as variáveis de simulação que alimentarão o motor de juros compostos:
      **- Investimento/Mes:** Defina a quantia em dinheiro que sera efetivamente aportada todos os meses.
      **- Anos:** Defina o horizonte de tempo padrao da simulacao corrente.
      **- Rendimento Mensal:** Ajuste a taxa de juros esperada para os ativos de Fundos Imobiliários.
A planilha exibira imediatamente nas linhas inferiores os resultados consolidados para o periodo escolhido.

O bloco CENÁRIOS FUTUROS dispensa edições. Ele calcula de forma automática o crescimento do patrimônio e o respectivo recebimento de dividendos em quatro marcos temporais pré-definidos: 02 anos, 05 anos, 10 anos e 20 anos. Utilize esta área para avaliar o efeito "bola de neve" dos dividendos reinvestidos a longo prazo.

**Passo 03 -** No bloco PERFIL, insira a classificação do seu perfil de investidor. O simulador aceita os seguintes parâmetros:
     **CONSERVADOR;**
     **MODERADO:**
     **AGRESSIVO**
Ao atualizar o Perfil e o campo Valor investido/mês, a tabela inferior executará uma busca na base de dados da Planilha2 para exibir o Percentual Sugerido e os Valores exatos em dinheiro que devem ser distribuídos por categoria.
