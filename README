# required

* [./jq](https://stedolan.github.io/jq/)

# usage

## setup

```bash
# create directory contains request body json files
mkdir github_status

# create request body json file
echo '{"foo": "bar"}' > github_status/something.json

# setup META file
echo 'URL=https://status.github.com/api.json' >> github_status/META
echo 'METHOD=GET' >> foo/META
echo 'SAVE_RESPONSE=yes' >> github_status/META
```

## command

* request via META settings
    * `json-curl ./github_status/something.json`
* override URL
    * `json-curl -u http://example.com/something/api ./path/to/request/body.json`
* override METHOD
    * `json-curl -m POST ./path/to/request/body.json`
* force save response (when META.SAVE_RESPOSNSE is not "yes")
    * `json-curl -s ./path/to/request/body.json`

