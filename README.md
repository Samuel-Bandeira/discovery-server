# ☕ Cafeteria Microservices - Discovery Server (Eureka)

Este repositório contém o **Servidor de Descoberta** (Naming Server) do ecossistema de microserviços da Cafeteria. Ele foi desenvolvido utilizando **Spring Cloud Netflix Eureka** para gerenciar a localização dinâmica de todos os serviços do sistema.

## 📖 Sobre o Projeto
Em uma arquitetura de microserviços, as instâncias dos serviços podem mudar de IP ou porta frequentemente. O **Discovery Server** atua como uma "agenda telefônica" central onde cada microserviço (como Pedidos ou Catálogo) se registra automaticamente ao iniciar.

### Principais Funcionalidades:
* **Service Registration:** Registro automático das instâncias dos microserviços.
* **Health Checking:** Monitoramento constante da saúde dos serviços registrados através de heartbeats.
* **High Availability Support:** Preparado para suportar múltiplas instâncias e balanceamento de carga.



## 🛠️ Tecnologias
* **Java 17**
* **Spring Boot 3.x**
* **Spring Cloud Netflix Eureka Server**
* **Maven** (Build System)

## 🚀 Como Executar
1. **Pré-requisitos:** Certifique-se de ter o Java 17+ instalado.
2. **Clonar o repositório:**
   ```bash
   git clone [https://github.com/Samuel-Bandeira/discovery-server.git](https://github.com/Samuel-Bandeira/discovery-server.git)