# elixir-gotchas
A catalog of pitfalls in Elixir; all of my most irritating mistakes.

will build examples later -- noting pitfalls

a || b
|> moo()

is actually

a || (b |> moo())

surprising pipe-forward higher-precedence than ||



0 is TRUTHY





