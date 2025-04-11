# Simulador de Investimentos: Invest7

## Descrição

O sistema de simulação de investimentos tem como objetivo auxiliar usuários na compreensão do seu perfil de investidor e na projeção de rendimentos financeiros. Ele oferece uma experiência intuitiva e acessível, permitindo que usuários realizem simulações detalhadas, sem necessidade de conhecimentos avançados sobre o mercado financeiro. Além disso, o sistema fornece informações atualizadas sobre produtos financeiros, ajudando os usuários a tomarem decisões mais estratégicas e alinhadas aos seus objetivos e perfil investidor.

## Tecnologias Utilizadas

| Componente     | Tecnologia     |
| -------------- | -------------- |
| Back-end       | Java 21        |
| Front-end      | JavaFX e CSS   |
| Banco de Dados | MySQL          |
| APIs           | viaCEP e BrAPI |
| IDEs           | IntelliJ e DBeaver|
| Build Tool     | Maven          |
| Metodologia    | Scrum          |
| Gestão do Projeto    | Jira     |


## Funcionalidades 

| **Funcionalidade**                    | **Descrição**                                                                 |
|--------------------------------------|-------------------------------------------------------------------------------|
| **CRUD**                             | Operações de criação, leitura, atualização e exclusão de dados do sistema.    |
| **Login**                            | Autenticação de usuários com verificação de credenciais.                      |
| **Cadastro**                         | Registro de novos usuários no sistema.                                        |
| **Questionário ANBIMA**              | Coleta de informações para identificação do perfil de investidor durante o cadastro.            |
| **Criptografia de Senha**            | Proteção das senhas dos usuários utilizando técnicas de criptografia.         |
| **Calculadoras de Renda Fixa e Variável** | Ferramentas para cálculo de rendimento em diferentes modalidades de investimento. |
| **Simulações de Ações, FIIs, Renda Fixa** | Simuladores para diferentes tipos de investimento com base em dados reais.    |
| **Simulação por Perfil Investidor**  | Sugestões de investimentos com base no perfil identificado pelo questionário. |
| **Gerar CSV**                        | Exportação de dados e relatórios em formato .csv.                             |
| **Gráficos**                         | Representação visual dos dados e simulações por meio de gráficos.             |

## Estrutura do Projeto

```
├───.mvn
│   └───wrapper
└───src
    └───main
        ├───java
        │   └───com
        │       └───example
        │           └───invest7
        │               ├───controller
        │               │   ├───user
        │               │   └───viewcontroller
        │               ├───dao
        │               ├───model
        │               │   └───produtos
        │               └───util
        ├───resources
        │   ├───com
        │   │   └───example
        │   │       └───invest7
        │   ├───fonts
        │   └───image
        └───test
           └───java
```


## Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

##

### Créditos
![Static Badge](https://img.shields.io/badge/Gustavo%20Sousa-github?logo=github&logoColor=white&labelColor=black&color=%23246cfb&cacheSecond=https%3A%2F%2Fgithub.com%2Fpucheranni)
![Static Badge](https://img.shields.io/badge/Leandro%20Sena-github?logo=github&logoColor=white&labelColor=black&color=%2353ab55&cacheSecond=https%3A%2F%2Fgithub.com%2FDev-LeandroSena)
![Static Badge](https://img.shields.io/badge/Leonardo%20Borges-github?logo=github&logoColor=white&labelColor=black&color=%23246cfb&cacheSecond=https%3A%2F%2Fgithub.com%2FLeonardoBorges)
![Static Badge](https://img.shields.io/badge/Thiago%20Ferrer-github?logo=github&logoColor=white&labelColor=black&color=%2353ab55&cacheSecond=https%3A%2F%2Fgithub.com%2Fthiagoferrer)
![Static Badge](https://img.shields.io/badge/Victória%20Rocha-github?logo=github&logoColor=white&labelColor=black&color=%23246cfb&cacheSecond=https%3A%2F%2Fgithub.com%2Fvicotirah)
