# Municípios Brasileiros - Tabela de Código IBGE

### Link para a Documentação da tabela
[link](https://github.com/filhotecmail/IBGE-Firebird-SQL/blob/main/Result.html)

Este repositório contém um script SQL para criar uma tabela chamada "MUNICIPIOS" em um banco de dados. A tabela é projetada para armazenar informações sobre os municípios brasileiros, incluindo seu código IBGE, nome, localização geográfica, código de estado, código SIAFI e fuso horário.

## Pré-requisitos

Para executar o script SQL, é necessário ter um banco de dados compatível com o SQL padrão, como PostgreSQL, MySQL ou Microsoft SQL Server.

## Como utilizar

Para criar a tabela "MUNICIPIOS" em seu banco de dados, execute o script SQL fornecido neste repositório. Certifique-se de ajustar as configurações de codificação e ordenação da tabela, conforme necessário, para garantir que ela esteja alinhada com as configurações do seu banco de dados.

## Esquema da tabela

A tabela "MUNICIPIOS" tem as seguintes colunas:

CODIGO_IBGE: um número inteiro que representa o código IBGE do município, que é utilizado para identificar cada município brasileiro de forma única.
NOME: uma string de até 100 caracteres que representa o nome do município.
LATITUDE: um número decimal que representa a latitude do município.
LONGITUDE: um número decimal que representa a longitude do município.
CAPITAL: um número inteiro que indica se o município é uma capital estadual (1) ou não (0).
CODIGO_UF: um número inteiro que representa o código do estado a que o município pertence.
SIAFI_ID: uma string de até 4 caracteres que representa o código SIAFI do município, que é utilizado para fins contábeis.
DDD: um número inteiro que representa o código de área do município.
FUSO_HORARIO: uma string de até 32 caracteres que representa o fuso horário do município.
Contribuindo
Sinta-se à vontade para enviar sugestões e correções por meio de pull requests ou issues neste repositório. Este projeto está sob a licença MIT, o que significa que você pode utilizá-lo livremente para fins pessoais e comerciais. Por favor, verifique a licença para mais detalhes.

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para mais detalhes.


