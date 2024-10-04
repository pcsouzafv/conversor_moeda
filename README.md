# Conversor de Moedas

Este projeto é um conversor de moedas que utiliza a API ExchangeRate para obter taxas de câmbio em tempo real. O programa é desenvolvido em Java e permite a conversão de diversas moedas, como dólar, euro, real brasileiro, entre outras.
![image](https://github.com/user-attachments/assets/97f87e84-f9f0-4f3f-b0c7-27bf863e1367)

Aqui está uma versão mais criativa e detalhada do `README.md` para o seu projeto de **Conversor de Moedas**:

---

# 🌍💱 Conversor de Moedas - Seu Guia Financeiro Global! 💸

**Bem-vindo ao Conversor de Moedas!** Este projeto em Java permite que você converta entre diferentes moedas com taxas de câmbio em tempo real, utilizando a API ExchangeRate. Quer saber quantos pesos argentinos cabem no seu dólar ou quanto valem os seus reais em euros? Você está no lugar certo!

---

## 🚀 Funcionalidades

- **Taxas de Câmbio em Tempo Real**: Obtenha as cotações mais recentes através da API ExchangeRate.
- **Conversão Simples e Rápida**: Escolha sua moeda de origem e destino, insira o valor e veja o resultado instantaneamente.
- **Menu Interativo**: Um menu fácil de navegar para facilitar a conversão entre várias moedas.
- **Moedas Suportadas**: Dólar (USD), Euro (EUR), Peso Argentino (ARS), Real Brasileiro (BRL), Yuan Chinês (CNY), e muito mais!

---

## 🎯 Objetivo

Este projeto foi desenvolvido para facilitar a conversão de moedas diretamente do terminal, fornecendo uma solução simples e intuitiva para os usuários que desejam entender melhor suas transações internacionais ou apenas matar a curiosidade sobre como uma moeda se compara a outra!

---

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter o seguinte instalado:

- **Java 8** ou superior.
- **Chave de API da ExchangeRate**. Se você ainda não tem, basta se cadastrar [aqui](https://www.exchangerate-api.com/) e gerar sua chave de acesso.

---

## 🛠️ Como Configurar e Executar

1. **Clone o Repositório:**

   Abra seu terminal e execute:

   ```bash
   git clone https://github.com/pcsouzafv/conversor-moedas.git
   ```

2. **Compile o Código:**

   Entre no diretório do projeto e compile o arquivo `ConversorMoedas.java`:

   ```bash
   javac ConversorMoedas.java
   ```

3. **Configure sua Chave de API:**

   No código, substitua `API_KEY` pela sua chave pessoal da ExchangeRate API.

   ```java
   private static final String API_KEY = "sua_chave_aqui";
   ```

4. **Execute o Programa:**

   Com tudo pronto, execute o programa com:

   ```bash
   java ConversorMoedas
   ```

5. **Escolha suas Moedas e Faça a Conversão:**

   - No menu, escolha a moeda de origem e a moeda de destino.
   - Insira o valor que deseja converter e veja a magia acontecer!

---

## 🧩 Estrutura do Código

Aqui está um resumo do que cada parte do código faz:

- **API_KEY**: Sua chave pessoal para acessar as taxas de câmbio.
- **API_URL**: O endpoint da API, já configurado com a chave e a moeda base.
- **Scanner**: Usado para capturar as escolhas e os valores fornecidos pelo usuário.
- **`obterTaxaCambio()`**: Método que faz a chamada à API e obtém a taxa de conversão entre duas moedas.
- **`converterMoeda()`**: Recebe o valor, aplica a taxa de câmbio e imprime o resultado.

---

## 🎮 Exemplos de Uso

Aqui estão alguns exemplos de como você pode usar o conversor:

- **Converter 100 dólares para reais**: 
   Escolha a opção 3 (Dólar para Real Brasileiro), insira o valor "100" e veja o resultado na tela!

- **Converter 50 euros para dólares**: 
   Selecione a opção 5 (Euro para Dólar), insira "50" e confira o valor convertido!

---

## 🔧 Possíveis Melhorias

Aqui estão algumas ideias para evoluir o projeto no futuro:

- **Adicionar Mais Moedas**: Incluir moedas de diferentes regiões do mundo.
- **Gráficos e Histórico**: Mostrar variações de câmbio ao longo do tempo com gráficos.
- **Interface Gráfica**: Mover do terminal para uma interface gráfica amigável (GUI).
- **Suporte a Criptomoedas**: Adicionar a conversão de moedas digitais como Bitcoin (BTC) e Ethereum (ETH).

---

## 🛡️ Segurança

- **Uso da API**: Certifique-se de não expor sua chave de API diretamente no código público (use variáveis de ambiente para maior segurança).
- **Tratamento de Exceções**: O código está preparado para lidar com erros de requisição e entrada inválida do usuário, garantindo uma experiência suave.

---

## 📜 Licença

Este projeto está licenciado sob os termos da [MIT License](LICENSE), permitindo que você o use, modifique e distribua à vontade.

---

## 🙌 Agradecimentos

- Um enorme agradecimento à **ExchangeRate API** por fornecer uma API confiável e fácil de usar para obter taxas de câmbio.
- A todos os que estão interessados em aprender e melhorar suas habilidades de programação com projetos práticos como este!

---

Agora, é só rodar o programa, e boa conversão! 💰🌐

---

