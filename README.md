# Islands

> Web Application for Islands, a variation on battleship

Repository contains code from working through [Functional Web Development with Elixir, OTP, and Phoenix](https://pragprog.com/book/lhelph/functional-web-development-with-elixir-otp-and-phoenix) by Pragmatic Programmers.

## Initial Setup

Create the business logic:

```
mix new --sup islands_engine
```

**Note**: The `--sup` flag generates an OTP skeleton with a supervision tree. See the [Mix Documentation](https://hexdocs.pm/mix/Mix.Tasks.New.html) for all available flags.
