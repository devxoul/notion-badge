# Notion Badge

Embed App Store badge in Notion.

## Usage

1. Add an Embed block

    <img width="400" alt="Embed" src="https://user-images.githubusercontent.com/931655/94790272-02088500-0411-11eb-82a8-446f4186ec1e.png">

2. Type link (See [API](#API) below)

    <img width="400" alt="Link" src="https://user-images.githubusercontent.com/931655/94794501-ed2ef000-0416-11eb-9b96-8574e7934a4f.png">

3. Voilà!

    <img width="400" alt="Voilà" src="https://user-images.githubusercontent.com/931655/94793883-1dc25a00-0416-11eb-8e22-50e7e3f6e257.png">

## API

#### Base URL

https://devxoul.github.io/notion-badge

#### Supported parameters

| Name | Description | Example |
|---|---|---|
| `id` | App Store [App ID](https://analytics.itunes.apple.com/#/campaigngenerator) _(Required)_ | `1519748688` |
| `pt` | App Store [Provider ID](https://analytics.itunes.apple.com/#/campaigngenerator) (default: none) | `121657414` |
| `ct` | App Store [Campaign Name](https://analytics.itunes.apple.com/#/campaigngenerator) (default: none) | `My%20Campaign` |
| `w` | Badge width (default: 120) | `160` |

#### Examples

* Example Notion page:

    https://www.notion.so/Notion-Badge-Example-d81d1ec971694388a3ca0da119a3cfa3

* Example badge URL:

    https://devxoul.github.io/notion-badge?id=1519748688&pt=121657414&ct=GitHub%20notion-badge&w=200

## License

notion-badge is under MIT license. See the [LICENSE](#LICENSE) file for more info.
