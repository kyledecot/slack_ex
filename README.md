# Slack

A client for the Slack API.

## Usage

Most of the API methods work by first creating a Slack client
(`Slack.client(token)`) and then passing it in to an API call. Note that a
`Slack.Client` is only a convenience wrapper for a map with a `:token` key.

```elixir
token
|> Slack.client
|> Slack.Channel.create(name: "mynewchannel")
```

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add `slack` to your list of dependencies in `mix.exs`:

    ```elixir
    def deps do
      [{:slack, "~> 0.0.9"}]
    end
    ```

## Todo

- [x] `Slack.API`
- [x] `Slack.Auth`
- [x] `Slack.Bot`
- [x] `Slack.Channel`
- [x] `Slack.Chat`
- [x] `Slack.DND`
- [x] `Slack.Emoji`
- [x] `Slack.File.Comment`
- [x] `Slack.File`
- [x] `Slack.Group`
- [x] `Slack.IM`
- [x] `Slack.MPIM`
- [x] `Slack.OAuth`
- [x] `Slack.Pin`
- [x] `Slack.Reaction`
- [x] `Slack.Reminder`
- [x] `Slack.RTM`
- [x] `Slack.Search`
- [x] `Slack.Star`
- [x] `Slack.Team`
- [x] `Slack.Team.Profile`
- [x] `Slack.UserGroup`
- [x] `Slack.UserGroup.User`
- [x] `Slack.User`
- [x] `Slack.User.Profile`
