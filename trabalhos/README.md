Considere o seguinte dataset: 
https://github.com/gustavowillam/ML/blob/main/datasets/regression/Rent_House.csv

Implemente um algoritmo de Machine Learning utilizando Regressão Linear para realizar a predição do valor do aluguel de um determinado imóvel.

Execute as seguintes etapas da Análise Exploratório dos Dados (EDA): 

Tratar dados ausentes (NaN) 

Tratar dados categóricos. 

Implemente técnicas de Eliminação de Outliers

Seleção de Variáveis (features)

Objetivos: Encontrar o melhor modelo que minimiza o RMSE e maximiza o R2 

a) Implemente uma solução utilizando a biblioteca statsmodels 

b) Implemente uma solução utilizando a biblioteca Scikit-Learning (Classe LinearRegreession)

Ao final do treinamento realize os testes de predição para os dados: 


#X_test com variáveis categóricas

X_test = pd.DataFrame(columns = ["cidade" ,"estado", "area", "num_quartos", "num_banheiros", "garagem", "num_andares", "aceita_animais", "mobilia", "valor_condominio", "valor_iptu", "valor_seguro_incendio"])

data = {'cidade': 'Rio de Janeiro',  'estado': 'RJ',  'area': 72, 'num_quartos': 2, 'num_banheiros': 1, 'garagem': 0, 'num_andares': 7, 'aceita_animais': 1, 'mobilia': 0, 'valor_condominio': 740, 'valor_iptu': 85, 'valor_seguro_incendio': 25}

X_test = X_test.append(data, ignore_index = True)

data = {'cidade': 'Sao Paulo',  'estado': 'SP',  'area': 72, 'num_quartos': 2, 'num_banheiros': 1, 'garagem': 0, 'num_andares': 7, 'aceita_animais': 1, 'mobilia': 0, 
        'valor_condominio': 740, 'valor_iptu': 85, 'valor_seguro_incendio': 25}

X_test = X_test.append(data, ignore_index = True)

print(X_test)

#X_test com variáveis numéricas

#cidade = {'Sao Paulo':1, 'Porto Alegre':2, 'Rio De Janeiro':3, 'Campinas':4, 'Belo Horizonte':5}
#estado = {'SP':1, 'RS':2, 'RJ':3, 'MG':5}

X_test = pd.DataFrame(columns = ["cidade" ,"estado", "area", "num_quartos", "num_banheiros", "garagem", "num_andares", "aceita_animais", "mobilia", "valor_condominio", "valor_iptu", "valor_seguro_incendio"])

data = {'cidade': 3,  'estado': 3,  'area': 72, 'num_quartos': 2, 'num_banheiros': 1, 'garagem': 0, 'num_andares': 7, 'aceita_animais': 1, 'mobilia': 0, 
        'valor_condominio': 740, 'valor_iptu': 85, 'valor_seguro_incendio': 25}

X_test = X_test.append(data, ignore_index = True)

data = {'cidade': 1,  'estado': 1,  'area': 72, 'num_quartos': 2, 'num_banheiros': 1, 'garagem': 0, 'num_andares': 7, 'aceita_animais': 1, 'mobilia': 0, 
        'valor_condominio': 740, 'valor_iptu': 85, 'valor_seguro_incendio': 25}

X_test = X_test.append(data, ignore_index = True)

print(X_test)
