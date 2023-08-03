# gh-action-planton-cli-login

```yaml
    steps:
      - uses: actions/checkout@v3
      - uses: plantoncloud/gh-action-planton-cli-login@main
        with:
          planton_cloud_client_id: ${{ secrets.PLANTON_CLOUD_CLIENT_ID }}
          planton_cloud_client_secret: ${{ secrets.PLANTON_CLOUD_CLIENT_SECRET }}
```
