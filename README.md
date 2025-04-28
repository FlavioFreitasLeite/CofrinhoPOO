# CofrinhoPOO

## 📚 Sobre o Projeto

O **CofrinhoPOO** é um sistema desenvolvido em **Java** como parte da atividade prática de **Programação Orientada a Objetos (POO)**.

A aplicação simula um cofrinho digital, permitindo o gerenciamento de moedas de diferentes tipos, com a utilização dos conceitos de:

- **Herança**
- **Polimorfismo**
- **Abstração**
- **APIs de Câmbio em Tempo Real**

O sistema consulta automaticamente as cotações atuais das moedas utilizando uma API pública.

---

## ⚙️ Funcionalidades

✅ Adicionar moedas (Real, Dólar, Euro)  
✅ Remover moedas específicas  
✅ Listar todas as moedas no cofrinho  
✅ Calcular o valor total convertido para **Real (BRL)**  
✅ Obter cotações **em tempo real** através da API ExchangeRate

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia  | Função |
|:------------|:-------|
| ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=java&logoColor=white) | Linguagem principal |
| ![Eclipse](https://img.shields.io/badge/Eclipse-2C2255?style=flat&logo=eclipse&logoColor=white) | IDE para desenvolvimento |
| ![Gson](https://img.shields.io/badge/Gson-1C1C1C?style=flat&logo=google&logoColor=white) | Biblioteca de parser JSON |
| 🌐 ExchangeRate-API | API pública para cotação de moedas |

---

## 🧩 Estrutura do Projeto

CofrinhoPOO/
 └── src/
      └── app/
          ├── Cofrinho.java
          ├── Dolar.java
          ├── Euro.java
          ├── Real.java
          ├── Moeda.java
          ├── Principal.java
          └── ExchangeRateService.java

- **Moeda:** Classe abstrata representando uma moeda genérica.
- **Real / Dolar / Euro:** Subclasses específicas que implementam conversão.
- **Cofrinho:** Armazena e manipula moedas usando uma lista dinâmica.
- **ExchangeRateService:** Faz chamadas HTTP para obter taxas de câmbio em tempo real.
- **Principal:** Classe com o menu de interação principal.

## 🚀 Como Executar
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/seuusuario/CofrinhoPOO.git
Abra no Eclipse IDE.

Garanta:

Java 11 ou superior instalado ✅

Biblioteca Gson adicionada ao Build Path ✅

Execute a classe Principal.java

## 💡 Importante: Tenha acesso à internet para que o sistema busque as cotações corretamente.
