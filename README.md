# App

GymPass style app

## RFs (Requisitos Funcionais)
- [ ] Deve ser possível se cadastrar
- [ ] Deve ser possível se autenticar
- [ ] Deve ser possível obter o perfil de um usuário logado
- [ ] Deve ser possível obter o número de checkins realizado pelo usuário logado
- [ ] Deve ser possível o usuário obter seu histórico de checkins
- [ ] Deve ser possível o usuário buscar academias próximas
- [ ] Deve ser possível o usuário buscar academias pelo nome
- [ ] Deve ser possível o usuário realizar checkin em uma academia
- [ ] Deve ser possível validar o checkin de um usuário
- [ ] Deve ser possível cadastrar uma academia

## RNs (Regras de Negócio)
- [ ] O usuário não deve poder se cadastrar com um email duplicado
- [ ] O usuário não pode fazer dois checkins no mesmo dia
- [ ] O usuário não pode fazer checkin se não estiver perto (100m) da academia
- [ ] O checkin só pode ser validado até 20min após criado
- [ ] O checkin só pode ser validado por administradores
- [ ] A academia só pode ser cadastrada por administradores

## RNFs (Requisitos não funcionais)
- [ ] A senha do usuário precisa estar criptografada
- [ ] Os dados da aplicação precisam estar persistido em um banco PostreSQL
- [ ] Todas listas de dados precisam estar paginadas com 20 itens por página
- [ ] O usuário deve ser identificado por um JWT (Jason Web Token)