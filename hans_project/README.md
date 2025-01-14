# Projeto `Análise de dados da hanseníase: uma abordagem preditiva para a saúde pública`

# Project `Data analysis of leprosy: a predictive approach for public health`

# Apresentação

O presente projeto foi originado no contexto das atividades da disciplina de pós-graduação [*Ciência e Visualização de Dados em Saúde*](https://github.com/datasci4health/home), oferecida no primeiro semestre de 2023, na Unicamp, pelos membros:

> |Nome  | RA | Especialização|
> |--|--|--|
> | Alexsandro Ferreira de Barros Júnior  | 233768  | Computação - Líder Github - [Conta GitHub](https://github.com/alexbjr) |
> | Giovanna Gennari Jungklaus  | 198010  | Computação - [Conta GitHub](https://github.com/gigennari)|
> | José Ernesto Stelzer Monar  | 139553  | Computação - [Conta GitHub](https://github.com/stelzer-monar-ifood)|
> | Maria Clara Castro Higino de Sousa  | 243237  | Computação - [Conta GitHub](https://github.com/mc-castro)|
> | Miriam Reyes Ortiz  | 265762  | Saúde  |


# Descrição Resumida do Projeto
> A hanseníase é uma doença infecciosa crônica e transmissível que afeta principalmente a pele e o sistema nervoso periférico. A doença pode afetar pessoas de qualquer sexo ou faixa etária, e sua progressão ocorre de forma lenta e progressiva. Se não for tratada na fase inicial, pode levar a incapacidades físicas. Atualmente, a hanseníase é classificada como uma doença negligenciada e continua sendo um problema de saúde pública em muitos países, incluindo o Brasil. Embora a tendência de novos casos tenha diminuído ao longo do tempo devido à introdução da terapia multidrogas, o Brasil ocupa atualmente o segundo lugar em termos de prevalência no mundo.
>
> O esquema de tratamento da terapia multidrogas (número de doses e tempo) depende da classificação operacional da doença, com base no número de lesões na pele. Os casos são classificados como paucibacilares (até cinco lesões) ou multibacilares (seis ou mais lesões de pele), com uma duração de tratamento de 6 a 12 meses, respectivamente. Apesar dos avanços no tratamento para a cura da doença, o abandono da terapia multidrogas ainda representa um obstáculo importante para o controle efetivo e a eliminação da hanseníase. Por exemplo, os casos de abandono podem resultar em curas imcompletas, levando a uma maior progressão da doença, o que pode prolongar o tempo de tratamento e aumentar os costos para o sistema de saúde, além de manter fontes persistentes de infecção na área geográfica. 
> 
> Evidências sugerem que existem fatores associados ao risco de abandono do tratamento da haneníase. A interrupção do tratamento pode ser influenciada por características pessoais, socioeconômicas e fatores clínicos ou médicos. Nesse contexto, este projeto tem como objetivo analisar os casos novos de hanseníase no período de 2009 a 2019, a fim de determinar padrões ou relações entre as características dos pacientes e da doença com os casos de cura e abandono do tratamento. Além disso, pretende-se identificar diferentes padrões espaciais de ocorrência e abandono, levando em consideração o índice de desenvolvimento humano. Para isso, serão utilizadas técnicas de machine learning para identificar as variáveis mais relevantes e sua relação com os casos de cura e abandono do tratamento.
>
> Espera-se que os resultados deste projeto possam ajudar na identificação de fatores que represemtem barreiras no tratamento, permitindo a alocação adequada de recursos em regiões de maior vulnerabilidade. Além disso, a análise desses dados pode fornecer insights importantes sobre a doença, contribuindo para a prevenção e o controle efetivo da hanseníase em nível nacional.
> 
> [Vídeo de apresentação](https://drive.google.com/file/d/1LdYcPP0i0cjiHvt-HNTh64a2jiKPNRNR/view?usp=sharing)

# Perguntas de Pesquisa
> Quais variáveis clínicas e epidemiológicas estão associadas ao tempo de cura dos pacientes com hanseníase?
> 
> Quais são as variáveis preditoras do tipo de saída por abandono do tratamento?
> 
> Quais são as variáveis preditoras associadas ao grau de incapacidade física?
> 
> Existe uma relação espacial entre o índice de desenvolvimento humano e a incidência (número de casos novos), os casos de abandono do tratamento e a gravidade da doença?
> 
> Como as percepções obtidas a partir da análise de dados podem ser utilizadas para melhorar o planejamento financeiro dos sistemas de saúde em relação ao tratamento da hanseníase?*
> 
> Qual é o desempenho dos modelos de machine learning na previsão do tempo de cura dos pacientes com hanseníase?

# Bases de Dados
> |Fonte | Descrição|
> |--|--|
> |[Sistema de Informação de Agravos de Notificação (SINAN)](http://indicadoreshanseniase.aids.gov.br) |Base mantida pelo Departamento de Doenças de Condições Crônicas e Infecções Sexualmente Transmissíveis - DCCI, do Ministério da Saúde. É uma centralização de todos os casos de hanseníase ocorridos no Brasil assim como diversas informações associadas a cada caso por paciente.| 

# Metodologia
> Será realizada uma análise exploratória de dados para identificar e selecionar características que mostrem correlação com os desfechos da doença. A partir desses dados, será utilizado um modelo de aprendizado de máquina que realize previsões quanto ao tempo de cura dos pacientes analisados. Para concluir o estudo, análises estatísticas serão realizadas para testar as hipóteses formuladas. 

# Ferramentas
> O projeto será realizado em Python e serão utilizadas a seguintes ferramentas e bibliotecas:
>
> |Ferramenta/Biblioteca | Descrição|
> |--|--|
> |[Pandas](https://pandas.pydata.org/) |Biblioteca para manipulação e análise de dados| 
> |[Numpy](https://numpy.org/) |Biblioteca para cálculos matemáticos e estatísticos| 
> |[Scikit-learn](https://scikit-learn.org/stable/) |Biblioteca para modelagem preditiva e aprendizado de máquina| 
> |[Matplotlib](https://matplotlib.org/) e [Seaborn](https://seaborn.pydata.org/) |Bibliotecas para visualização de dados| 
> |[Jupyter Notebook](https://jupyter.org/) |Ferramenta para desenvolvimento e apresentação de notebooks interativoss| 

# Cronograma
> |Etapas | Sem 1 | Sem 2| Sem 3| Sem 4| Sem 5| Sem 6| Sem 7| Sem 8| Sem 9| Sem 10|
> |--|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
> | Definição do escopo do projeto e planejamento da metodologia  | X |  |  |  |  |  |  |  |  |  |
> | Pré-processamento dos dados  |  | X |  |  |  |  |  |  |  |  |
> | Análise exploratória|  |  | X | X |  |  |  |  |  |  |
> | Entrega 2  |  |  |  | X |  |  |  |  |  |  |
> | Modelagem preditiva e avaliação dos modelos  |  |  |  |  | X | X | X |  |  |  |
> | Avaliação do modelo  |  |  |  |  |  |  |  | X |  |  |
> | Elaboração do relatório  |  |  |  |  |  |  |  |  | X |  |
> | Entrega final e apresentação  |  |  |  |  |  |  |  |  |  | X |
