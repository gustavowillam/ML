# Dataset Breast Cancer Wisconsin 

Fonte: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

As características são computadas a partir de uma imagem digitalizada de um aspirado por agulha fina (PAAF) de uma massa mamária. Eles descrevem características dos núcleos celulares presentes na imagem. Algumas das imagens podem ser encontradas em http://www.cs.wisc.edu/~street/images/

Informações do atributo:

1) Número de identificação

2) Diagnóstico (M = maligno, B = benigno)

(3-32) Dez características de valor real são computadas para cada núcleo de célula:

a) raio (média das distâncias do centro aos pontos do perímetro)

b) textura (desvio padrão dos valores de escala de cinza)

c) perímetro

d) área

e) suavidade (variação local nos comprimentos dos raios)

f) compacidade (perímetro^2 / área - 1,0)

g) concavidade (gravidade das porções côncavas do contorno)

h) pontos côncavos (número de porções côncavas do contorno)

e) simetria

j) dimensão fractal ("aproximação do litoral" - 1)

A média, desvio padrão e "pior" ou maior (média dos três maiores valores) desses recursos foram calculados para cada imagem, resultando em 30 recursos. Por exemplo, o campo 3 é o Raio Médio, o campo 13 é o Raio SE, o campo 23 é o Pior Raio.

Todos os valores de recursos são recodificados com quatro dígitos significativos.

Valores de atributo ausentes: nenhum
Distribuição de classes: 357 benignos, 212 malignos

Y - Variável de previsão (Diagnostico)
• Diagnostico: Maligno (M) ou Benigno (B) (binário: "1", significa "Maligno", "0" significa "Benigno")

a) Creators: 

	Dr. William H. Wolberg, General Surgery Dept., University of
	Wisconsin,  Clinical Sciences Center, Madison, WI 53792
	wolberg@eagle.surgery.wisc.edu

	W. Nick Street, Computer Sciences Dept., University of
	Wisconsin, 1210 West Dayton St., Madison, WI 53706
	street@cs.wisc.edu  608-262-6619

	Olvi L. Mangasarian, Computer Sciences Dept., University of
	Wisconsin, 1210 West Dayton St., Madison, WI 53706
	olvi@cs.wisc.edu 

# Dataset Dados Compra

Dataset utilizado para demonstrar EDA e Pré-processamento

Atributos: 

-Pais

-Idade

-Salario

-Compra


# Dataset Framingham 

Fonte: https://www.kaggle.com/navink25/framingham

Descrição do Dataset 

A Organização Mundial da Saúde estimou que 12 milhões de mortes ocorrem em todo o mundo, todos os anos, devido a doenças cardíacas. Metade das mortes nos Estados Unidos e em outros países desenvolvidos são devidas a doenças cardiovasculares. O prognóstico precoce de doenças cardiovasculares pode auxiliar na tomada de decisões sobre mudanças de estilo de vida em pacientes de alto risco e, por sua vez, reduzir as complicações. Esta pesquisa pretende identificar os fatores de risco mais relevantes de doenças cardíacas, bem como prever o risco geral usando regressão logística
O conjunto de dados está disponível publicamente no site Kaggle e é de um estudo cardiovascular em andamento em moradores da cidade de Framingham, Massachusetts. O objetivo da classificação é prever se o paciente tem risco de contrair doença coronariana futura (DCF). O conjunto de dados fornece as informações dos pacientes. Inclui mais de 4.000 registros e 15 atributos.

Variáveis

Cada atributo é um fator de risco potencial. Existem fatores de risco demográficos, comportamentais e médicos.

a)	Demográfico:

•	Sexo: masculino ou feminino (Nominal)

•	Idade: Idade do paciente;(Contínuo - Embora as idades registradas tenham sido truncadas para números inteiros, o conceito de idade é contínuo)

•	Educacao: Grau de Instrução da pessoa. 

b)	Comportamental

•	Fumante atual: se o paciente é fumante atual ou não (Nominal)

•	Cigarros por dia: o número de cigarros que a pessoa fumou em média em um dia. (pode ser considerado contínuo, pois pode-se fumar qualquer número de cigarros, até meio cigarro.)

c)	Histórico médico

•	BP Meds: se o paciente estava ou não sob medicação para pressão arterial (Nominal)

•	AVC Prevalente: se o paciente já teve ou não um AVC (Nominal)

•	Hip predominante: se o paciente era ou não hipertenso (Nominal)

•	Diabetes: se o paciente tinha ou não diabetes (Nominal)

d)	Médico (atual)

•	Tot_Col: nível de colesterol total (Contínuo)

•	Sys_BP: pressão arterial sistólica (contínua)

•	Dia_BP: pressão arterial diastólica (Contínua)

•	IMC: Índice de Massa Corporal (Contínuo)

•	Freq_Cardiaca: frequência cardíaca (Contínua - Na pesquisa médica, variáveis como a frequência cardíaca, embora de fato discretas, são consideradas contínuas devido ao grande número de valores possíveis.)

•	Glicose: nível de glicose (Contínuo)

Y - Variável de previsão (alvo desejado) 

• DCF: Risco de doença cardíaca coronária CHD (binário: "1", significa "Sim", "0" significa "Não")


# Dataset: Insurance_claims 

Fonte: https://www.kaggle.com/roshansharma/insurance-claim

Descrição do Dataset https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4954928053318020/1058911316420443/167703932442645/latest.html

Reclamações de Seguros - Detecção de Fraude Caso de negócio:

A fraude de seguros é um grande problema na indústria.

É difícil identificar alegações de fraude.

A IHS está em uma posição única para ajudar o setor de Seguro Automóvel com esse problema.


# Dataset: Marketing_Analysis 

Dataset utilizado para EDA e Pré-Processamento de Dados 

Atributos: 

• age  (idade)

• salary (salário) 

• balance (saldo)        

• marital (estado civil)       

• targeted: determinado cliente antes de segmentado ou não

• default (yes/no)   

• housing  (yes/no)     

• loan  Tipos de empréstimo: empréstimos ou empréstimos para habitação        

• contact  (contato)       

• day      (dia)     

• month    mês de contato

• duration (duração)     

• campaign (campanha)     

• pdays    (total de dias da campanha)     

• previous (anterior)     

• poutcome: resultado do contato anterior

• job      (trabalho)      

• education (grau de instrução)     

Variável Y:  response  (Sim/Nao) - Resposta do cliente após a chamada - Usuário faria uma campanha de Marketing (sim ou não)      


# Dataset: Telecom Users 

Fonte: https://www.kaggle.com/radmirzosimov/telecom-users-dataset

Descrição do Dataset

Qualquer negócio quer maximizar o número de clientes. Para atingir esse objetivo, é importante não apenas tentar atrair novos, mas também reter os já existentes. Reter um cliente custará à empresa menos do que atrair um novo. Além disso, um novo cliente pode estar pouco interessado em serviços de negócios e será difícil trabalhar com ele, enquanto clientes antigos já possuem os dados necessários sobre a interação com o serviço.

Assim, prevendo o churn, podemos reagir a tempo e tentar manter o cliente que quer sair. Com base nos dados sobre os serviços que o cliente utiliza, podemos fazer-lhe uma oferta especial, tentando alterar a sua decisão de sair da operadora. Isso tornará a tarefa de retenção mais fácil de implementar do que a tarefa de atrair novos usuários, sobre a qual ainda não sabemos nada.

Você recebe um conjunto de dados de uma empresa de telecomunicações. Os dados contêm informações sobre quase seis mil usuários, suas características demográficas, os serviços que utilizam, o tempo de uso dos serviços da operadora, a forma de pagamento e o valor do pagamento.

A tarefa é analisar os dados e prever o churn de usuários (para identificar as pessoas que vão ou não renovar o contrato). O trabalho deve incluir os seguintes itens obrigatórios:

Descrição dos dados (com cálculo das estatísticas básicas);
Pesquisa de dependências e formulação de hipóteses;
Construção de modelos de previsão de saída (com justificação para a escolha de um determinado modelo) com base em hipóteses testadas e relações identificadas;
Comparação da qualidade dos modelos obtidos.


Atributos: 

customerID - ID do cliente

gender - sexo do cliente (masculino/feminino)

SeniorCitizen - o cliente está aposentado (1, 0)

Partner - o cliente é casado (Sim, Não)

tenure - há quantos meses uma pessoa é cliente da empresa

PhoneService - o serviço telefônico está conectado (Sim, Não)

MultipleLines - são várias linhas telefônicas conectadas (Sim, Não, Sem serviço telefônico)

InternetService - provedor de serviços de Internet do cliente (DSL, Fibra óptica, Não)

OnlineSecurity - o serviço de segurança online está conectado (Sim, Não, Sem serviço de internet)

OnlineBackup - o serviço de backup online está ativado (Sim, Não, Sem serviço de internet)

DeviceProtection - o cliente tem seguro do equipamento (Sim, Não, Sem serviço de internet)

TechSupport - o serviço de suporte técnico está conectado (Sim, Não, Sem serviço de internet)

StreamingTV - o serviço de streaming de TV está conectado (Sim, Não, Sem serviço de internet)

StreamingMovies - o serviço de streaming de cinema está ativado (Sim, Não, Sem serviço de internet)

Contract - tipo de contrato do cliente (Mês a mês, Um ano, Dois anos)

PaperlessBilling - se o cliente usa faturamento sem papel (Sim, Não)

PaymentMethod - método de pagamento (cheque eletrônico, cheque enviado, transferência bancária (automática), cartão de crédito (automático))

MonthlyCharges - pagamento mensal atual

TotalCharges - o valor total que o cliente pagou pelos serviços durante todo o tempo

Variável Y: Churn - se houve churn (Sim ou Não)


# Dataset: Red Wine Quality 

Fonte: https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009

Descrição do Dataset


Input variables (based on physicochemical tests):

1 - fixed acidity

2 - volatile acidity

3 - citric acid

4 - residual sugar

5 - chlorides

6 - free sulfur dioxide

7 - total sulfur dioxide

8 - density

9 - pH

10 - sulphates

11 - alcohol

Output variable (based on sensory data):

12 - quality (score between 0 and 10)


# Dataset: Iris 

Fonte: https://www.kaggle.com/datasets/arshid/iris-flower-dataset

O conjunto de dados de flores de íris é um conjunto de dados multivariado introduzido pelo estatístico e biólogo britânico Ronald Fisher em seu artigo de 1936 O uso de medições múltiplas em problemas taxonômicos. Às vezes é chamado de conjunto de dados de íris de Anderson porque Edgar Anderson coletou os dados para quantificar a variação morfológica das flores de íris de três espécies relacionadas. O conjunto de dados consiste em 50 amostras de cada uma das três espécies de Iris (Iris Setosa, Iris virginica e Iris versicolor). Quatro características foram medidas de cada amostra: o comprimento e a largura das sépalas e pétalas, em centímetros.

Este conjunto de dados tornou-se um caso de teste típico para muitas técnicas de classificação estatística em aprendizado de máquina. 

Atributos 

O conjunto de dados contém um conjunto de 150 registros em 5 atributos: 

Petal_Length: Comprimento da Pétala 

Petal_Width: Largura da Pétala

Sepal_Length: Comprimento da Sépala

Sepal_Width: Largura da Sépala

Y: Classe (Espécie).

