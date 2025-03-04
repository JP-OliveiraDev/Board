# 📋 Board

**Projeto de Board para Gerenciamento de Tarefas**

Bem-vindo ao **Projeto de Board para Gerenciamento de Tarefas**! Este projeto foi desenvolvido como parte do bootcamp **Decola Tech 2025** e tem como objetivo ajudar você a organizar e acompanhar suas tarefas de forma eficiente e intuitiva. Com um board customizável, você pode criar, mover, bloquear e cancelar cards de tarefas, tudo isso salvo em um banco de dados MySQL para garantir que suas informações estejam sempre seguras e acessíveis.

---

## 🚀 Funcionalidades

- **Criação de Tarefas**: Adicione novas tarefas ao board de forma simples e rápida.
- **Movimentação de Tarefas**: Mova tarefas entre diferentes colunas (ex: "A Fazer", "Em Progresso", "Concluído").
- **Bloqueio de Tarefas**: Bloqueie tarefas que estão aguardando dependências ou revisões.
- **Cancelamento de Tarefas**: Cancele tarefas que não serão mais necessárias.
- **Persistência de Dados**: Todas as alterações são salvas em um banco de dados MySQL, garantindo que suas informações sejam mantidas mesmo após reinicializações.

---

## 🛠️ Tecnologias Utilizadas

- **Java**: Linguagem de programação principal utilizada no desenvolvimento do projeto.
- **Liquibase**: Ferramenta de migração de banco de dados para gerenciar alterações no esquema do banco de dados.
- **MySQL**: Banco de dados relacional utilizado para armazenar as informações das tarefas.
- **Lombok**: Biblioteca para reduzir a verbosidade do código Java, automatizando a criação de getters, setters, construtores, entre outros.

---

## 🛠️ Como Executar o Projeto

### Pré-requisitos

- **Java Development Kit (JDK)**: Certifique-se de ter o JDK instalado em sua máquina.
- **MySQL**: Instale e configure o MySQL para servir como banco de dados do projeto.
- **Maven**: Gerenciador de dependências utilizado no projeto.

### Configuração do Banco de Dados

1.  Crie um banco de dados MySQL para o projeto.
2.  Configure as credenciais de acesso ao banco de dados no arquivo de configuração do projeto.

### Executando o Projeto

1. Clone o repositório do projeto:
```
git clone https://github.com/JP-OliveiraDev/Board.git
```

2. Navegue até o diretório do projeto:
```
cd seu-projeto
```

3. Compile o projeto utilizando o Maven:
```
mvn clean install
```

4. Execute o projeto:
```
mvn spring-boot:run
```

### 🤝 Contribuição
Contribuições são sempre bem-vindas! Se você tiver alguma sugestão, correção de bugs ou melhoria, sinta-se à vontade para abrir uma issue ou enviar um pull request.

---

**Nota: Este projeto foi desenvolvido como parte do bootcamp Decola Tech 2025. Para mais informações sobre o bootcamp, visite Decola Tech 2025.**
