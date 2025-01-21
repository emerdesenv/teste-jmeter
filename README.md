## Temas Abordados neste Projeto Jmeter

* Simulando vários usuários simultâneos
* Teste básicos
* Teste de Carga
* Teste de Permormance
* Implementações de métricas de tempo de requisição
* Implementação para geração de relatórios

## Primeios passos após o clone do Projeto

* Realizar o clone do projeto na sua máquina e colocar o mesmo dentro de uma pasta chamada **projetos**
* Abrir o projeto no **Visual Studio Code** ou algum editdor de sua preferência
* No terminal rodar o comando: **npm install**
* Criar o arquivo **.env** conforme o arquivo de exemplo **env-example.txt**

## Configuração para testes de API (localhost) + MongoDB Clound

* Após a configuração do MongoDB Clound, o arquivo **.env** deve estar configurado com a credencial de acesso ao mongo

## Instalação das Tecnologias

* **Observações**: Se você já tiver o arquivo **package.json** o mesmo pode ser implementado as instruções em **devDependencies**
* **Observações**: Se você não tiver o arquivo **package.json** crie o com o comando: **npm init -y** e depois **npm install**

## Documentações de Referências

* **Jmeter** - https://jmeter.apache.org/
* **MongoDB Clound** - https://cloud.mongodb.com/
* **MongoDB Compass** - https://www.mongodb.com/pt-br/docs/compass/current/install/

## Ligando a API Localhost para teste com o MongoDB Clound

* **Observações** - Lembrando que é necessário realizar a etapa de configurações do MongoDB Clound antes deste processo

* **node app.js** - Irá ligar a API juntamente realizando a conexão com o MongoDB Clound 