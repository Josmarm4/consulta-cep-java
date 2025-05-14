# Consulta CEP Java 🏠

Este é um projeto simples em Java que realiza a consulta de um endereço a partir de um CEP, utilizando a [API ViaCEP](https://viacep.com.br/). O programa também gera um arquivo `.json` com os dados do endereço consultado.

## 📦 Funcionalidades

- Leitura do CEP digitado pelo usuário
- Consulta à API ViaCEP
- Conversão da resposta em um objeto Java (`Endereco`)
- Geração de um arquivo `.json` com os dados do endereço
- Tratamento de erros de requisição

## 🛠️ Tecnologias utilizadas

- Java 17+
- API HTTP nativa do Java (`HttpClient`)
- Biblioteca [Gson](https://github.com/google/gson) para conversão JSON

## 📁 Estrutura do Projeto

```
📦buscador
┣ 📜ConsultaCep.java
┣ 📜Endereco.java
┣ 📜GeradorDeArquivo.java
┣ 📜Principal.java
┗ 📜README.md
```

## ▶️ Como executar

1. **Clone o repositório:**

```bash
git clone https://github.com/SEU_USUARIO/consulta-cep-java.git
cd consulta-cep-java
```

2. Compile os arquivos:

```bash
javac *.java
```
3. Execute o programa:
   
```
java Principal
```

4. Digite um CEP válido quando solicitado.
   
5. O resultado será exibido no terminal e salvo em um arquivo .json.
   
## 📌 Exemplo de saída
```
{
  "cep": "01001-000",
  "logradouro": "Praça da Sé",
  "complemento": "lado ímpar",
  "localidade": "São Paulo",
  "uf": "SP"
}
```

