## Camadas (Layers)

* **Dominio**: Cont�m a representa��o do Neg�cio;
* **Infraestrutura**: Suporte ao Dom�nio para dependencias externas _(Ex: Abstra��o de Log e perif�ricos)_;
* **Infraestrutura.IoC**: Respons�vel pela inje��o de depend�ncia;
* **Infraestrutura.Tests**: Cont�m os testes de Integra��o;
* **Infraestrutura.EntityFramework**: Implementa��o de Persist�ncia de dados utilizando o ORM EntityFramework;
* **Infraestrutura.NHibernate**: Implementa��o de Persist�ncia de dados utilizando o ORM NHibernate;

## Tecnologias usadas
* **Autofac**: Container de Inje��o de Depend�ncia;
* **NUnit**: Asser��o dos testes;
* **EntityFramework**: ORM;
* **Nhibernate**: ORM;
* **Effort**: Banco de dados em mem�ria para testes com EntityFramework;
* **SQLite**: Banco de dados em mem�ria para testes com NHibernate;

## Padr�es e Melhores Pr�ticas (Patterns & Best Practices)

* **Uppercase**
  * Constants
* **PascalCase**
  * Class 
  * Methods 
  * (Public / Protected) Properties
  * (Public / Protected) Fields
  * Events
  * Enums
  * Interface
* **kamelCase**
  * (Private) Properties
  * (Private) Fields
  * vars
  * params