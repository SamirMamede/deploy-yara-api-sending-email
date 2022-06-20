   <div align="center">
        <a href="https://im.ge/i/r4kqNp"><img src="https://i.im.ge/2022/06/17/r4kqNp.md.png" alt="r4kqNp.md.png" border="0"></a>
    </div>
    <div aligne="center">
        <h3>- CRUD usuário:</h3>
        <a href="https://api-yara-sendingemail.herokuapp.com/users">https://api-yara-sendingemail.herokuapp.com/users</a>
        <p>Informações úteis: </p>
        <p>Para salvar um usuário no banco de dados, nameUser e emailUser devem ser inseridos.</p>
        <p>{</p>
        <p>"nameUser": "MariaClara",</p>
        <p>"emailUser": "mariaclara@email.com"</p>
        <p>}</p>
        <p>Para os métodos GET, DELETE e PUT, você deverá informar o ID do usuário correspondente no database após o /users.</p>
        Exemplo: api-yara-sendingemail.herokuapp.com/users/1
        <h3>- CRUD mensagem:</h3>
        <a href="https://api-yara-sendingemail.herokuapp.com/message">https://api-yara-sendingemail.herokuapp.com/message</a>
        <p>Informações úteis: </p>
        <p>Para salvar uma mensagem no banco de dados, messageSubject e messageText devem ser inseridos.</p>
        <p>{</p>
        <p>"messageSubject": "Natal",</p>
        <p>"messageText": "Feliz Natal !!"</p>
        <p>}</p>
        <p>Para os métodos GET, DELETE e PUT, você deverá informar o ID da mensagem correspondente no database após o /message.</p>
        <p>Exemplo: api-yara-sendingemail.herokuapp.com/message/1 </p>
        <p>- Envio de e-mails para usuários cadastrados:</p>
        <p>api-yara-sendingemail.herokuapp.com/sending-email/nameUser</p>
        <p>Informações úteis: </p>
        <p>Neste cenário, em que a mensagem não será pré-formatada, você deverá inserir os seguintes dados, subject e text.</p>
        <p>{</p>
        <p>"subject": "Aniversário",</p>
        <p>"text": "Parabéns João !!"</p>
        <p>}</p>
        <p>- Envio de e-mails pré formatados, para usuários cadastrados:</p>
        <p>api-yara-sendingemail.herokuapp.com/sending-email/nameUser/messageSubject</p> 
        <p>Aqui você apenas informa o nome do usuário cadastrado e o assunto direto na URL.</p>
        <p>Exemplo:</p>
        api-yara-sendingemail.herokuapp.com/sending-email/MariaClara/Natal    
    </div>
