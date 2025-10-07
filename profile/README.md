Most projects of Combo Lab are forks of existing work rather than built from scratch. We maintain original licenses and do our best to honor all license requirements. If you notice any license compliance issues, please reach out, we're committed to making things right.

**Thank you** to all the open source developers whose work made these projects possible.

---

Combo Lab is currently working on the following projects.

## combo

[`combo`](https://github.com/combo-lab/combo) started as a fork of [`phoenix`](https://github.com/phoenixframework/phoenix) with following goals:

- Build a focused MVC web framework. Strip down to core web framework essentials.
- Consolidate related dependencies:
  - Merge `phoenix_template`, `phoenix_html`, `phoenix_live_reload`, and other tightly coupled packages.
  - Extract the HEEx template engine from `phoenix_live_view` while removing the `phoenix_live_view` dependency entirely.
- Modernize frontend integration - Embrace the frontend ecosystem rather than resist it.

Although `combo` will continue to track `phoenix` changes, full compatibility is not guaranteed.

Related projects:

- [`combo_new`](https://github.com/combo-lab/combo_new)
- [`combo_pubsub`](https://github.com/combo-lab/combo_pubsub)
- [`combo_ecto`](https://github.com/combo-lab/combo_ecto)
- [`combo_vite`](https://github.com/combo-lab/combo_vite)
- [`combo_inertia`](https://github.com/combo-lab/combo_inertia)
