# spotify-now-playing

A simple script to generate an SVG badge for your Spotify now playing status.

- can use in github readme (eg;- [Check my profile](https://github/amarnathcjd/amarnathcjd))

## Requirements

- sp_dc: copy the `sp_dc` cookie from `open.spotify.com` and set it as an environment variable ('SPOTIFY_COOKIE')

## Deploy To Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/amarnathcjd/spotify-now-playing)

## Usage

### SVG Badge

#### Markdown
```markdown
![Spotify Now Playing](https://<your-vercel-deployment-url>/api/current-playing?svg=true)
```

#### HTML
```html
<img src="https://<your-vercel-deployment-url>/api/current-playing?svg=true" alt="Spotify Now Playing">
```

### JSON Response

```bash
curl https://<your-vercel-deployment-url>/api/current-playing
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


