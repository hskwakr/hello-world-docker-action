# hello-world-docker-action

[Docker コンテナのアクションを作成する - GitHub Docs](https://docs.github.com/ja/actions/creating-actions/creating-a-docker-container-action "Docker コンテナのアクションを作成する - GitHub Docs")

このアクションは"Hello World"もしくは"Hello" + ログに挨拶する人物名を出力します。

## Inputs

## `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

## `time`

The time we greeted you.

## Usage

uses: actions/hello-world-docker-action@v1
with:
  who-to-greet: 'Mona the Octocat'
