# Sass and PostCSS

## Sass Package
<p style="padding-left: 20px;">Install Sass with Node.js</p>

```
npm install node-sass
```
## Usage
```
var scss = require('node-sass');
sass.render({
	file: scss.filename,
	[, options..]
}.function(err, result)) {/*....*/}
//OR
var result = sass.renderSync({
	data: scss_content,
	[, options..]
});
```

## Command Line
<p style="padding-left: 20px;">Generate A new css file</p>

```
sass index.scss NewFile.css
```

<p style="padding-left: 20px;"> Print the compiled echo</p>

```
sass index.css
```
## Help

```
sass --help
```



