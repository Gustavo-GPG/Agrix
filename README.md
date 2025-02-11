# Boas vindas ao repositório do meu projeto final Agrix!

O Agrix é um sistema de gestão e monitoramento de fazendas.

# Resumo

Essa é uma plicação spring boot que desenvolvi ao final dos meus estudos na [Trybe](https://www.betrybe.com).
A aplicação possui as funcionalidades básicas de criar, ler, atualiazar e deletar dados relacionados a fazendas, plantações e fertilizantes e tudo com base no ambiente spring, usando Spring Data JPA, Spring Web, Spring Security e o Spring Boot.

#🚀 Tecnologias utilizadas
---
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java" width="40" height="40"/> Java  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" alt="Spring Boot" width="40" height="40"/> Spring Boot  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" alt="Spring Web" width="40" height="40"/> Spring Web  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" alt="Spring Data JPA" width="40" height="40"/> Spring Data JPA  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" alt="Spring Security" width="40" height="40"/> Spring Security<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL" width="40" height="40"/> MySQL

---
<details>
  <summary>📊 Diagrama Relacional de Entidades</summary>
  
  ![DRE-Agrix](DRE-Agrix.png)

</details>

---
# 🖥️ Iniciando aplicação
• Para copiar o repositório para uma pasta local, use o seguinte comando no terminal:

```bash
git@github.com:Gustavo-GPG/ProjetoFinalAngrix.git
```
Caso você não tenha o Git instalado, você pode instalá-lo usando os seguintes comandos, dependendo do seu sistema operacional:

Debian/Ubuntu (Terminal Bash):
```bash
sudo apt-get install git
```
Windows (PowerShell):
```bash
winget install --id Git.Git -e --source winget
```
Ou você pode seguir a documentação do site [git](https://git-scm.com/downloads) para mais meios de instalação.

• Navegue até a raiz da pasta criada no clone, abra o terminal e digite o comando:
```bash
mvn install
```
• Navegue até \src\main\java\com\betrybe\agrix\AgrixApplication.java e rode a aplicação manualment ou com:
```bash
mvn spring-boot:run
```

• Navegue até a pasta criada no clone e abra o terminal

⚠️**Atenção:** A aplicação usa por padrão a porta 8080 então certifique-se de tela disponível

Agora é só abrir o navegador e colocar o endereço http://localhost:8080/
---

Este projeto foi guiado por requisitos pré-estabelecidos pela [Trybe](https://www.betrybe.com).
