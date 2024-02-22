# Helm-Slack-Time-Localization-Bot

A Helm chart for the [Slack Time Localization Bot](https://github.com/Slack-Time-Localization-Bot/Slack-Time-Localization-Bot).

## Quickstart

```yaml
# values.yaml
environment:
  - name: SLACK_APP_TOKEN
    value: "changeme"
  - name: SLACK_BOT_TOKEN
    value: "changeme"
  - name: DEBUG
    value: "false"
```

```shell
helm repo add slack-time-localization-bot https://slack-time-localization-bot.github.io/Helm-Slack-Time-Localization-Bot/
helm repo update
helm install slack-time-localization-bot slack-time-localization-bot/slack-time-localization-bot --values values.yaml
```
