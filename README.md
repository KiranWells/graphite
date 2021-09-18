# Graphite

A node-base data manipulation app.

## Project setup
```sh
npm install
# run the following once to download and compile
# the needed rust crates
npm run tauri:serve
```

The UI side (Javascript, Vue, etc.) is in the `src/` folder, while the Rust backend is located in `src-tauri/src`.

### Compiles and hot-reloads for development
```sh
npm run tauri:serve
```

### Compiles and minifies for production
```sh
npm run tauri:build
```

### Lints and fixes files
```sh
npm run lint
```

## Dependencies/Reference

- [Tauri](https://tauri.studio/)
- [Vue](https://vuejs.org/)
- [Vuex](https://vuex.vuejs.org/)

## Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
