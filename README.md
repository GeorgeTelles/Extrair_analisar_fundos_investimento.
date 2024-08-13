<div>
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_clara.png" alt="logo clara" width="300" style="display: inline-block; vertical-align: top; margin-right: 10px;">
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_dark.png" alt="logo dark" width="300" style="display: inline-block; vertical-align: top;">
</div>


# **Extrair e analisar dados de fundos de investimento**

Esse algoritmo em Python tem como objetivo obter dados de fundos de investimento direto da fonte: o portal de dados da CVM.

Vou processar estes dados para posteriormente analisá-los.

Quero responder algumas perguntas importantes, como:

1. Quais fundos do Brasil tem o maior PL (patrimônio líquido)?
2. Quais fundos tem mais cotistas?
3. Quais os 10 fundos que teviveram as maiores altas?
4. Quais os 10 fundos que teviveram as maiores baixas?

Ferramentas importantes para ajudar a analisar e comparar fundos de investimento

Portal de dados Anbima
https://data.anbima.com.br/

Mais Retorno
https://maisretorno.com/comparacao-fundos

1. Identificar os sites que farão parte da busca (cotas e cadastral)
2. Iniciar extração dos dados
3. Obter e tratar os dados
4. Juntar os dois e começar as análises
5. Responder questionamentos do projeto

### Qual o processo?

Vou começar a extração explorando as páginas da CVM que tem as informações que serão extraídas.

Para dados de desempenho dos fundos:

https://dados.cvm.gov.br/dados/FI/DOC/INF_DIARIO/DADOS/

Para dados cadastrais dos fundos:

http://dados.cvm.gov.br/dados/FI/CAD/DADOS/

dados abertos da CVM: 

https://dados.cvm.gov.br/
