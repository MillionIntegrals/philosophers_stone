# PhilosophersStone

Various metaprogramming utilities for the Elixir language, mainly 
targeted at reducing boilerplate in writing Elixir/OTP applications.

Largely inspired by: https://github.com/sasa1977/exactor
by striving fore cleaner and more transparent implementation.

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add `philosophers_stone` to your list of dependencies in `mix.exs`:

    ```elixir
    def deps do
      [{:philosophers_stone, "~> 0.1.0"}]
    end
    ```

  2. Ensure `philosophers_stone` is started before your application:

    ```elixir
    def application do
      [applications: [:philosophers_stone]]
    end
    ```

