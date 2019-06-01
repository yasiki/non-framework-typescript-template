# non-framework-typescript-template
my template

# procedure
on windows

1. npm init -y
2. npm install -D typescript
3. npx tsc --init
4. npm install -D webpack webpack-cli ts-loader
5. npx webpack init
   1. n
   2. ./src/index
   3. dist
   4. n
   5. SASS
6. mkdir src
7. copy nul src\index.ts
8. add to webpack.config.js
   1. rules
   ```javascript
	{
		test: /\.ts$/,
		use: [
			{
				loader: 'ts-loader'
			}
		]
	},
   ```
   2. resolve
   ```javascript
    resolve:{
	    extensions: ['.ts','.js']
    },
   ```
