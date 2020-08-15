## Generate wasm package
```
wasm-pack build
```

## Link package
```
 cd pkg && yarn link && cd ../www && yarn link wasm-game-of-life
```

## launch local web server
1. move to `./www`
2. run `yarn run start`
   
## production build
1. move to `./wwww`
2. run `yarn run build`