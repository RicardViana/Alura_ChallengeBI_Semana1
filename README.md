# Alura - Challenge BI - Semana 1 - Logísta

Como primeiro desafio proposto pela **Alura** através do **Challenge BI** (https://www.alura.com.br/challenges/bi), a empresa Alura Log (empresa fictícia) através do gerente logística solicitou a criação dashboard para acompanhamento de algumas métricas do setor, sendo elas:

- Quantas entregas foram feitas no prazo;

- Quantas entregas foram feitas atrasadas;

- Número de veículos disponíveis;

- Índice de ocorrências por estado;

- Nível médio de estoque por ano;

- Ship to door (S2D) 

Onde o resultado foi o seguinte utilizando a ferramenta da microsoft Power BI: 

![image](https://user-images.githubusercontent.com/62486279/132950216-a3e4f253-ee01-4880-b9b4-634914f6f538.png)

Link: 
https://app.powerbi.com/view?r=eyJrIjoiZjI2ODNmMzEtYTNjYS00YWIzLWI5OTktMDk4YWZmMDNhZWNkIiwidCI6IjlhMmZjZWE5LWZkNTItNDFiNC1hZTMyLWIyYWViNzBmMzQ2ZSJ9

Através de quatro (4) bases disponibilizadas:

**Tabela - Estoque**

![image](https://user-images.githubusercontent.com/62486279/132950533-59b2ccac-c8fb-4e0c-a53d-11009bfa5406.png)

**Tabela - Pedidos**

![image](https://user-images.githubusercontent.com/62486279/132950563-bb1f7071-63cf-442d-bfe8-4e1cb94ca97c.png)

![image](https://user-images.githubusercontent.com/62486279/132950600-23d620c3-d507-49e9-83d7-78e14bcc95d6.png)

**Tabela - Produtos**

![image](https://user-images.githubusercontent.com/62486279/132950613-e6253ffc-75d1-4b15-9f27-bb00534be9a3.png)

**Tabela - Veículos**

![image](https://user-images.githubusercontent.com/62486279/132950631-c8aff977-0368-4103-b6dc-d4508b227e32.png)

Alem de ter criado mais duas tabelas auxiliares:

**Tabela - Calendario**

![image](https://user-images.githubusercontent.com/62486279/132950666-bf176049-33b9-49b1-972a-cdf8ccf3c512.png)

*Calendario criado de forma dinamica através do **campo/coluna** **Data da compra** da tabela de **Produtos** 

**Estados**

![image](https://user-images.githubusercontent.com/62486279/132950688-eae2c215-fa97-4b13-98f6-2b5ce09856f4.png)

Gerando o seguinte relacionamento entre essas tabelas:

![image](https://user-images.githubusercontent.com/62486279/132950755-a63eb5b7-6fd7-4f0a-a334-85503c7e4dca.png)
