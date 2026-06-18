# .github

## Pin actions version

```shell
npm install
npm run pin-actions
```


### Update already pinned actions

Update from:

```yaml
- uses: actions/setup-node@48b55a011bda9f5d6aeb4c2d9c7362e8dae4041e # v6
```

To:

```yaml
- uses: actions/setup-node@v7
```

Then run:

```shell
npm run pin-actions
```

### Add github token (API rate limit)

Create a `.env` containing :

```dotenv
GITHUB_TOKEN=<your-github-token>
```
