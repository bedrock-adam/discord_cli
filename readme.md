# Discord CLI

Discord CLI is an (incomplete) shell interface to the discord API, implemented in ruby.

## Prerequisites

* ruby 2.6.5
* bundler

## Installation

Use [bundler](https://bundler.io/) to install Discord CLI.

```bash
bundle install
```

## Usage

```bash
BOT_TOKEN=<BOT_TOKEN> channel/create_invite
  --channel_id <CHANNEL_ID>
  --max_age <MAX_AGE>
  --max_uses <MAX_USES>
  --temporary <TEMPORARY>
  --unique <UNIQUE>

> Created invite
>         uses:           0
>         max_age:        0
>         max_uses:       0
>         temporary:      false
>         url:            https://discord.gg/AAAAAAAAAA
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
