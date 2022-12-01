# Cadastro de carro

**Requisitos Funcionais**

- Deve ser possível cadastrar um novo carro.

**Regras de Negócio**

- Não deve ser possível cadastrar um carro com uma placa já existente.
- Não deve ser possível alterar a placa de um carro já cadastrado.
- O carro deve ser cadastrado, por padrão, com disponibilidade.
- O usuário responsável pelo cadastro deve ser um usuário administrador.

# Listagem de carros

**Requisitos Funcionais**

- Deve ser possível listar todos os carros disponíveis.
- Deve ser possível listar todos os carros disponíveis pelo nome da categoria.
- Deve ser possível listar todos os carros disponíveis pelo nome da marca.
- Deve ser possível listar todos os carros disponíveis pelo nome do carro.

**Regras de Negócio**

- O usuário não precisa estar logado no sistema.

# Cadastro de Especificação no carro

**Requisitos Funcionais**

- Deve ser possível cadastrar uma especificação para um carro

**Regras de Negócio**

- Não deve ser possível cadastrar uma especificação .para um carro não cadastrado.
- Não deve ser possível cadastrar uma especificação já existente para o mesmo carro.
- O usuário responsável pelo cadastro deve ser um usuário administrador.

# Cadastro de imagens do carro

**Requisitos Funcionais**

- Deve ser possível cadastrar a imagem do carro.

**Requisitos Não Funcionais**

- Utilizar o multer para o upload dos arquivos.

**Regras de Negócio**

- O usuário deve poder cadastrar mais de uma imagem para o mesmo carro.
- O usuário responsável pelo cadastro deve ser um usuário administrador.

# Aluguel de carro

**Requisitos Funcionais**

- Deve ser possível cadastrar um aluguel.

**Regras de Negócio**

- O aluguel deve ter duração mínima de 24 horas.
- Não deve ser possível cadastrar um novo aluguel caso já exista um aberto para o mesmo usuário.
- Não deve ser possível cadastrar um novo aluguel caso já exista um aberto para o mesmo carro.
