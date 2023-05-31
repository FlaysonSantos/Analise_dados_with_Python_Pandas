# Bem vindo ao projeto Api_Flask!

Para este projeto o desafio final envolve a entrega de uma API desenvolvida no framework Flask utilizando a Plataforma COLAB. O Objetivo principal está relacionado com a leitura de uma planilha de dados no formato JSON utilizando uma API no ambiente de desenvolvimento colaborativo COLAB.


# Instale biblioteca flask no Colab

!pip install flask

## Criando o dataset em json salvando na variavel "d"

d = {

"Numero":1,

"Name":"Mahesh",

"Age":"25",

"City":"Bangalore",

"Country":"India"

},{

"Numero":2,

"Name":"Alex",

"Age":"26",

"City":"London",

"Country":"UK"

},{

"Numero":3,

"Name":"David",

"Age":"27",

"City":"Sao Francisco",

"Country":"USA"

},{

"Numero":4,

"Name":"John",

"Age":"28",

"City":"Toronto",

"Country":"Canada"

},{

"Numero":5,

"Name":"Chris",

"Age":"29",

"City":"Paris",

"Country":"France"

}

## Estrutura do app Flask

app = Flask(__name__)

@app.route("/")

def  inicio():

return "Ola Dev"

if  __name__ == "__main__":

app.run(debug=True)

## Resultado 

No final sera gerado um arquivo em csv com nome de "dados.csv" criado com dados do json
