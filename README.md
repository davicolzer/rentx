# Cadastro de carro
**Requisito funcional**

Deve ser possível cadastrar um novo carro
Deve ser possível listar todas as categorias.

**Regra de negócio**

Não deve ser possível cadastrar um carro com uma placa já existente.
O carro deve ser cadastrado, por padrão, com disponibilidade.
* O usuário responsável pelo cadastro deve ser um usuário administrador.

# Listagem de carros
**Requisito funcional**

Deve ser possível listar todos os carros disponíveis.
Deve ser possível listar todos os carros disponível pelo nome da categoria
Deve ser possível listar todos os carros disponível pelo nome da marca
Deve ser possível listar todos os carros disponível pelo nome do carro

**Regra de negócio**

O usuário não precisa estar logado no sistema.

# Cadastro de especificação no carro
**Requisito funcional**

Deve ser possível cadastrar uma especificação para um carro
Deve ser possível listar todas as especificações
Deve ser possível listar todos os carros

**Regra de negócio**

Não deve ser possível cadastrar uma especificação para um carro não cadastrado
Não deve ser possível cadastrar uma especificação já existente para o mesmo carro.
O usuário responsável pelo cadastro deve ser um usuário administrador.

# Cadastro de imagens do carro
**Requisito funcional**

Deve ser possível cadastrar a imagem do carro
Deve ser possível listar todos os carros

**Requisito não funcional**

Utilizar o multer para upload dos arquivos

**Regra de negócio**

O usuário deve poder cadastrar mais de uma imagem para o mesmo carro
O usuário responsável pelo cadastro deve ser um usuário administrador.

# Aluguel de carro

**Requisito funcional**

Deve ser possível cadastrar um aluguel

**Regra de negócio**

O aluguel deve ter duração miníma de 24 Horas.
Não deve ser possível cadastrar um novo aluguel caso já exista um aberto para o mesmo usuário.
Não deve ser possível cadastrar um novo aluguel caso já exista um aberto para o mesmo carro.