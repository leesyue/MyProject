## 项目接口文件 
  | 接口名称 | 请求方式 | 请求示列 |
  | --- | ---- | ---- |
  | 正在热映 | get | http://39.97.33.178/api/movieOnInfoList?cityId=10 |
  | 即将上映 | get | http://39.97.33.178/api/movieComingList?cityId=10 |
  | 搜索 | get | http://39.97.33.178/api/searchList?cityId=10&kw=a |
  | 城市 | get | http://39.97.33.178/api/cityList |
  | 电影详情 | get | http://39.97.33.178/api/detailmovie?movieId=345808 |
  | 影院 | get | http://39.97.33.178/api/cinemaList?cityId=10 |
  | 城市定位 | get | http://39.97.33.178/api/getLocation |

## 技术要点
- [x] `vue`
- [x] `vuex`
- [x] `vue-router`
- [x] `better-scroll`
- [x] `proxy`
- [x] `axios`


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

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
