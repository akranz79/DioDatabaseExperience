# DioDatabaseExperience_E-Commerce
Repositório de exercicios do bootcamp Database Experience
Este primeiro exercicio foi realizado a modelagem do banco de dados de E-Commerce e os refinamentos solicitados, conforme descritos abaixo:

1º - Cliente PJ e PF - Uma conta pode ser PJ ou PF, mas não pode ter as duas informações.
Solução: Foi criado uma entidade Cliente como gerenalização e Pessoa Fisica e Pessoa Juridica como especialização, herdando os atributos de Cliente.
2º - Pagamento - Pode ter cadastrado mais de uma forma de pagamento.
Solução: Foi criado uma entidade Pagamento, para persistir as formas de pagamento, com os atributos de cartão débito/crédito, bandeira, numero, etc
e criado um relacionamento um para varios com a entidade cliente. Ou seja, um cliente pode cadastrar um ou muitos cartões.
3º - Entrega – Possui status e código de rastreio.
Solução: Foi criado para este requisito uma entidade Entrega, com os atributos Status, Codigo de rastreio e data. E um relacionamento com a entidade 
pedido, um para um, ou seja, para cada pedido, será associado uma data de entrega.

Possiveis refinamentos poderão acontecer no decorrer do período até o termino do bootcamp.
