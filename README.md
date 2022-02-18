# Blog

To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.setup`
  * Start Phoenix endpoint with `mix phx.server` or inside IEx with `iex -S mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Changesets

A changeset is a data structure that tells Ecto how to change your data. Its corresponding module – Ecto.Changeset – contains functions to create and operate with these data structures.

## Repo

While OOP language libraries like Ruby’s ActiveRecord act on (or create the illusion that they act on) objects – for example, you would write Post.find(1) – Ecto uses the Repo module as a mediator between you and the database, to which you submit commands that you want to get executed.

Repo.get(Post, 1)

Here’s a good article on the differences between ActiveRecord vs. Ecto.

If you need something, you ask Repo. If you want to insert something, you give it to Repo. If you don’t ask, you shall not receive. All communication with the database goes through Repo.

## Ecto query language

While the Repo module has some basic calls to the database, the chance is you will need something more. In the Ecto.Query module, you will find the tools to create custom, composable queries with the Ecto DSL.

## Learn more

  * Official website: https://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Forum: https://elixirforum.com/c/phoenix-forum
  * Source: https://github.com/phoenixframework/phoenix
