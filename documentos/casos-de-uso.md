# Casos de Uso - Sistema de Aluguel de Carros


# Caso de Uso 01 - Realizar aluguel de um veículo


## Ator Principal

Cliente


## Objetivo

Permitir que o cliente escolha e alugue um veículo disponível no sistema.


## Pré-condições

- O cliente deve possuir cadastro no sistema.
- Deve existir pelo menos um veículo disponível.


## Fluxo Principal

1. O cliente acessa o sistema.
2. O cliente informa seus dados ou realiza login.
3. O cliente consulta os veículos disponíveis.
4. O cliente escolhe um veículo.
5. O sistema verifica a disponibilidade do veículo.
6. O cliente confirma o aluguel.
7. O sistema registra o contrato de aluguel.
8. O sistema informa que o aluguel foi realizado.


## Fluxo Alternativo

- Caso o veículo escolhido esteja indisponível, o sistema deve informar ao cliente e apresentar outros veículos.


## Pós-condição

O aluguel é registrado no sistema e o veículo fica reservado para o cliente.



---

# Caso de Uso 02 - Devolução do veículo


## Ator Principal

Funcionário da locadora


## Objetivo

Permitir que o funcionário registre a devolução de um veículo alugado.


## Pré-condições

- O veículo deve estar registrado como alugado.
- O cliente deve entregar o veículo.


## Fluxo Principal

1. O cliente entrega o veículo na locadora.
2. O funcionário consulta o aluguel no sistema.
3. O funcionário verifica as condições do veículo.
4. O funcionário registra a devolução.
5. O sistema calcula possíveis valores adicionais.
6. O sistema atualiza o status do veículo para disponível.
7. O sistema confirma a devolução.


## Fluxo Alternativo

- Caso o veículo apresente problemas ou danos, o funcionário registra uma observação no sistema.


## Pós-condição

O veículo retorna para a lista de veículos disponíveis para novos aluguéis.
