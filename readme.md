# Discord CLI

Discord CLI is a shell implementation of the discord API, implemented in ruby.

### Why

At Bedrock Mentoring, we needed a way to measure how effective our marketing campaigns were at bringing aspiring programmers into our 
awesome discord community (helps land job interviews).

We quickly learned that the discord UI does not support the creation of unique channel unlimited invite tokens, which would allow us
to tie marketing campaign to them.

We later learnt however, that this is possible through the discord API.

Enter the `channel/create_invite` script, that allows us to create unique unlimited invite tokens (for a channel) quickly.

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
