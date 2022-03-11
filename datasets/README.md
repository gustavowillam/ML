# Dataset Breast Cancer Wisconsin

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

# Dataset Country Clusters

Dataset utilizado para Aprendizado Não-Supervisionado

Atributos:

-Country

-Latitude

-Longitude

-Language

# Dataset Dados Compra

Dataset utilizado para demonstrar EDA e Pré-processamento

Atributos: 

-Pais

-Idade

-Salario

-Compra




