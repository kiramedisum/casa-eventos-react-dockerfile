# Sistema de Casa de Eventos React

Este é um sistema de gerenciamento para casas de eventos.

## Pré-requisitos

- Docker instalado em sua máquina
- Node.js e npm (caso queira rodar localmente sem Docker)

## Como usar com Docker

1. Clone este repositório:
   ```
   git clone https://github.com/roofranklin/casa-de-eventos-react.git
   cd casa-de-eventos-react
   ```

2. Execute o container:
   ```
   docker run -p 3000:3000 casa-eventos-react
   ```

3. Abra seu navegador e acesse `http://localhost:3000`

## Como usar sem Docker (desenvolvimento local)

1. Clone o repositório como mostrado acima.

2. Instale as dependências:
   ```
   npm install
   ```

3. Inicie a aplicação:
   ```
   npm start
   ```

4. Abra `http://localhost:3000` no seu navegador.

## Scripts Disponíveis

- `npm start`: Inicia o servidor de desenvolvimento
- `npm test`: Executa os testes
- `npm run build`: Compila o app para produção

## Contribuindo

Contribuições são bem-vindas! Por favor, faça um fork do projeto e crie um Pull Request com suas mudanças.

Desenvolvido por [Roo Franklin](https://github.com/roofranklin)