# CSVReader

CSVReader é um simples leitor de arquivos CSV desenvolvido em C. Ele foi criado para facilitar a leitura e manipulação de dados de arquivos CSV em projetos que exigem esse tipo de funcionalidade.

## Funcionalidades

- Leitura de arquivos CSV.
- Manipulação e filtragem de dados.
- Ordenação dos dados lidos.
- Possibilidade de aplicar filtros específicos aos dados do CSV.

## Estrutura do Projeto

- **csvreader.c**: Código principal para ler e processar o arquivo CSV.
- **filtros.c**: Funções para aplicar filtros aos dados.
- **io.c**: Funções auxiliares para entrada e saída de dados.
- **lista.c**: Implementação das estruturas de dados utilizadas.
- **ordena.c**: Funções para ordenar os dados lidos.

## Como Compilar

Para compilar o projeto, use o `Makefile` incluído:

```bash
make
```

## Como Utilizar

Execute o programa com um arquivo .CSV como argumento

```bash
./csvreader arquivo.csv
```
