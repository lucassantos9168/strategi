# Stramoveis

Projeto criado para segunda etapa do processo seletivo do Grupo Strategi. Em suma, o projeto trata-se de uma aplicação web de venda de imóveis. A premissa é de que um corretor de imóveis fará login no sistema e poderá gerenciar clientes (cadastrar, alterar e excluir), como também realizar simulações de compra com os imóveis cadastrador no banco de dados. <br> <br> <br>

### 📋 Pré-requisitos para iniciar o projeto <br> <br>

Abaixo está os programas que usei para iniciação do projeto.

```
- XAMPP;
- Apache NetBeans 12.0;
```
<a href="https://www.apachefriends.org/pt_br/index.html"> Link para instalação do XAMPP; </a>

<a href="https://dlcdn.apache.org/netbeans/netbeans/12.0/Apache-NetBeans-12.0-bin-windows-x64.exe"> Link para instalação do Apache NetBeans 12.0; </a> <br> <br> <br>

### 🔧 Instalação <br> <br>

Após a instalação do XAMPP e Apache, realize os seguintes passos:

```
Inicialize o XAMPP e seus módulos "Apache" e "MySQL";
```
```
Clique na ação "Admin" do módulo "MySQL";
```
```
Vá em "Importar" na barra superior, escolha o arquivo "dbstramoveis" encontrado em "strategi/bd/dbstramoveis.sql" e clique em "Executar" no canto inferior da página;
```
Com esses passos realizados, o banco de dados já está funcionando localmente. As próximas ações mostrarão como iniciar o projeto no Apache NetBeans e executá-lo.
```
Copie a pasta "strategi" para a parta "htdocs" dentro do diretório do XAMPP;
```
```
Abra o Apache e vá até File -> Open Project e abra o projeto que você colou no passo anterior;
```
```
Tecle F6 e aguarde a aplicação ser aberta no seu navegador.
```
<br> <br>



## ⚙️ Executando os testes

<br>

### 1. Login: <br> <br>

O primeiro teste é o de login. Esse teste demonstra o funcionamento do sistema de login integrado com o banco de dados importado. Utilize o seguinte login para entrar no sistema:

```
login: Lucas
senha: strategi
```
Note que ao digitar alguma das duas informações de forma incorreta uma mensagem de erro será mostrada. <br> <br>


### 2. Cadastro de clientes: <br> <br>

Já logado, vamos realizar o cadastro de um cliente. Clique no primeiro ícone para ir até a tela de gerenciamento de clientes e tenta cadastrar um novo. Fique atento à forma com que os dados são inseridos, em cada input há uma instrução para como eles devem ser registrados. Segue abaixo um exemplo de cadastro:

```
Nome:     Thresh
CPF:      974.465.600-02
E-mail:   thresh@gmail.com
Telefone: (84) 99289-7845
``` 

### <br> 3. Alterando dados: <br> <br>

Com o cliente "Thresh" cadastrado, clique no ícone de alteração dos dados na tela de gerenciamento. A tela de alteração de dados será aberta. Aí vem um exemplo de alteração:

```
CPF:      974.465.600-02
E-mail:   lanterna@gmail.com
Telefone: (89) 99345-8914
``` 

### <br> 4. Excluindo cliente: <br> <br>

Para excluir um cliente é simples, basta clicar no ícone de exclusão, o "X" a direita do cliente.

### <br> 5. Simulando compra: <br> <br>

Para simular a compra de um imóvel vá até a tela de vendas, selecione um cliente e um método de pagamento para a venda e clique no botão "Simular" ao lado do imóvel desejado. Será mostrado então os dados do imóvel. <h2> Embora os dados estejam sendo todos mostrados, não consegui fazer com que o corretor, cliente e método de pagamento escolhido fossem apresentados na tela. <h2> <br>


## 📦 Construido com

* MySQL - Sistema de gerenciamento de banco de dados;
* PHP - Linguagem interpretada.
<br> <br>

## ✒️ Autores e referências

* **Lucas Eduardo**
* [Flaticon](https://www.flaticon.com) - Ícones utilizados nas páginas.
