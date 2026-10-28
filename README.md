# 🚌 BusPass — Sistema de Mobilidade Urbana e Gestão de Transporte Público

Projeto desenvolvido pela equipe **Four Sync**, com o objetivo de modernizar e facilitar a utilização do transporte público por meio de uma plataforma web intuitiva e acessível.

O **BusPass** é uma solução tecnológica voltada à mobilidade urbana, integrando gerenciamento de cartões de transporte, consulta de saldo, recargas, informações sobre linhas de ônibus e visualização de pontos e trajetos em um mapa interativo.

---

## 📚 Contexto e Problema

O transporte público é essencial para a mobilidade urbana, porém muitos passageiros enfrentam dificuldades para consultar saldos, realizar recargas, localizar pontos de ônibus e acessar informações sobre linhas e horários.

A falta de centralização dessas informações pode gerar atrasos, deslocamentos desnecessários e dificuldades no planejamento das viagens.

O **BusPass** surge como uma proposta de solução digital capaz de reunir diferentes funcionalidades relacionadas ao transporte coletivo em uma única plataforma, proporcionando maior praticidade, organização e autonomia aos passageiros.

---

## 🎯 Objetivos do Projeto

Desenvolver uma aplicação web interativa que:

- **Facilite o gerenciamento de cartões:** Permita aos usuários cadastrar e acompanhar seus cartões de transporte.
- **Simplifique as recargas:** Ofereça uma interface prática para adicionar e gerenciar créditos.
- **Centralize informações:** Disponibilize consultas de linhas, horários e pontos de ônibus.
- **Auxilie no planejamento de trajetos:** Utilize mapas interativos para facilitar a visualização de locais e deslocamentos.
- **Melhore a experiência do usuário:** Proporcione uma navegação moderna, intuitiva e responsiva.
- **Promova a mobilidade inteligente:** Utilize recursos tecnológicos para tornar o transporte público mais acessível e organizado.

---

## 👥 Equipe — FOUR SYNC

| Integrante | Funções / Responsabilidades |
|---|---|
| **[Vitor](https://github.com/vtvitor)** | Full-Stack Developer |
| **[Leticia](https://github.com/leticiameira-star)** | Full-Stack Developer |
| **[Maria](https://github.com/konomi-naruko)* | Front-End Developer |
| [Kauan](https://github.com/kauan-cmd-alt) | UI/UX Designer |
O projeto foi desenvolvido de forma colaborativa, reunindo conhecimentos em desenvolvimento web, integração de sistemas, banco de dados e design de interfaces.

---

## 🛠️ Implementação Técnica

### Tecnologias utilizadas

| Camada | Tecnologias |
|---|---|
| **Front-End** | HTML5, CSS3 e JavaScript |
| **Back-End** | Java 21 e Spring Boot 3.5.6 |
| **API** | REST, utilizando requisições HTTP e JSON |
| **Banco de Dados** | MySQL |
| **Persistência** | Spring Data JPA / Hibernate |
| **Gerenciamento de dependências** | Maven |
| **Infraestrutura** | Render |

A aplicação utiliza uma arquitetura em camadas, separando a interface do usuário, as regras de negócio e a persistência de dados.

### ⚙️ Recursos e Funcionalidades

- **Cadastro e autenticação:** Criação de contas e acesso por meio de login.
- **Gerenciamento de cartões:** Cadastro, consulta e gerenciamento de cartões vinculados ao usuário.
- **Consulta de saldo:** Visualização dos créditos disponíveis no cartão.
- **Recarga de transporte:** Funcionalidade para adicionar créditos e atualizar o saldo.
- **Linhas de ônibus:** Consulta das linhas cadastradas no sistema.
- **Localização de pontos:** Visualização de pontos de ônibus e informações geográficas.
- **Mapa interativo:** Apoio à navegação e ao planejamento de deslocamentos.
- **Interface responsiva:** Adaptação da apresentação para diferentes tamanhos de tela.
- **Integração front-end e back-end:** Comunicação entre a interface web e os serviços REST.

> **Nota:** A recarga atualiza o saldo registrado pelo sistema. A integração com pagamentos bancários reais ainda não está incluída nessa descrição como recurso implementado.

---

## 📦 Estrutura do Projeto

O desenvolvimento está dividido em dois repositórios principais.

**Front-End:**

```text
frontend-projeto/
├── index.html
├── style.css
├── script.js
├── api.js
├── data.js
├── geocode_points.js
└── Mapa_legendas.png
```

**Back-End:**

```text
backend-projeto/
├── src/
│   └── main/
│       ├── java/
│       │   └── com/onbius/busspass/
│       │       ├── config/
│       │       ├── controller/
│       │       ├── entity/
│       │       ├── repository/
│       │       ├── service/
│       │       └── BusspassApplication.java
│       └── resources/
│           └── application.properties
├── pom.xml
└── Dockerfile
```

A estrutura favorece a manutenção do código e a organização das responsabilidades entre as diferentes camadas do sistema.

---

## 🔗 Links e Repositórios

- **Front-End:** [github.com/vtvitor/frontend-projeto](https://github.com/vtvitor/frontend-projeto)
- **Back-End:** [github.com/vtvitor/backend-projeto](https://github.com/vtvitor/backend-projeto)
- **Landing-Page:** https://landing-page-wt6o.onrender.com


---

## 🚀 Como Utilizar

1. **Clonagem:** Faça o download dos repositórios do front-end e back-end.
2. **Banco de dados:** Configure uma instância do MySQL e os parâmetros de conexão no Spring Boot.
3. **Back-end:** Execute a aplicação Java com Maven, disponibilizando os endpoints da API REST.
4. **Front-end:** Configure o endereço da API em `api.js` e abra `index.html` no navegador.
5. **Cadastro:** Crie uma conta ou faça login com suas credenciais.
6. **Cartões:** Cadastre um cartão, consulte seu saldo e utilize a funcionalidade de recarga.
7. **Mobilidade:** Consulte linhas, visualize pontos de ônibus e explore os recursos do mapa interativo.

---

## 🔮 Possibilidades de Evolução

- Integração de pagamentos reais via Pix e cartões bancários.
- Monitoramento de ônibus por GPS em tempo real.
- Notificações automáticas de saldo baixo.
- Estimativas de chegada dos ônibus aos pontos.
- Sugestões de trajetos com base na localização do passageiro.
- Integração com dispositivos físicos, como ESP32 e leitores RFID, para validação dos cartões.

---

## 📝 Considerações Finais

O **BusPass** representa uma proposta de modernização da experiência dos usuários do transporte público, reunindo tecnologias de desenvolvimento web, integração de APIs REST e persistência de dados em uma solução voltada à mobilidade urbana.

Desenvolvido pela equipe **Four Sync**, o projeto demonstra a aplicação prática de conceitos como programação orientada a objetos, arquitetura em camadas, modelagem de banco de dados, comunicação entre sistemas e desenvolvimento de interfaces.

Além de contribuir para o aprendizado técnico dos integrantes, o BusPass apresenta potencial para evoluir como uma plataforma de apoio à mobilidade urbana, tornando o acesso às informações do transporte coletivo mais simples, rápido e organizado.
