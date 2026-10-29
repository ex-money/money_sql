# TODO

Work on `ex_money_sql` is tracked here. There are no open items; the 2.2.0 release moved the library onto ex_money 6.3 and Localize 1.5.

## Done

* [x] **Changeset errors for exception structs** — the Ecto casts return a changeset error instead of raising when `Money.new/3` or `Money.parse/2` return an exception struct. 2026-10-30, v2.2.0.
