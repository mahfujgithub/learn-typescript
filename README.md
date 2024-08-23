### Installation by Clone the repository
* Open your terminal and run the commands,
<br>

``` git clone https://github.com/mahfujgithub/learn-typescript.git ```

``` cd learn-typescript ```

``` npm install ```

``` npm start ```


## Follow the Steps to Install Manually

* You need to download and install NodeJS globally in Your Machine.
* Same as need to install __TypeScript__ globally by this command,
<br>

``` npm i -g typescript ```

* Need to initialize a typescript config file by,
<br>

``` tsc -init ```

* You can install __ts-node-dev__ npm package to see live output on your terminal by,
<br>

``` npm i ts-node-dev ```

* Add a script to your __package.json__ file to run __ts-node-dev__,
<br>

``` "start": "ts-node-dev --respawn --transpile-only index.ts" ```

* It's ready to run, now write code into your __index.ts__ file and get output by run the command,
<br>

``` npm start ```