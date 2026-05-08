# Sistema de Estacionamento ACME

##  Descrição do Projeto

Este projeto consiste no desenvolvimento de um sistema WEB Full-Stack para gerenciamento de estacionamentos diários da empresa ACME.

O sistema permite o cadastro de veículos e o controle das estadias realizadas no estacionamento, registrando entrada, saída e cálculo do valor total da permanência.

---

##  Objetivo

Desenvolver um sistema completo utilizando:

- Front-end Web  
- API REST  
- Banco de Dados MySQL  
- Prisma

Com foco em:

- CRUD de veículos  
- CRUD de estadias  
- Relacionamento entre tabelas  
- Comunicação entre Front-End e Back-End  

---

## Tecnologias Utilizadas

### Front-End
- HTML5  
- CSS3  
- JavaScript  

### Back-End
- Node.js  
- Express  
- Prisma ORM  
- CORS  
- Dotenv  

### Banco de Dados
- MySQL  

---

##  Funcionalidades

###  Veículos

- Cadastro de veículos  
- Listagem de veículos  
- Busca por placa  
- Atualização de dados  
- Exclusão de veículos  

### Estadias

- Cadastro de estadias  
- Registro automático da entrada  
- Registro de saída  
- Cálculo automático do valor total  
- Listagem de estadias  

---

##  Como Executar o Projeto

1. Clone o repositório:
```bash
git clone 
```

2. Acesse a pasta:
```bash
cd api
```

3. Instale as dependências:
```bash
npm install
```

4. Configure o arquivo `.env`:
```env
PORT=3000
DATABASE_URL="mysql://root@localhost:3306/estacionamento_acme"
```

5. Execute as migrations:
```bash
npx prisma migrate dev
```

6. Gere o Prisma Client:
```bash
npx prisma generate
```

7. Inicie o servidor:
```bash
npm run dev
```

---

##  Funcionamento do Sistema

1. O usuário cadastra um veículo  
2. O atendente registra uma nova estadia  
3. O sistema salva automaticamente a data e hora da entrada  
4. Ao finalizar a estadia, o sistema registra a saída  
5. O valor total é calculado automaticamente com base no tempo de permanência  

---

## Diferenciais

- Sistema Full-Stack completo  
- Integração entre Front-End e API REST  
- Persistência de dados com MySQL  
- Utilização de Prisma ORM  
- Interface moderna e responsiva  
- Cálculo automático de estadias  

---

## 📄 Licença

Projeto desenvolvido para fins educacionais.
