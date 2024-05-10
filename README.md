# exercicio_banco_de_dados_modulo2

<div align="center">
<sub>Figura 1: Modelo Banco de Dados</sub>
<img src="../assets/wad/modelagem_banco_de_dados.png" style="width:90%"><br>
<sup>Fonte: Autoria (2024)</sup>
</div>


&nbsp;&nbsp;&nbsp;&nbsp;Nesta modelagem podemos observar as seguintes relações entre as tabelas:


**usuarios - manuais (1 - N):** Chave estrangeira ´userpubliser_id´ na tabela ´manuais´ recebe o identificador do usuário, para identificar qual usuário publicou o manual.

**usarios - manuais (N - N):** Relação entre as duas tabelas para definir a atribuição das tarefas, necessitando de uma tabela intermediária ´atribuicoes´ que recebe o identificador do usuário que deve fazer a tarefa, quem atribuiu e o manual que foi atribuido.

**usuarios - manuais (N - N):** Relação entre as duas tabelas para armazenar os manuais marcados como favoritos pelo usuário, necessitando de uma tabela intermediária ´favoritos´, recebendo o identificador do usuário e do respectivo manual.

**manuais - arquivos (1 - N):** Chave estrangeira ´manual_id´ na tabela ´files´, para identificar os arquivos para cada manual.
