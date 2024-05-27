# Classificação de Imagens CIFAR-10

Esse repositório tem como objetivo classificar imagens da base de dados CIFAR-10. Para isso, foi implementado uma CNN para realizar as previsões e uma API em Python para poder receber as imagens e retornar os resultados. A seguir, será apresentado 3 casos de testes com 3 imagens diferentes.

# Testes

A primeira imagem utilizada para o teste foi a de um avião, apresentada a seguir:

![alt text](airplane.jpg)

Para interagir com a API foi utilizada a ferramenta Postman. Foi utilizado o método POST e a imagem foi enviada através do body, com a key "file" e o value "airplane.jpg". Podemos ver que a resposta da requisição foi executada com sucesso e o modelo acertou a previsão:

![alt text](<image (13).png>)

Log da API no Google Colab:

![alt text](<image (9).png>)

A segunda imagem utilizada para o teste foi a de um caminhão:

![alt text](truck.jpg)

Requisição e resposta no POSTMAN:

![alt text](<image (8).png>)

Log do Google Colab:

![alt text](<image (10).png>)

A terceira e última imagem foi a do seguinte cachorro:

![alt text](dog.jpg)

Requisição e resposta no POSTMAN:

![alt text](<image (11).png>)

Log do Google Colab:

![alt text](<image (12).png>)

Portanto, podemos concluir que os testes foram executados com sucesso e o modelo fez as previsões corretamente.