# 📊 DesafioControleFluxo

Projeto Java desenvolvido como parte de um desafio da [DIO - Digital Innovation One](https://www.dio.me/), com foco em **controle de fluxo**, **tratamento de exceções** e **boas práticas** de programação orientada a objetos. O objetivo é criar um programa que valide entradas do usuário e realize contagens com base em parâmetros fornecidos, aplicando conceitos fundamentais de Java.

---

## 📌 Índice

- [📘 Sobre o Projeto](#sobre-o-projeto)
- [🎯 Funcionalidades](#funcionalidades)
- [🚀 Tecnologias Utilizadas](#tecnologias-utilizadas)
- [⚙️ Como Executar](#como-executar)
- [📂 Estrutura do Projeto](#estrutura-do-projeto)
- [🧠 O que Aprendi](#o-que-aprendi)
- [📈 Melhorias Futuras](#melhorias-futuras)
- [👨‍💻 Autor](#autor)
- [📜 Licença](#licença)

---

## 📘 Sobre o Projeto

O **DesafioControleFluxo** é um projeto prático que implementa um sistema de contagem baseado em parâmetros fornecidos pelo usuário. Ele foi projetado para reforçar o aprendizado de **controle de fluxo** (estruturas condicionais e de repetição) e **tratamento de exceções** em Java, com uma abordagem orientada a objetos. O programa valida entradas, lança exceções personalizadas e exibe resultados de forma clara e organizada.

---

## 🎯 Funcionalidades

- **Validação de Entrada**: Verifica se os parâmetros fornecidos pelo usuário são válidos.
- **Exceções Personalizadas**: Implementa a classe `ParametrosInvalidosException` para tratar erros de entrada.
- **Contagem Dinâmica**: Realiza contagens com base nos parâmetros fornecidos, exibindo resultados com `System.out.println`.
- **Código Modular**: Estrutura orientada a objetos, promovendo reutilização e manutenção.

---

## 🚀 Tecnologias Utilizadas

- **Java 17**: Linguagem principal para desenvolvimento.
- **Maven**: Ferramenta de build e gerenciamento de dependências.
- **IntelliJ IDEA**: IDE recomendada (ou qualquer outra compatível, como Eclipse ou VS Code).
- **Git/GitHub**: Controle de versão e hospedagem do código.

---

## ⚙️ Como Executar

Siga os passos abaixo para executar o projeto localmente:

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/Luizguni/DesafioControleFluxo.git

   Acesse o diretório do projeto :

2. ##Acesse o diretório do projeto :
      Copiar
      cd DesafioControleFluxo      

3. ##Compilar o projeto com Maven :
      Copiar
      mvn clean install      

4. ##Execute o programa :
      mvn exec:java -Dexec.mainClass="com.luizguni.DesafioControleFluxo"

5. ##Interaja com o programa :
      Insira os parâmetros solicitados via console (ex.: dois números inteiros).
      O programa validará as entradas e exibirá o resultado da contagem.
   
Pré-requisitos :

Java 17 (JDK) instalado.
Configuração do Maven.
Git instalado (opcional, para clonagem).
📂 Estrutura do Projeto
texto simples

Copiar
DesafioControleFluxo/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/luizguni/
│   │   │       ├── DesafioControleFluxo.java
│   │   │       └── ParametrosInvalidosException.java
│   │   ├── resources/
│   ├── test/
│       └── java/
├── pom.xml
├── README.md
└── .gitignore

DesafioControleFluxo.java : Classe principal que contém a lógica do programa.
ParametrosInvalidosException.java : Exceção personalizada para tratamento de erros.
pom.xml : Arquivo de configuração do Maven.


🧠 O que Aprendi
Exceções Personalizadas : Criação e uso de abordagens customizadas ( ParametrosInvalidosException ).
Controle de Fluxo : Aplicação de estruturas condicionais ( if-else ) e de repetição ( for ).
Entrada de Dados : Utilização da classe Scanner para leitura de inputs do usuário.
Boas Práticas : Estruturação de código limpa, modular e orientada a objetos.
Gerenciamento de Projetos : Configuração e uso do Maven para builds e integração com GitHub.


📈 Melhorias Futuras
Interface Gráfica : Implemente uma GUI com Swing ou JavaFX para interação mais amigável.
Testes Automatizados : Adicione testes unitários com JUnit para garantir robustez.
Persistência de Dados : Armazenar o histórico de contágios em arquivos ou banco de dados.
Arquitetura MVC : Refatorar o código para seguir o padrão Model-View-Controller.
Documentação : Inclui JavaDoc para documentar classes e métodos.


👨‍💻 Autor
Desenvolvido por Luiz Guni Santos.

GitHub : Luizguni
LinkedIn : luizguni

⭐Gostou do projeto? Deixe uma estrela no repositório!
