## Ruby Discord & Telegram Bot Boilerplate

A boilerplate project for running Discord and Telegram bots together in a single Ruby application.
Perfect starting point if you want a clean structure, environment setup, and testing out of the box.

## Prerequisites

- Ruby 3.0^

## Installation

```
gem install sylvia
```

then

```
sylvia bot new_app
```

## Structure

<pre>
├── app/        # Bot logic (Discord, Telegram, controllers, model?)
├── bin/        # Executable entry point scripts
├── config/     # Configuration, including example .env
├── spec/       # RSpec test suite
├── Gemfile     # Project dependencies
├── Rakefile    # Build/test/automation tasks
├── .rubocop.yml    # Code linting rules
</pre>

## Setup and Configuration

#### Install dependencies

```
bundle install
```

#### Configure environment variables

Edit `config/.env` and set your credentials:

`TOKEN_DISCORD`, `CLIENT_ID_DISCORD`

`TOKEN_TELEGRAM`

`SERVER_ID_DISCORD` (optional, for Discord dev testing)

#### 5. Run Bot

```
./bin/START
```

#### 6. Single Run Bot

```
rake discord
```

or

```
rake telegram
```

## Unit Test

```
rake test
```

## License

MIT License

#### Credits

Created by `whdzera`

Feel free to fork, improve, or contribute via pull requests!
