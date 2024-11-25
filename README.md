## Foundry

**Foundry é um kit de ferramentas ultrarrápido, portátil e modular para desenvolvimento de aplicações Ethereum, escrito em Rust.**

O Foundry consiste em:

- **Forge**: Framework de testes Ethereum (similar ao Truffle, Hardhat e DappTools).
- **Cast**: Canivete suíço para interagir com contratos inteligentes EVM, enviar transações e obter dados da blockchain.
- **Anvil**: Nó Ethereum local, semelhante ao Ganache e Hardhat Network.
- **Chisel**: REPL Solidity rápido, utilitário e detalhado.

## Documentação

https://book.getfoundry.sh/

## Uso

### Compilar

```shell
$ forge build
```

### Testar

```shell
$ forge test
```

### Formatar

```shell
$ forge fmt
```

### Snapshots de Gas

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Implantar

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <sua_url_rpc> --private-key <sua_chave_privada>
```

### Cast

```shell
$ cast <subcomando>
```

### Ajuda

```shell
$ forge --help
$ anvil --help
$ cast --help
```
