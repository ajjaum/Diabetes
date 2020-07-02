# Projeto `Análise de Dados sobre Diabetes no Brasil - VIGITEL`
# Project `Data Analysis on Diabetes in Brazil - VIGITEL`

# Descrição Resumida do Projeto
~~~
<Descreva resumidamente o que fará o projeto. O resumo idealmente deve: apresentar o contexto; indicar o problema; apresentar a sua solução para o problema; indicar porque a sua solução é melhor do que os esforços atuais (não obrigatório); concluir com os resultados alcançados.>
~~~

# Abstract in English
~~~
<English version of the abstract.>
~~~

# Equipe
* `<nome completo>` - `<RA>`

# Vídeo do Projeto
`<coloque um link para o vídeo apresentado o projeto.>`

# Introdução e Motivação
~~~
<Descrição do tema do projeto, incluindo motivação, contexto gerador e caracterização do problema. A introdução também pode apresentar iniciativas correlatas para lidar com o problema (não obrigatório) e deve introduzir de forma mais detalhada que o resumo a solução proposta e resultados alcançados. Aqui também são apresentadas as seções do projeto.>
~~~

## Perguntas de Pesquisa
~~~
Com base nos dados do Vigitel de 2006 a 2019 qual a prevalência de diabetes em amostras da população brasileira e quais fatores podem estar associados a esta doença?
~~~

## Objetivos do projeto
~~~
Avaliar a prevalência de diabetes em brasileiros e verificar se há associação com outros fatores da pesquisa Vigitel de 2006 a 2019.
~~~

# Recursos e Métodos

## Bases de Dados

Foi utilizado, exclusivamente, os dados disponíveis no portal do Departamento de Informação e Análise Epidemiológica da base de dados do [VIGITEL](http://svs.aids.gov.br/download/Vigitel/). Foram utilizados os dados anos de 2007 a 2013 e 2015 a 2019, para avaliar a evolução da prevalência de diabetes ao longo dos anos da pesquisa e suas associações. O uso das tabelas foram orientadas pelo [Dicionário](http://svs.aids.gov.br/download/Vigitel/Dicionario-de-dados-Vigitel.xls) disponibilizado no [VIGITEL](http://svs.aids.gov.br/download/Vigitel/).  

Base de Dados | Endereço na Web | Resumo descritivo e uso
----- | ----- | -----
Base 01 | http://svs.aids.gov.br/download/Vigitel/Vigitel-2007-peso-rake.xls | `Pesquisa VIGITEL do ano de 2007`
Base 02 | http://svs.aids.gov.br/download/Vigitel/Vigitel-2008-peso-rake.xls | `Pesquisa VIGITEL do ano de 2008`
Base 03 | http://svs.aids.gov.br/download/Vigitel/Vigitel-2009-peso-rake.xls | `Pesquisa VIGITEL do ano de 2009`
Base 04 | http://svs.aids.gov.br/download/Vigitel/Vigitel-2010-peso-rake.xls | `Pesquisa VIGITEL do ano de 2010`
Base 05 | http://svs.aids.gov.br/download/Vigitel/Vigitel-2011-peso-rake.xls | `Pesquisa VIGITEL do ano de 2011`
Base 06 | http://svs.aids.gov.br/download/Vigitel/Vigitel-2012-peso-rake.xls | `Pesquisa VIGITEL do ano de 2012`
Base 07 | http://svs.aids.gov.br/download/Vigitel/Vigitel-2013-peso-rake.xls | `Pesquisa VIGITEL do ano de 2014`
Base 10 | http://svs.aids.gov.br/download/Vigitel/Vigitel-2014-peso-rake.xls | `Pesquisa VIGITEL do ano de 2014`
Base 11 | http://svs.aids.gov.br/download/Vigitel/Vigitel-2015-peso-rake.xls | `Pesquisa VIGITEL do ano de 2015`
Base 12 | http://svs.aids.gov.br/download/Vigitel/Vigitel-2016-peso-rake.xls | `Pesquisa VIGITEL do ano de 2016`
Base 13 | http://svs.aids.gov.br/download/Vigitel/Vigitel-2017-peso-rake.xls | `Pesquisa VIGITEL do ano de 2017`
Base 14 | http://svs.aids.gov.br/download/Vigitel/Vigitel-2018-peso-rake.xls | `Pesquisa VIGITEL do ano de 2018`
Base 15 | http://svs.aids.gov.br/download/Vigitel/Vigitel-2019-peso-rake.xls | `Pesquisa VIGITEL do ano de 2019`

## Ferramentas

`<Elencar ferramentas utilizadas no projeto preferencialmente no formato da tabela a seguir.>`
Ferramenta | Endereço na Web | Resumo descritivo e uso
----- | ----- | -----
Ferramenta 1 | http://ferramenta1.org/ | `<Descrição da Ferramenta 1 e para que ela foi usada no projeto.>`
Ferramenta 2 | http://ferramenta2.org/ | `<Descrição da Ferramenta 2 e para que ela foi usada no projeto.>`

# Metodologia
~~~
<Abordagem/metodologia adotada, incluindo especificação de quais técnicas foram exploradas, tais como: aprendizagem de máquina, análise de redes, análise estatística, ou integração de uma ou mais técnicas.>
~~~

## Detalhamento do Projeto
~~~
<Apresente aqui detalhes da análise. Nesta seção ou na seção de Resultados podem aparecer destaques de código como indicado a seguir. Note que foi usada uma técnica de highlight de código, que envolve colocar o nome da linguagem na abertura de um trecho com `~~~`, tal como `~~~python`.

Os destaques de código devem ser trechos pequenos de poucas linhas, que estejam diretamente ligados a alguma explicação. Não utilize trechos extensos de código. Se algum código funcionar online (tal como um Jupyter Notebook), aqui pode haver links. No caso do Jupyter, preferencialmente para o Binder abrindo diretamente o notebook em questão.>
~~~

~~~python
df = pd.read_excel("/content/drive/My Drive/Colab Notebooks/dataset.xlsx");
sns.set(color_codes=True);
sns.distplot(df.Hemoglobin);
plt.show();
~~~

## Evolução do Projeto
~~~
<Relate a evolução do projeto: possíveis problemas enfrentados e possíveis mudanças de trajetória. Relatar o processo para se alcançar os resultados é tão importante quanto os resultados.>
~~~

# Resultados e Discussão
~~~
<Apresente os resultados da forma mais rica possível, com gráficos e tabelas. Mesmo que o seu código rode online em um notebook, copie para esta parte a figura estática. A referência a código e links para execução online pode ser feita aqui ou na seção de detalhamento do projeto (o que for mais pertinente).

A discussão dos resultados também pode ser feita aqui na medida em que os resultados são apresentados ou em seção independente. Aspectos importantes a serem discutidos: É possível tirar conclusões dos resultados? Quais? Há indicações de direções para estudo? São necessários trabalhos mais profundos?>
~~~

# Conclusões
~~~
<Apresente aqui as conclusões finais do trabalho e as lições aprendidas.>
~~~

# Trabalhos Futuros
~~~
<Indique trabalhos futuros a partir do ponto alcançado.>
~~~
