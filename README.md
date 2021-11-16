# qa-checklist

> A GitHub App built with [Probot](https://github.com/probot/probot) that Checklist app that posts comments helpful reminders for QA checklists. 

## Setup

```sh
# Install dependencies
npm install

# Run the bot
npm start
```

## Docker

```sh
# 1. Build container
docker build -t qa-checklist .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> qa-checklist
```

## Contributing

If you have suggestions for how qa-checklist could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[ISC](LICENSE) © 2021 Bat Battur <b.bagy@yahoo.com>
