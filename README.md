# js-boiler-plate
This a Js Boiler Plate. Can be used with Node React or Angular Projects. 
Installs all the basic dependecies for a modern js Project

1. *** Step 1 ***
Commands run on the project 
    `npm init -y`   to Initialize the repo

Updated the package.json File

2. Creation of .editorconfig File for linting Code
This sets the format of code when code is written in basic editors. More details can be found om [EditorConfig](https://editorconfig.org/)

3. Other Code editors we use ES Lint. It brings consistency to code. 
Details about installing [ES Lint](https://eslint.org/) can be foud there.
`npm i -D eslint` 
To check if installed correctly run  `npx eslint` 


To set it up `npx eslint --init`  Follow the Instruction based on the project you installing

To try `npx eslint src/*.js`  To see the errors 

4. Install Prettier to format the code 
You can visit the site for more configuratins on [Prettier-eslint](https://github.com/prettier/prettier-eslint)

`npm i -D --save-dev prettier-eslint` 


`npm i -D --save-dev prettier-eslint-cli`   or `yarn add --dev prettier-eslint-cli` 

Update package.json file to 

            "scripts": {
                    "lint": "eslint '**/*.js'",
                    "lint:fix" : "prettier-eslint  '**/*.js' --write"
                },
        
`npm lint:fix`   to format the code


5. *** Step 5 ***
Installing Husky 
`npm i -D husky lint-staged`   