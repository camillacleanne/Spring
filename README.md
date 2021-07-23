# Spring
## Como criar meu primeiro olá mundo backend com meu projeto Spring? 

## Sigam-me as pessoas boas:

###1. Pelo navegador entrar no site https://start.spring.io/
  >
  ###1.1 Group: geralmente com nome da empresa
  >
  ###1.2 Artifact: geralmente com nome do projeto
  >
  ###1.3 Adicionar as seguintes dependências:
  >
      Spring Boot DevTools
      Spring Web
      Validation



![unknown (6)](https://user-images.githubusercontent.com/57760132/126806902-5454a036-4738-4df4-a1a8-6ac347457d92.png)
###2. Clicar nno botão GENERATE CTRL +

 

![unknown (7)](https://user-images.githubusercontent.com/57760132/126806915-86de57b8-84a0-4e13-9338-05da0bb78509.png)
###3. Ter baixado o *Winrar* para extrair os arquivos na pasta.


![unknow (8)](https://user-images.githubusercontent.com/57760132/126806978-462957c2-019c-4e20-b90a-a5b56b7b366f.png)
###4.Entrar no *Eclipse* para importar sua pasta como *Maven project.*

![unknown (9)](https://user-images.githubusercontent.com/57760132/126806989-fddbd0b2-464a-42aa-a05c-35ceadf83ae4.png)
###5.Selecionar um projeto Maven existente.

![unknown (10)](https://user-images.githubusercontent.com/57760132/126806997-9cd37116-36b8-4fde-8dc9-43c7cc881d0e.png)

#VOILÁ
![10_bob_esponja](https://user-images.githubusercontent.com/57760132/126813685-a5ec5b03-8761-4b82-a6a8-db5e2faa3de2.gif)

###6.Selecionar a pasta extraída.


![unknown (11)](https://user-images.githubusercontent.com/57760132/126807003-12aec31f-70e3-4052-b2f8-43f19fad3c30.png)
###7. Verificar se o arquivo *.pom* esta marcado.

![image](https://user-images.githubusercontent.com/57760132/126812304-eddd8aa5-35ac-48ef-883d-368488c07d19.png)
###8. Em seu pacote inicial crie um novo package que vai servir como nosso *controller*

![image](https://user-images.githubusercontent.com/57760132/126807308-758b4147-a858-4ece-a0da-042a1737fe28.png)
###9.Boas praticas nomear o controller e clicar no Finish


![image](https://user-images.githubusercontent.com/57760132/126807359-17757a75-c493-473e-84b9-4b884bbc75be.png)
###10.Criar uma nova classe


![image](https://user-images.githubusercontent.com/57760132/126807904-784e40c9-9d3c-47d8-9c32-199db65e309b.png)
###11.Utlilizar as anotações *@RequestController e @RequestMapping("/aqui dentro o caminho para exibir no http") e @GetMapping*, importante fazer os *imports* das anotações

![image](https://user-images.githubusercontent.com/57760132/126809372-1caf9173-ca91-42e4-8d79-395058b4ae4a.png)
###11.No seu src clicar com bot~]ao direito do mouse e na opção "run as" executar o projeto java.

![image](https://user-images.githubusercontent.com/57760132/126809939-8a56f736-a8ae-4673-92db-a9740c0dd379.png)
###12. Abra o seu navegador e através na url http://localhost:8080/( aqui o caminho que vc indicou na sua anotação @RequestMapping *atenção nao pode ter espaço nesse request*) o meu ficou: http://localhost:8080/hello 

