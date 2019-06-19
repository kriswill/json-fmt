# json-fmt

Compact JSON formatter for the command line

## Install

```sh
yarn global add https://github.com/kriswill/json-fmt
```

This will create a global command `json-fmt`

## Use

```
cat package.json | json-fmt
```

Emits formatted JSON to stdout, pipe to new files as you please..

```sh
echo "$(cat my.json | json-fmt)" >| my.json
```

Replaces `my.json` file with formatted JSON content


