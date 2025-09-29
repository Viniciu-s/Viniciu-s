name: GitHub Profile Summary Cards

on:
  schedule: # atualiza todo dia à meia-noite UTC
    - cron: "0 0 * * *"
  workflow_dispatch: # permite rodar manualmente se quiser

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: vn7n24fzkq/github-profile-summary-cards@release
        env:
          GITHUB_TOKEN: ${{ secrets.READ_ME }}
        with:
          USERNAME: Viniciu-s
