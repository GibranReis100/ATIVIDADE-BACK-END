# ATIVIDADE-BACK-END
avaliação para estagio
CREATE TABLE tb_customer_account(id_customer INTEGER,cpf_cnpj NUMERIC,nm_customer VARCHAR(100) NOT NULL,
is_active VARCHAR(15), vl_total INTEGER NOT NULL, PRIMARY KEY (id_customer));

INSERT INTO tb_customer (id_customer,cpf_cnpj, nm_customer, is active,vl_total)

VALUES (1500,123.456.789-10, 'Joao da Silva', 'ATIVO', 1500)


INSERT INTO tb_customer (id_customer,cpf_cnpj, nm_customer, is active,vl_total)

VALUES (500,111.222.333-44, 'MARIA ABRANTES', 'INATIVO',500)


INSERT INTO tb_customer (id_customer,cpf_cnpj, nm_customer, is active,vl_total)

VALUES (2600,222.333.444-55, 'CRISTIANO RONALDO AVEIRO', 'ATIVO', 2700)


INSERT INTO tb_customer (id_customer,cpf_cnpj, nm_customer, is active,vl_total)

VALUES (2700,333.444.555-66, 'EMILIO DOS REIS', 'ATIVO', 11400)


SELECT AVG(vl_total) FROM tb_customer WHERE vl_total>560;

SELECT AVG(id_customer) FROM tb_customer WHERE id_customer>=1500 AND id_customer<=2700;
