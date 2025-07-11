# 📄 Calculadora Web com Spring Boot

Este projeto é uma **calculadora web** criada com **Spring Boot** (backend em Java) e uma **interface gráfica em HTML e JavaScript**.  

Ela permite realizar operações básicas: **soma, subtração, multiplicação e divisão**.

---

## ✅ Funcionalidades

✔ Somar dois números.  
✔ Subtrair dois números.  
✔ Multiplicar dois números.  
✔ Dividir dois números (verificando divisão por zero).  
✔ Interface gráfica fácil de usar no navegador.  
✔ API REST (pode ser acessada por URL também).

---

## 🛠️ Requisitos para rodar

- **Java 8 ou superior** (verificar com: `java -version`)
- **Maven** (verificar com: `mvn -v`)
- Navegador web (Chrome, Firefox, etc.)

---

## 💻 Passo a passo para executar

### 1️⃣ Baixe ou clone o projeto

Se você está criando do zero, execute:
---
```bash
mvn archetype:generate -DgroupId=com.calculadora -DartifactId=calculadora -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false 
```
Entre na pasta:

```bash
cd calculadora
```
## 2️⃣ Configure o arquivo pom.xml

Abra o arquivo pom.xml no editor (por exemplo, nano):

```bash
nano pom.xml
```
Apague tudo que tem dentro e cole o conteúdo atualizado que inclui Spring Boot (está disponível no roteiro do professor ou aqui no repositório).

## 3️⃣ Crie o código Java

Crie a pasta e o arquivo:

```bash
mkdir -p src/main/java/com/calculadora
nano src/main/java/com/calculadora/Main.java
```
Cole o código do arquivo Main.java.

4️⃣ Crie a interface gráfica (HTML)

```bash
mkdir -p src/main/resources/static
nano src/main/resources/static/index.html
```
Cole o conteúdo do HTML (interface visual).

Este arquivo terá campos para inserir os números, botões para cada operação e um espaço para exibir o resultado.

## 5️⃣ Compile e execute

No terminal, dentro da pasta do projeto:

```bash
mvn clean install
mvn spring-boot:run
```
## 🌐 Como usar

Abra o navegador e digite:

```bash
http://localhost:8080/index.html
```
Você verá a tela com campos de número e botões para cada operação.

## 🔹 Testar os endpoints diretamente

```bash
http://localhost:8080/somar/5/3
http://localhost:8080/subtrair/10/4
http://localhost:8080/multiplicar/2/8
http://localhost:8080/dividir/20/5
```

