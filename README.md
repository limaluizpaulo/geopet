<h1 align="center">Geo Pet</h1>
<p align="center">
  <img alt="Version" src="https://img.shields.io/badge/version-0.1.0-blue.svg?cacheSeconds=2592000" />
 
</p>

**Descrição**
O Projeto Geo Pet é uma aplicação que permite o cadastro de pets e suas informações de localização, bem como o controle de contas de pessoas cuidadoras. A aplicação utiliza uma Rest API para expor as funcionalidades para os usuários.



### :nut_and_bolt: Tecnologias

Esse projeto foi desenvolvido com a seguinte técnologias:

- C#
- Entity Framework Core
- QRCoder
- Nominatim.API
- ViaCEP API

## Funcionalidades

### Contas de pessoas cuidadoras

As contas de pessoas cuidadoras permitem o cadastro de usuários que irão cuidar dos pets cadastrados na aplicação. As funcionalidades disponíveis para as contas de pessoas cuidadoras são:

- Cadastro de nova conta de pessoa cuidadora, validando o CEP via ViaCEP API
- Listagem de todas as contas de pessoa cuidadora
- Obtenção de uma conta de pessoa cuidadora pelo id
- Atualização de uma conta de pessoa cuidadora pelo id
- Exclusão de uma conta de pessoa cuidadora pelo id

### Pets

Os pets são os animais cadastrados na aplicação. As funcionalidades disponíveis para os pets são:

- Cadastro de novo pet
- Listagem de todos os pets
- Obtenção de um pet pelo id
- Atualização de um pet pelo id
- Exclusão de um pet pelo id
- Geração de QR Code para um pet perdido, contendo informações como nome, idade, porte e raça do pet.

### Integração com a Nominatin API para obter informações de endereços

A aplicação utiliza a API Nominatin para obter informações de endereços, como latitude, longitude e nome de ruas.

### Integração com a ViaCEP API para validar CEPs

A aplicação utiliza a ViaCEP API para validar CEPs informados pelo usuário.

### Criptografia de senhas para garantir a segurança dos usuários

As senhas dos usuários são criptografadas utilizando o algoritmo SHA256, garantindo a segurança das informações armazenadas no banco de dados.

#### :thinking: Como rodar

```bash


Para executar o projeto, é necessário ter o .NET Core SDK instalado na máquina. Em seguida, siga os seguintes passos:

1. Clone o repositório do projeto
2. Abra o terminal na pasta do projeto
3. Execute o comando `dotnet run` para iniciar o servidor
4. Acesse `http://localhost:5000/swagger` no navegador para acessar a documentação da API

```


#### Licença

Este projeto está licenciado sob a licença XXX. Consulte o arquivo LICENSE para obter mais detalhes.

#### Autor

👤 **Luiz Paulo Lima**

- Site: [@limaluizpaulo](https://luizpaulo.eng.br)
- Github: [@limaluizpaulo](https://github.com/limaluizpaulo)
- LinkedIn: [@limaluizpaulo](https://linkedin.com/in/limaluizpaulo)

👤 **Allan Eric**

- Github: [@allan](https://github.com/)
- LinkedIn: [@allan](https://linkedin.com/in/)
