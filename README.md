# exercicio_banco_de_dados_modulo2



&nbsp;&nbsp;&nbsp;&nbsp;Nesta modelagem podemos observar as seguintes relações entre as tabelas:


**usuarios - manuais (1 - N):** Chave estrangeira ´id_manuais´ na tabela ´usuarios´ recebe o identificador do usuário, para identificar qual usuário publicou o manual.

**usarios - manuais (N - N):** Relação entre as duas tabelas, na qual varios usuarios podem receber varios manuais e varios manuais podem ser disponibilizados para varios usuarios.

**usuarios - manuais (N - N):** Relação entre as duas tabelas para armazenar os manuais marcados como favoritos pelo usuário, necessitando de uma tabela intermediária ´favoritos´, recebendo o identificador do usuário e do respectivo manual.

**manuais - arquivos (1 - N):** Chave estrangeira ´id_manuais´ na tabela ´arquivos´, para identificar os arquivos para cada manual.
