<h1>API RESTful para controle de estacionamento de condomínio usando Spring Data JPA </h1>
<p> A API permite ler, inserir, atualizar e deletar vagas de estacionamento de um banco de dados PostgreSQL.<br>





<h2>🛠 Tecnologias Utilizadas</h2>

<ul>
    <li>VS Code</li>
    <li>Java 11</li>
    <li>Maven</li>
    <li>Spring Web</li>
    <li>Spring Data JPA</li>
    <li>PostgreSQL Driver</li>
    <li>Hibernate Validator</li>
    <li>Lombok</li>
    <li>Postman</li>
</ul>

<h2>Rotas</h2>
<h3>/parking-spot</h3>
<ul>
<li>via GET: lista todos as vagas de estacionamento cadastradas e os dados de ocupação</li>
<li>via POST: cadastra uma nova vaga e seus dados de ocupação</li>
</ul>
<h3>/parking-spot/{id}</h3>
<ul>
<li>via GET: lista a vaga com id {id}</li>
<li>via PUT: atualiza os dados da vaga com id {id}</li>
<li>via DELETE: deleta a vaga com id {id}</li>
</ul>