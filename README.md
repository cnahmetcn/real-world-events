# real-world-vue

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Json Database
```
npm i -g json-server
```

```
json-server --watch db.json
```

```
json-server -d 1500 db.json
```
1.5 saniye gecikmeyle işlem yapar

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

# App Architecture

EventService.js dosyası axios kullanarak json-server yardımıyla db.json a bağlanır. Ardından dönen sonuç yine EventService.js dosyasına gelir. 
Ardından store -> views -> components içerisinde döngü devam eder. 