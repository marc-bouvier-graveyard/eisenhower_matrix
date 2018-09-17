# Daily log - Eisenhower matrix in elixir

## Bootstrapping project

Pheonix project without Ecto.

```
mix phx.new --no-ecto eisenhower_matrix
* creating eisenhower_matrix/config/config.exs
* creating eisenhower_matrix/config/dev.exs
* creating eisenhower_matrix/config/prod.exs
* creating eisenhower_matrix/config/prod.secret.exs
* creating eisenhower_matrix/config/test.exs
* creating eisenhower_matrix/lib/eisenhower_matrix/application.ex
* creating eisenhower_matrix/lib/eisenhower_matrix.ex
* creating eisenhower_matrix/lib/eisenhower_matrix_web/channels/user_socket.ex
* creating eisenhower_matrix/lib/eisenhower_matrix_web/views/error_helpers.ex
* creating eisenhower_matrix/lib/eisenhower_matrix_web/views/error_view.ex
* creating eisenhower_matrix/lib/eisenhower_matrix_web/endpoint.ex
* creating eisenhower_matrix/lib/eisenhower_matrix_web/router.ex
* creating eisenhower_matrix/lib/eisenhower_matrix_web.ex
* creating eisenhower_matrix/mix.exs
* creating eisenhower_matrix/README.md
* creating eisenhower_matrix/test/support/channel_case.ex
* creating eisenhower_matrix/test/support/conn_case.ex
* creating eisenhower_matrix/test/test_helper.exs
* creating eisenhower_matrix/test/eisenhower_matrix_web/views/error_view_test.exs
* creating eisenhower_matrix/lib/eisenhower_matrix_web/gettext.ex
* creating eisenhower_matrix/priv/gettext/en/LC_MESSAGES/errors.po
* creating eisenhower_matrix/priv/gettext/errors.pot
* creating eisenhower_matrix/lib/eisenhower_matrix_web/controllers/page_controller.ex
* creating eisenhower_matrix/lib/eisenhower_matrix_web/templates/layout/app.html.eex
* creating eisenhower_matrix/lib/eisenhower_matrix_web/templates/page/index.html.eex
* creating eisenhower_matrix/lib/eisenhower_matrix_web/views/layout_view.ex
* creating eisenhower_matrix/lib/eisenhower_matrix_web/views/page_view.ex
* creating eisenhower_matrix/test/eisenhower_matrix_web/controllers/page_controller_test.exs
* creating eisenhower_matrix/test/eisenhower_matrix_web/views/layout_view_test.exs
* creating eisenhower_matrix/test/eisenhower_matrix_web/views/page_view_test.exs
* creating eisenhower_matrix/.gitignore
* creating eisenhower_matrix/assets/brunch-config.js
* creating eisenhower_matrix/assets/css/app.css
* creating eisenhower_matrix/assets/css/phoenix.css
* creating eisenhower_matrix/assets/js/app.js
* creating eisenhower_matrix/assets/js/socket.js
* creating eisenhower_matrix/assets/package.json
* creating eisenhower_matrix/assets/static/robots.txt
* creating eisenhower_matrix/assets/static/images/phoenix.png
* creating eisenhower_matrix/assets/static/favicon.ico

Fetch and install dependencies? [Yn] y
* running mix deps.get
* running mix deps.compile
* running cd assets && npm install && node node_modules/brunch/bin/brunch build

We are all set! Go into your application by running:

    $ cd eisenhower_matrix

Start your Phoenix app with:

    $ mix phx.server

You can also run your app inside IEx (Interactive Elixir) as:

    $ iex -S mix phx.server
```
