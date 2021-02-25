# Rocketpay

To start your Phoenix server:

  * Create docker postgres database `docker run --name postgres -e POSTGRES_PASSWORD=postgres -p 5432:5432 -d postgres`
  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.setup`,  `mix ecto.create` and `mix ecto.migrate` 
  * Start Phoenix endpoint with `mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.


## What I`ve learn ?

  * Create a phoenix project
  * Configure ElixirLS, Elixir Linter and Credo
  * Understand a Phoenix Project Structure
  * Phoenix Routes and Controllers
  * Elixir Imutability Principle
  * Pattern Matching
  * Pipe Operator
  * Enum and Stream
  * Create and execute automated tests
  * Create migrations with Ecto
  * Create and using tables witch Ecto Schema
  * Validate data with Changeset and Pattern Matching
  * Combine Bcrypt and Changeset and virtual fields to create hashed fields
  * Use Repo module
  * Use facade to separate business logic
  * Response data with maps
  * Handle controller errors with Fallback Controller
  * Simple schemas associations (:belongs_to and :has_one)
  * Retrive associated data with Repo.preload
  * Transaction management with Ecto.Multi
  * Apply constrain in migrations

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Learn more

  * Official website: https://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Forum: https://elixirforum.com/c/phoenix-forum
  * Source: https://github.com/phoenixframework/phoenix
