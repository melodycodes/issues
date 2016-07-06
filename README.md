# Issues

Elixir project to fetch _n_ issues from a Github project and display them in a table. Taken from [_Programming Elixir 1.2_](https://pragprog.com/book/elixir12/programming-elixir-1-2) by Dave Thomas.

## Usage

```
issues <user> <project> [ count | 4 ]
```

For help:
```
issues -h
```

## Example use
```
$ ./issues elixir-lang elixir 3
numb | created_at           | title
-----+----------------------+--------------------------------------------------
3328 | 2015-05-14T15:00:37Z | Support delayed evaluation of code in .iex.exs
3400 | 2015-06-17T13:04:45Z | Float.round is inconsistent
3413 | 2015-06-21T07:58:03Z | Remove Float.to_string/2 and Float.to_char_list/2...
```
