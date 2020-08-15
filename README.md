# About
Learning [Rust and WebAssembly tutorial](https://rustwasm.github.io/docs/book/game-of-life/introduction.html)

[![Netlify Status](https://api.netlify.com/api/v1/badges/6f14ebb5-3da4-4411-af83-82374c97db09/deploy-status)](https://app.netlify.com/sites/wonderful-stonebraker-622f98/deploys)

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