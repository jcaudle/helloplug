# Helloplug

This is from working through _[Building a web framework from scratch in Elixir](https://codewords.recurse.com/issues/five/building-a-web-framework-from-scratch-in-elixir)_

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add `helloplug` to your list of dependencies in `mix.exs`:

    ```elixir
    def deps do
      [{:helloplug, "~> 0.1.0"}]
    end
    ```

  2. Ensure `helloplug` is started before your application:

    ```elixir
    def application do
      [applications: [:helloplug]]
    end
    ```

