# App

Gympass style app.

## RFs (Requisitos funcionais)

- [x] Deve ser possível fazer o registo;
- [x] Deve ser possível fazer autenticação;
- [x] Deve ser possível obter o perfil de um utilizador logado;
- [ ] Deve ser possível obter o número de check-ins realizados pelo utilizador logado;
- [ ] Deve ser possível o utilizador obter o seu histórico de check-ins;
- [ ] Deve ser possível o utilizador buscar os ginásios próximos;
- [ ] Deve ser possível o utilizador pesquisar ginásios pelo nome;
- [x] Deve ser possível o utilizador realizar o check-in em um ginásio;
- [ ] Deve ser possível validar o check-in do utilizador;
- [ ] Deve ser possível registar um ginásio;

## RNs (Regras de negócio)

- [x] O utilizador não se pode registar com um email duplicado;
- [x] O utilizador não pode fazer 2 check-ins no mesmo dia;
- [x] O utilizador não pode fazer check-in se não estiver perto (100m) de um ginásio;
- [ ] O check-in só pode ser validado até 20 minutos após criado;
- [ ] O check-in só pode ser validado por administradores;
- [ ] O ginásio só pode ser registado por utilizador;

## RNFs (Requisitos não-funcionais)

- [x] A palavra-passe do utilizador precisa estar criptografada;
- [x] Os dados da aplicação precisam estar persistidos em uma base de dados PostgreSQL;
- [ ] Todas as listas de dados precisam estar paginadas com 20 itens por página;
- [ ] O utilizador deve ser identificado por um JWT (JSON Web Token);