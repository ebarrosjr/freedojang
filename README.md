# FREE DOJANG

Projeto opensource de controle de finanças, alunos, colaboradores, agendamento, performance e campeonatos para academias de artes marciais. 

Ideia _non sense_ de desenvolver toda a aplicação utilizando tecnologias mais discutidas no mercado.

## Pastas

### backend
    - Aqui estão os códigos da aplicação de gerenciamento no formato RESTFULL nas linguagens e framworks das pastas filhas.

### database

    - Apesar de termos as migrations, os scripts SQL de criação do banco de dados encontram-se nesta pasta

### docs

    - O projeto em si, a lista de requisitos, casos de uso, testes, DER e manuais

### frontend

    - Assim como o backend, a estrutura (o mesmo layout) visual encontra-se nessa pasta com os frameworks utilizados de acordo com o nome das pastas filhas, com exceção do HTML que está distribuído em suas filhas de acordo com o framework CSS utilizado, o mais leve comporá os estilos das outras pastas.

### public

    - Nesta pasta será desenvolvido o site público e dos alunos, no frontend mais leve gerado pela pasta frontend

## Notas gerais

Cadas pasta contém o seu arquivo README com instruções para colocar em funcionamento, o arquivo [CONTRIBUTING](docs/CONTRIBUTING.md) para os desenvolvedores que quiserem colaborar e as regras de commit e pullrequest está na pasta docs.

Cada uma das pastas filhas em back e frontend são submodulos do git, com seu repositório separado permitindo que contribua apenas na linguagem que interessa.

Esse esforço serviu como _hands on_ no curso de desenvolvimento web completo que está disponível na hotmart.