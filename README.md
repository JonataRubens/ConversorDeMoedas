# ConversorDeMoedas
 
Este é um código em Java que tenta converter um valor de uma moeda para outra usando uma API de taxas de câmbio.

Pacote e Importações:
O código está no pacote Converter.
Importa várias classes relacionadas a manipulação de URL, HTTP e JSON.

Variáveis e Constantes:
API_URL: Constante que armazena a URL da API de taxas de câmbio.

Método main:
É o ponto de entrada do programa.
Define o valor a ser convertido (amount), a moeda de origem (baseCurrency) e a moeda de destino (targetCurrency).
Chama o método getExchangeRates() para obter as taxas de câmbio da API.
Calcula e imprime o valor convertido.

Método getExchangeRates():
Este método é responsável por fazer uma requisição HTTP para a API de taxas de câmbio e obter a resposta em formato JSON.
Usa a classe HttpClient para fazer a requisição e a classe HttpResponse para receber a resposta.
Retorna um objeto JSONObject que contém as taxas de câmbio.

Tratamento de Exceções:
O código usa blocos try-catch para lidar com possíveis exceções que podem ocorrer durante a execução, como erros de E/S (IOException) ou erros ao fazer a requisição HTTP (InterruptedException, URISyntaxException).

Comentários:
Existem comentários explicativos ao longo do código para ajudar a entender o que cada parte faz.

Observações:
No entanto, há um comentário indicando que o código não está funcionando e que precisa ser corrigido.
