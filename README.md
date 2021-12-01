<h1> Spring </h1>

<br />

## Como criar meu primeiro <olá mundo> backend com meu projeto Spring? 

## Sigam-me as pessoas boas:

<br />
###01. Pelo navegador entrar no site https://start.spring.io/

<br />

<h2> 02 - Setup do Projeto</h2>

<br />

<h3>Configurações iniciais</h3>

<br />

| Item             | Descrição                                                    |
| ---------------- | ------------------------------------------------------------ |
| **Name**         | Nome do Projeto (Geralmente em letras minúsculas)            |
| **Type**         | Define o Gerenciador de Dependências (Maven)                 |
| **Packaging**    | Define como a aplicação será empacotada (JAR)                |
| **Java Version** | Versão do Java (a versão da imagem pode ser diferente da sua tela) |
| **Language**     | Linguagem (Java)                                             |
| **Group**        | O domínio reverso de sua empresa ou organização. **Exemplo:** *generation.org.br* => ***br.org.generation*** |
| **Artifact**     | O artefato a ser gerado, ou seja, o nome da aplicação que será criada (Mesmo nome do projeto) |
| **Version**      | Versão da API (não alterar)                                  |
| **Description**  | Descrição do projeto                                         |
| **Package**      | Estrutura do pacote inicial da aplicação (Group + Artifact). Exemplo: ***<u>br.org.generation.helloworld</u>*** |

<br />


**Dependências**
<br />

Neste projeto vamos inserir 3 dependências, conforme mostra a figura abaixo:

<br />

<div align="center"><img src="https://i.imgur.com/jeY8cYu.png" title="source: imgur.com" /></div>

<br />

| Dependência               | Descrição                                                    |
| ------------------------- | ------------------------------------------------------------ |
| **Spring Web**            | Fornece todas as Bibliotecas necessárias para trabalhar com o protocolo http. |
| **Spring Boot Dev Tools** | Permite a atualização do projeto em tempo real durante o processo de Desenvolvimento da aplicação. |
| **Validation**            | Fornece um conjunto de anotações que permite validar os atributos das Classes da Camada Model. |

<br />

![unknown (6)](https://user-images.githubusercontent.com/57760132/126806902-5454a036-4738-4df4-a1a8-6ac347457d92.png)

<br />
###2. Clicar nno botão GENERATE CTRL +

 

![unknown (7)](https://user-images.githubusercontent.com/57760132/126806915-86de57b8-84a0-4e13-9338-05da0bb78509.png)

<br />
###3. Ter baixado o *Winrar* para extrair os arquivos na pasta.


![unknow (8)](https://user-images.githubusercontent.com/57760132/126806978-462957c2-019c-4e20-b90a-a5b56b7b366f.png)

<br />
###4.Entrar no *Eclipse* para importar sua pasta como *Maven project.*

![unknown (9)](https://user-images.githubusercontent.com/57760132/126806989-fddbd0b2-464a-42aa-a05c-35ceadf83ae4.png)

<br />

###5.Selecionar um projeto Maven existente.

![unknown (10)](https://user-images.githubusercontent.com/57760132/126806997-9cd37116-36b8-4fde-8dc9-43c7cc881d0e.png)


###6.Selecionar a pasta extraída.


![unknown (11)](https://user-images.githubusercontent.com/57760132/126807003-12aec31f-70e3-4052-b2f8-43f19fad3c30.png)
###7. Verificar se o arquivo *.pom* esta marcado.

<br />

<div align="center"> <h2>*** IMPORTANTE ***</h2></div>

Caso o projeto apresente algum erro no arquivo pom.xml, utilize o <b>Guia de correção do arquivo pom.xml</b> para corrigir o problema.

<br />

<h2>Passo 03 - Ajuste da versão do Java (17 para 16) - arquivo pom.xml</h2>

<br />

**Caso você tenha configurado o seu projeto com a versão 11 do Java, ignore este passo.**
![image](https://user-images.githubusercontent.com/57760132/126812304-eddd8aa5-35ac-48ef-883d-368488c07d19.png)

<br />
###8. Em seu pacote inicial crie um novo package que vai servir como nosso *controller*

![image](https://user-images.githubusercontent.com/57760132/126807308-758b4147-a858-4ece-a0da-042a1737fe28.png)

<br />
###9.Boas praticas nomear o controller e clicar no Finish


![image](https://user-images.githubusercontent.com/57760132/126807359-17757a75-c493-473e-84b9-4b884bbc75be.png)

<br />
###10.Criar uma nova classe ( boas práticas começas com letra maiúscula ) 


![image](https://user-images.githubusercontent.com/57760132/126807904-784e40c9-9d3c-47d8-9c32-199db65e309b.png)

<br />
###11.Utlilizar as anotações *@RequestController e @RequestMapping("/aqui dentro o caminho para exibir no http") e @GetMapping*, importante fazer os *imports* das anotações

![image](https://user-images.githubusercontent.com/57760132/126809372-1caf9173-ca91-42e4-8d79-395058b4ae4a.png)
<br />
###11.No seu src clicar com botãoo direito do mouse e na opção "run as" executar o projeto java.

![image](https://user-images.githubusercontent.com/57760132/126809939-8a56f736-a8ae-4673-92db-a9740c0dd379.png)
<br />
###12. Abra o seu navegador e através na url http://localhost:8080/( aqui o caminho que vc indicou na sua anotação @RequestMapping *atenção nao pode ter espaço nesse request*) o meu ficou: http://localhost:8080/hello 

.
![10_bob_esponja](https://user-images.githubusercontent.com/57760132/126813685-a5ec5b03-8761-4b82-a6a8-db5e2faa3de2.gif)


