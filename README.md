# Conversor de Moedas

Este projeto é um conversor de moedas que utiliza a API ExchangeRate para obter taxas de câmbio em tempo real. O programa é desenvolvido em Java e permite a conversão de diversas moedas, como dólar, euro, real brasileiro, entre outras.
![image](https://github.com/user-attachments/assets/97f87e84-f9f0-4f3f-b0c7-27bf863e1367)

## Requisitos

- Java 8 ou superior
- Chave de API da ExchangeRate (obtenha em: [https://www.exchangerate-api.com/](https://www.exchangerate-api.com/))

## Como usar

1. Clone o repositório:

   ```bash
  Estrutura do Código
API_KEY: Chave da API necessária para fazer requisições à ExchangeRate API.
API_URL: URL da API para obter as taxas de câmbio.
Scanner: Objeto utilizado para capturar as entradas do usuário.
obterTaxaCambio: Função que faz a requisição à API e retorna a taxa de câmbio entre duas moedas.
converterMoeda: Realiza a conversão do valor fornecido pelo usuário com base na taxa obtida.
Funcionalidades
Conversão entre múltiplas moedas.
Taxas de câmbio obtidas em tempo real.
Menu interativo para o usuário escolher as opções de conversão.
Melhorias Futuras
Adicionar mais moedas.
Melhorar o tratamento de exceções.
Implementar suporte para moedas criptográficas.
