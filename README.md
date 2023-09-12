<span align="center">

# M6S1

</span>

Atividade do Módulo 6 da Semana 1 do curso da Ultima School - Django


Exercício:


Crie uma nova página (url, view e template) para indicar uma página de contato. Essa página precisa ter os campos do formulário para mandar uma mensagem. Por enquanto só precisa ter a página, sem nenhuma ação.

Esta página precisa ter:

- 3 campos: Nome, E-mail e Mensagem. 
- A rota que irá chamar esta página deverá ser /contato/
- A view deve ser criada no mesmo arquivo onde está a view inicio
- Coloque um link na página inicial que, ao clicar vá para esta página de contato.


Para conseguir rodar e visualizar a página precisamos de um ambiente virtual, se ainda não tiver basta seguir os seguintes passos abaixo para criação.

No terminal você deve digitar:

1 - python -m venv nome-do-ambiente

2 - nome-do-ambiente\scripts\activate

3 - pip install django

4 - python .\manage.py runserver

Caso você já possua um ambiente virtual criando basta seguir do passo 2 ao 4.
