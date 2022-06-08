# Exthereum Blockchain [![CircleCI](https://circleci.com/gh/exthereum/blockchain.svg?style=svg)](https://circleci.com/gh/exthereum/blockchain)

Elixir implementation of Ethereum's Blockchain. This includes functionality to build and verify a chain of Ethereum blocks that may be advertised from any peer. We complete the resultant state of the blocktree and form a canonical blockchain based on difficulty.

## Installation

```bash
export "CFLAGS=-I/usr/local/include -L/usr/local/lib"
cd deps/libsecp256k1 && rebar compile
mix compile
```

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `blockchain` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [{:blockchain, "~> 0.1.2"}]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/blockchain](https://hexdocs.pm/blockchain).

