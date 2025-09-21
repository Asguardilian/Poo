# Poo
Quarto Semestre: Primeira Prova

# Guia de Instalação e Uso do Sistema de Notas

Este é um guia rápido para configurar e rodar o projeto de controle de notas em TypeScript.

### ⚙️ Pré-requisitos

Certifique-se de que você tem o [Node.js](https://nodejs.org/) instalado em seu computador. A instalação do Node.js já inclui o npm (gerenciador de pacotes).

### 🛠️ Instalação

1.  Abra o seu terminal (ou prompt de comando) na pasta raiz do projeto.
2.  Instale as dependências do projeto com o seguinte comando:
    ```bash
    npm install
    ```
    Isso vai instalar o `prompt-sync` (para interação com o usuário) e o `ts-node` (para rodar o código TypeScript diretamente).

### ▶️ Como Rodar o Código

Você tem duas opções para rodar o projeto:

**Opção 1: Rodar o TypeScript diretamente (recomendado)**
Esta opção é mais rápida e não exige que você compile o código primeiro.

```bash
ts-node main.ts
