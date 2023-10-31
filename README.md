# Automacao-De-Processos
 Neste projeto eu estarei fazendo um processo de automação que analisa os indicadores de diversas lojas, a análise irá comparar as vendas diárias e anuais de cada loja e irá ranquear qual loja teve a melhor vendo diária e melhor venda anual. Através disso, as análises serão enviadas por email para diferentes gerentes fictícios.

Passo a passo:
 * Dentro do projeto eu utilizei o Python e algumas das suas bibliotecas, dentro dele eu puxei a base de dados de todas as lojas com suas vendas diárias e anual
 * Puxei os indíces de vendas de acordo com cada loja e peguei a data mais recente na base de dados para conseguir fazer o cálculo dos indicadores
 * Criei um loop para criar uma pasta com uma planilha excel dos indíces de cada loja respectiva
 * Defini metas para todas as lojas, sendo elas: faturamento diário e anual, quantidade de produtos vendidos diário e anual, ticket médio diário e anual
 * Calculei todos os indíces da meta
 * Enviei email para os respectivos gerentes com todos os cálculos feitos e mostrando se bateu ou não a meta
 * Criei um rank mostrando a loja que mais faturou e a que menos faturou, enviei essas informações para uma diretoria fictícia
