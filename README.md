## Temas Abordados neste Projeto Jmeter

* Simulando vários usuários simultâneos
* Teste básicos
* Teste de Carga
* Teste de Permormance
* Teste de Estresse
* Teste de Pico
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

* **Observações:** - Para adicionar o plugin realize o download em **Plugins Manager**, após o download copie o arquivo para a pasta **lib > ext** e cole o arquivo.
* **Observações:** - Para configurar o plugin reinicie o Jmeter, clique em **Opções** e selecione **Plugins Manager** depois em **Available Plugins**
* **Observações:** - Para achar o plugin pesquise por **Custom Thread Groups** e selecione, por fim clique em **Apply changes and Restart JMeter**
* **Observações:** - Para adicionar o plugin será necessário clicar em **Adicionar > Threads (Users)** e selecionar o **Ultimate Thread Group**

* **Jmeter** - https://jmeter.apache.org/
* **Plugin** - https://jmeter-plugins.org/wiki/PluginsManager/
* **MongoDB Clound** - https://cloud.mongodb.com/
* **MongoDB Compass** - https://www.mongodb.com/pt-br/docs/compass/current/install/

## Ligando a API Localhost para teste com o MongoDB Clound

* **Observações** - Lembrando que é necessário realizar a etapa de configurações do MongoDB Clound antes deste processo

* **node app.js** - Irá ligar a API juntamente realizando a conexão com o MongoDB Clound 

## Rodando o Jmeter

* Executar o executavel do jmeter através do arquivo que foi feito o download ou das configurações de ambiente