# ACCOUNTS

## Descrição
ACCOUNTS é um simples sistema bancário que funciona diretamente no terminal, permitindo ao usuário criar contas, consultar saldo, depositar e sacar dinheiro.

## Funcionalidades
- **Criar conta**: Cria um arquivo JSON para armazenar as informações da conta.
- **Consultar saldo**: Exibe o saldo atual da conta.
- **Depositar**: Adiciona um valor ao saldo da conta.
- **Sacar**: Remove um valor do saldo da conta.
- **Sair**: Encerra o programa.

## Tecnologias utilizadas
- **Node.js**
- **Inquirer** (para interação no terminal)
- **Chalk** (para colorir mensagens)
- **FS** (para manipulação de arquivos)

## Como rodar o projeto
1. Clone o repositório:
   ```bash
   git clone https://github.com/ArthurBerto/projeto-accounts/
   ```
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Execute o programa:
   ```bash
   node index.js
   ```

## Estrutura de pastas
```
.
├── accounts/           # Contas criadas (arquivos JSON)
├── node_modules/       # Dependências
├── index.js            # Código principal
├── package.json        # Configurações do projeto
```

## Observações
- Certifique-se de que a pasta `accounts/` existe ou será criada ao criar a primeira conta.
- O saldo é armazenado como um valor numérico dentro de um arquivo JSON para cada conta.

---

Feito com ❤️ por Arthur Berto
