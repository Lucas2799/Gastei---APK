# 📱 Gastei — MVP de Educação Financeira

O **Gastei** é uma aplicação mobile desenvolvida como **MVP (Minimum Viable Product)**, com foco em **educação financeira**.  
O objetivo do projeto é auxiliar usuários a desenvolverem uma relação mais consciente com o dinheiro, por meio do **controle de gastos**, **definição de limites financeiros** e **alertas preventivos**.

Este projeto também funciona como um **estudo prático de Arquitetura de Software aplicada ao ecossistema .NET**, com ênfase em organização, escalabilidade e boas práticas.

---

## 🚀 Status do Projeto

🟡 **MVP concluído**  
O aplicativo ainda **não está publicado na Play Store**.  
Para fins de **demonstração técnica e validação**, um **APK está disponível para instalação manual (sideload)**.

> ⚠️ Observação: por não se tratar de uma distribuição oficial, o Android pode exibir avisos de segurança durante a instalação.

---

## 🧠 Visão Arquitetural

O projeto foi desenvolvido utilizando **.NET MAUI 9**, com foco em **baixo acoplamento, alta coesão e manutenibilidade**.

### 🏗️ Arquitetura Utilizada

- **Arquitetura em Camadas (Layered Architecture)**
  - **Presentation (UI)** — Telas e ViewModels
  - **Application / Services** — Orquestração e regras de aplicação
  - **Domain** — Regras de negócio e entidades
  - **Infrastructure** — Persistência e integrações

- **MVVM (Model–View–ViewModel)**
  - Separação clara entre UI e lógica de negócio
  - Facilita testes, manutenção e evolução da aplicação

---

## 🧩 Padrões de Projeto e Boas Práticas

Durante o desenvolvimento, foram aplicados padrões amplamente utilizados em aplicações .NET profissionais:

- **Repository Pattern** — abstração do acesso a dados
- **Service Layer Pattern** — centralização das regras de negócio
- **Dependency Injection (DI)** — baixo acoplamento e maior testabilidade
- **Princípios SOLID** — código limpo, extensível e sustentável
- **Async/Await** — operações assíncronas para melhor performance e experiência do usuário

---

## 📊 Domínio e Regras de Negócio

- Controle de orçamento baseado em **perfis financeiros**
- Cálculo dinâmico de **limites por categoria (buckets)**
- Monitoramento de uso mensal
- **Alertas preventivos** ao se aproximar dos limites definidos

O domínio foi estruturado visando **evolução incremental** e futura expansão do produto.

---

## 🛠️ Tecnologias Utilizadas

- **.NET MAUI 9**
- **C#**
- **MVVM**
- **Dependency Injection**
- **Async/Await**

---

## 📦 APK para Demonstração

O APK do MVP pode ser encontrado na seção **Releases** deste repositório.

> 📌 **Importante:** o aplicativo ainda não está pronto para produção comercial.

---

## 🗺️ Roadmap (Próximos Passos)

- Implementação de autenticação e autorização
- Persistência centralizada de dados
- Validação com usuários reais
- Evolução da arquitetura conforme crescimento do produto
- Preparação para publicação na Play Store

---

## 👨‍💻 Autor

**Lucas Tavares**  
Desenvolvedor .NET e estudante de **Arquitetura de Software**, com foco em aplicações escaláveis, manuteníveis e orientadas a boas práticas.

🔗 [Conecte-se comigo no LinkedIn](https://www.linkedin.com/in/ltavares123/)

---

## 📄 Licença

Este projeto é destinado a fins educacionais e de demonstração técnica.  
Licença a ser definida.
