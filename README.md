## 💻 Sobre o projeto

A API Clines é o backend da **Caelum Airlines**. Ela permite que o cliente compre reservas de voos e que o usuário do backoffice gerencie voos, aeroportos e aeronaves.

---

## ⚙️ Funcionalidades

- [x] Compra/atualização de reservas de voos;
- [x] Gerenciamento de voos;
- [x] Gerenciamento de aeroportos;
- [x] Gerenciamento de aeronaves;
- [x] Listagem de voos disponíveis para reserva;
- [x] Sistema de backoffice para administração.

---

## 🛠 Tecnologias

As seguintes tecnologias foram utilizadas no desenvolvimento da API Clines:

- **[Java 11](https://www.oracle.com/java)**
- **[Docker](https://www.docker.com)**
- **[Docker Compose](https://docs.docker.com/compose)**
- **[GNU Make](https://www.gnu.org/software/make)**

---

## 🚀 Executando a API Clines

Para executar este projeto, siga os passos abaixo:

```shell script
./mvnw clean package
docker image build --build-arg JAR=target/clines-api-0.0.1-SNAPSHOT.jar -t caelum/clines-api:latest .
docker-compose up
```
