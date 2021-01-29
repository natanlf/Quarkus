# Quarkus
Estudo Quarkus

### Banco de dados Mysql
Banco de dados: `quarkus_test`

CREATE TABLE `produto` (
  `id` bigint(20) NOT NULL,
  `dataAtualizacao` datetime(6) DEFAULT NULL,
  `dataCriacao` datetime(6) DEFAULT NULL,
  `descricao` varchar(255) DEFAULT NULL,
  `nome` varchar(255) DEFAULT NULL,
  `valor` double NOT NULL
);

