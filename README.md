# Construindo um Esquema Conceitual para Banco de Dados
# Oficina Mecânica

#### Desafio de Projeto proposto no Bootcamp Suzano - Análise de DAdos com Power BI na plataforma Dio.

### Descrição do Desafio
_Agora você irá criar um esquema conceitual do zero. A partir da narrativa fornecida você será capaz de criar todas as entidades, relacionamentos e atributos. Caso encontre algo que não foi definido na narrativa, utilize a sua compreensão do contexto e deixe uma descrição no README do seu github para verificação._

Instrutora: *Juliana Mascarenhas*
</b>
### Objetivo:
Criar o esquema conceitual para o contexto de oficina com base na narrativa fornecida.

### Narrativa:
- Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica.
- Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões periódicas.
- Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
- A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra.
- O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços.
- A mesma equipe avalia e executa os serviços.
- Os mecânicos possuem código, nome, endereço e especialidade.
- Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.

### Ferramentas utilizadas:

- [MySQL Workbench](https://www.mysql.com/products/workbench/)

### Modelo Conceitual:

![image](https://github.com/user-attachments/assets/b51350e3-c3fa-4de1-b1d1-6fda26c7e0cb)
