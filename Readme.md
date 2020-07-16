# github-now

![preview](/preview.png)

Update your profile with the song you are listening, using chrome extensions, in real time.

## Supported Platforms

- Youtube Music
- Soundcloud
- Spotify

## Howto

Beware it's WIP project;

1. Create and edit `README.Template.md` file in profile repository
2. Create github personal oauth token
3. Edit [background.ts](/src/background/background.ts), line 122 and 123, replace id and oauth token
4. `npm install && npm run build`
5. Install unpacked extension in chrome, `/dist`

## Templates

- `{CURRENT_PLAYING_SOURCE}`
- `{CURRENT_PLAYING_NAME}`
- `{CURRENT_PLAYING_ARTISTS}`
- `{CURRENT_PLAYING_ALBUM}`
- `{CURRENT_PLAYING_RELEASED}`
- `{CURRENT_PLAYING_ALBUM_SRC}`
- `{CURRENT_PLAYING_URL}`
- `{CURRENT_PLAYING_LAST_UPDATED}`

## Todo

- [ ] Account/OAuth config via extension settings
- [ ] More platform than youtube music
