# Sistema de Locadora de Veículos 🚗🏍️

## Descrição

Este é um sistema de gerenciamento para locadoras de veículos, desenvolvido para nos auxiliar na produção da sprint 2, nesse projeto utilizamos **PHP**, **HTML**, **CSS** e **Bootstrap**. Ele permite que administradores gerenciem veículos disponíveis para locação, calculem valores de aluguel e registrem operações de aluguel e devolução de veículos.

## Funcionalidades

### 1. **Cadastro de Veículos**
   - Adicionar novos veículos com informações como:
     - Modelo
     - Placa
     - Tipo (Carro ou Moto)
   - Validações para garantir que os campos sejam preenchidos corretamente.

### 2. **Cálculo de Aluguel**
   - Permite calcular a previsão do custo do aluguel com base no tipo de veículo e na quantidade de dias.

### 3. **Gerenciamento de Veículos**
   - Exibe uma tabela com os veículos cadastrados, contendo:
     - Tipo do veículo
     - Modelo
     - Placa
     - Status (Disponível ou Alugado)
   - Permite realizar as seguintes ações:
     - **Alugar um veículo:** Especificar o número de dias desejados.
     - **Devolver um veículo alugado.**
     - **Deletar veículos** (somente disponível para administradores).

### 4. **Interface Responsiva**
   - Utiliza **Bootstrap** para oferecer uma interface responsiva e amigável.
   - Ícones fornecidos pela biblioteca **Bootstrap Icons** para melhorar a usabilidade.

## Estrutura do Sistema

### Backend
- O backend é implementado em **PHP** (trecho placeholder no código: `// backend`), responsável por processar as requisições, gerenciar os dados e realizar as operações de CRUD dos veículos.

### Frontend
- **HTML e CSS**: Design da interface e estilização.
- **Bootstrap**:
  - Layout responsivo.
  - Estilização de componentes como botões, tabelas e formulários.
- **JavaScript (Bootstrap)**:
  - Validação de formulários.

### Formulários
- **Adicionar Veículo**: Formulário para registrar novos veículos.
- **Calcular Previsão de Aluguel**: Formulário para calcular o custo do aluguel de veículos.
- **Gerenciamento de Veículos**: Ações disponíveis diretamente na tabela de veículos cadastrados.

## Tecnologias Utilizadas

- **PHP**: Backend para processamento de dados.
- **HTML5**: Estruturação do conteúdo.
- **CSS3**: Estilização personalizada.
- **Bootstrap 5**: Framework CSS para design responsivo e moderno.
- **Bootstrap Icons**: Biblioteca de ícones para interface.

## Estrutura do Projeto

```
LocadoraDe_Veiculos/
├── index.php         # Página principal do sistema
├── style.css         # Arquivo de estilos personalizados
├── bootstrap.min.css # Biblioteca Bootstrap
└── ...
```
