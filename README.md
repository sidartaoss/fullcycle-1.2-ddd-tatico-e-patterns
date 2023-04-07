# DDD - Modelagem Tática e Patterns: Desafio Eventos de Customer

Este desafio consiste em:

- Implementar 2 Eventos de Domínio ligados ao Agregado _Customer_:

  - O primeiro evento deverá acontecer assim que um novo _Customer_ for criado. Serão criados 2 _event handlers_ para esse evento:

    - _EnviaConsoleLog1Handler_. Deverá exibir no console: "Esse é o primeiro _console.log_ do evento: _CustomerCreated_";

    - _EnviaConsoleLog2Handler_. Deverá exibir no console: "Esse é o segundo _console.log_ do evento: _CustomerCreated_";

  - O segundo evento deverá acontecer assim que o endereço de _Customer_ for alterado. Será criado 1 (um) _event handler_ para esse evento:

    - _EnviaConsoleLogHandler_. Deverá exibir no console: "Endereco do cliente {_id_}, {_name_} alterado para: {_street_}, {_number_}, {_city_}"

> N.T.: Linguagem de programação para este desafio: _TypeScript_.

```
/src/domain/event/@shared/event-dispatcher.spec.ts
```
