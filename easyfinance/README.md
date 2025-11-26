# 🦇 Easy Finance — Batman Edition  
Sistema financeiro educativo desenvolvido em Spring Boot, com foco em usabilidade, estética moderna e uma identidade visual inspirada no universo Batman.

---

## 📌 Sobre o Projeto
O **Easy Finance** é um sistema em desenvolvimento para estudos e prática de desenvolvimento backend e frontend com **Java + Spring Boot**.  
O projeto está sendo estilizado com base em telas de referência e adaptado com a identidade visual do **Batman**, usando cores escuras e detalhes em amarelo.

Este repositório documenta todas as etapas da construção do sistema, desde a criação do projeto até a interface customizada.

---

## 🏗 Tecnologias Utilizadas
- **Java 21 (LTS)**
- **Spring Boot 3.x**
- Spring Web  
- Spring Security  
- Thymeleaf  
- Spring Boot DevTools  
- Maven  
- HTML/CSS  
- VS Code (como IDE principal)

---

## 📁 Estrutura Inicial do Projeto
Após a criação via Spring Initializr, a estrutura gerada foi:

easyfinance/
├─ .mvn/
├─ .vscode/
├─ src/
├─ target/
├─ .gitignore
├─ mvnw
├─ mvnw.cmd
├─ HELP.md
├─ pom.xml


O arquivo **pom.xml** contém todas as dependências necessárias para o funcionamento do projeto.

---

## ⚙️ Configuração do Ambiente

### ✔ Verificação da versão do Java  
O ambiente foi configurado com a versão:
java version "21.0.8" 2025-07-15 LTS
Java(TM) SE Runtime Environment (build 21.0.8+12-LTS-250)
Java HotSpot(TM) 64-Bit Server VM (build 21.0.8+12-LTS-250, mixed mode, sharing)


---

## 🔧 Build e Execução do Projeto

### 1️⃣ Instalar dependências e validar o projeto:
```bash
mvn clean install
Resultado esperado:
BUILD SUCCESS

2️⃣ Rodar o sistema:
mvn spring-boot:run

3️⃣ Acessar a aplicação no navegador:
http://localhost:8080/login

🎨 Interface do Usuário — Identidade Batman
As telas serão desenvolvidas seguindo:
🎨 Paleta de cores:
Preto / Grafite
Cinza escuro
Amarelo Batman (#F1C40F)
Azul escuro estilo Arkham

🦇 Elementos visuais:
Logo do Batman fornecida
Layout moderno, centralizado e responsivo
Campos e botões inspirados nas telas enviadas como referência

As telas base serão:
Login
Dashboard inicial
Tela de análise financeira

(Em construção)
🚧 Próximos Passos do Desenvolvimento
Criar página de login personalizada com tema Batman
Substituir a tela padrão do Spring Security
Adicionar CSS dedicado
Criar componentes de layout reutilizáveis
Criar dashboard inicial com base nas imagens enviadas
Implementar autenticação real (futuro)

🗂 Histórico das Ações Realizadas
Projeto criado via Spring Initializr no VS Code
Dependências escolhidas: Web, Security, Thymeleaf, DevTools
Correções de diretório para execução do Maven
Primeira execução bem-sucedida
Login padrão carregado em /login
Planejamento da identidade visual Batman
Organização e documentação completa do progresso