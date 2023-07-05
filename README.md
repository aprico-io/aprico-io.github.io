### Dev

- [Install Hugo](https://gohugo.io/installation/)
- Install node and npm
- `$ npm install`
- `$ npm run dev` - will setup tailwindcss generation
- `$ hugo serve` - in new terminal serves a site at `http://localhost:1313`

### Deploy to firbease

- Install firebase tools globally

```bash
$ npm install -g firebase-tools
```

- Build the static site

```bash
$ hugo
```

- Authenticate with aprico.io account

```bash
$ firebase login
```

- Deploy to the https://aprico.io domain, settings are described in `firebase.json` file

```bash
$ firebase deploy --only hosting -m "Message describing deployment"
```
