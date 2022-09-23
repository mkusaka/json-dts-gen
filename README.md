# json-dts-gen
generate d.ts file from json

# usage

as default, this cli generate .d.ts file.
Its filename follows original yaml file, like original.yml, then generate original.d.ts .

```bash
npm i -g typescript
npx json-dts-gen [target yaml file]
```

# example

```bash
curl https://raw.githubusercontent.com/OAI/OpenAPI-Specification/master/examples/v3.0/petstore.json -o petstore.json
npx json-dts-gen petstore.json
```
