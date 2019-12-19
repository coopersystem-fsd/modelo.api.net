# Modelo de API .NET Core + DDD

O modelo.api é um projeto open source, escrito em .Net Core.

O objetivo deste projeto é mostrar que é possível criar uma nova arquitetura, mais simplificada, baseando-se no DDD (Design Domain Driven).

## Tecnologias  implementadas

* FluentValidation.AspNetCore
* Microsoft.EntityFrameworkCore.Design
* Microsoft.EntityFrameworkCore.Tools
* Pomelo.EntityFrameworkCore.MySql
* MySqlConnector

## Configurações

### Criar tabela User

```database
CREATE TABLE `User` ( `Id` INT NOT NULL , `Cpf` VARCHAR(255) NOT NULL , `BirthDate` DATE NOT NULL , `Name` VARCHAR(255) NOT NULL );
```

### Incluir usuário inicial

```database
INSERT INTO `User` (`Id`, `Cpf`, `BirthDate`, `Name`) VALUES ('1', '01569347603', '1989-06-30', 'vinicius');
```
## Como utilizar

@todo: preencher

## Referências

- [Projeto original](https://github.com/alex250195/Modelo.Api)
- [Uma nova arquitetura em .Net Core baseada em DDD](https://medium.com/@alexalvess/criando-uma-api-em-net-core-baseado-na-arquitetura-ddd-2c6a409c686)
