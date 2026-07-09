# VibeNest Template: Actual Budget

This is a thin VibeNest-ready deploy adapter for [Actual Budget](https://github.com/actualbudget/actual).

It does not fork or modify Actual. The repo only provides explicit Docker defaults for the sync server:

- official image: `actualbudget/actual-server:latest`
- app port: `5006`
- persistent `/data` volume
- conservative upload limits

## VibeNest notes

One-click deploy stays disabled until smoke confirms the public URL opens Actual and a 256 MB memory check passes. Treat budget data as private and keep the volume backed up.

## Upstream

- Product: https://github.com/actualbudget/actual
- Docker docs: https://actualbudget.org/docs/install/docker/
