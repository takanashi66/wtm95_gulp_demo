# gulpfile

## プラグイン

+ browser-sync
+ gulp-sass
+ gulp-plumber
+ gulp-notify
+ gulp-autoprefixer
+ gulp-sourcemaps
+ gulp-merge-media-queries

### プラグインのインストール

```
npm install --save-dev gulp browser-sync gulp-plumber gulp-sass gulp-notify gulp-autoprefixer gulp-sourcemaps gulp-merge-media-queries
```


## このでものディレクトリマップ

```
project/
	├ htdocs/
	│		├ common/
	│	  │ 	├ sass/
	│	  │ 	├ css/
	│	  │ 	├ map/
	│	  │ 	├ img/
	│	  │ 	└ js/	
	│		└index.html
	│
	├ .git/
	├ node_modules/
	├ gulpfile.js
	└ package.json
  
```


## もしプラグインが壊れていた場合

```
npm rebuild [壊れてたプラグイン名]
```
