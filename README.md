# ATIVIDADE-BACK-END
avaliação para estagio--
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
----------------------------------------------------------------------------------------------------------------------

#ATIVIDADE BACK END PYTHON E BANCO DE DADOS SQL

#Gibran Reis

print('CRIAÇÃO DE DADOS REFERENTES A TABELA tb_customer_account')

clientes= int(input('DIGITE O NUMERO DE CLIENTES: '))

cont= 1

while (cont<= clientes):
    id_customer = int(input('Digite o ID do cliente: '))
    cpf_cnpj = int(input('Digite o cpf/cnpj do cliente: '))
    nm_customer =(input('Digite o nome do cliente: '))
    is_active =(input('Digite se o cliente esta ativo ou não: '))
    vl_total = int(input('Digite o valor total do saldo do cliente:'))
    cont+=1
print('A média final do campo vl_total dos clientes é: ',(vl_total+clientes)/cont)
print('O calculo da media ordenando do saldo do maior para o menor cliente é: saldo= ',vl_total, '/' 'id: ', id_customer,'/' 'cpf_cnpj: ',cpf_cnpj, 'nome: ', nm_customer,'/' 'ATIVO SIM OU NÃO: ',is_active)
    



    

