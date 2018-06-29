# Scripts

My personal scripts

## Configuration

First of all, rename `config.ini.example` to `config.ini`

### Twitch
1. Register a new application at https://www.twitch.tv/kraken/oauth2/clients/new
    - Application name can be whatever
    - Enter `https://twitchapps.com/tokengen/` as Redirect URI
2. Get OAuth token from https://twitchapps.com/tokengen/
    - Enter the Client ID acquired from first step
    - Enter `user_read` as scope
3. Edit twitch section configs in `config.ini`
    - client_id: your client id from 1.step
    - oauth_token: your oauth token from 2.step
