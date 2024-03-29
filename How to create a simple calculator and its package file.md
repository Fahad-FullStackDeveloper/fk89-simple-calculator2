Q:  How to create a simple calculator and its package file?
A:  In designated folder/directory open cmd and write down following commands:
    * Create new folder and Open "CMD/Terminal" by located folder where you want store your app data.
    * " npm init " (for creating "package.json" file)
    * " tsc --init " (for creating "tsconfig.json" file)
    * " code . " (open vs code in required folder)

MAKE CHANGES IN CREATED FILES:
        (a) "tsconfig.json" {( line#14 "ES2022" ), ( line#28 "NodeNext" ), ( line#30 un-comment & "NodeNext" )}
        (b) "package.json" { Add before Debug: ( "type": "module", )}
        (c) "package.json" { "bin": "index.js", } (for link your .ts file into npm/root and what tells which file to include for execute.)
    * create a '.ts' file
    * " tsc -w" (for watch and compile every code)
    * " npm i inquirer" in "CMD/Terminal" (download package file from https://www.npmjs.com/package/inquirer)
    * " npm i --save-dev @types/inquirer" (installation for save dev)
    * after writing code type in "CMD/Terminal" " node fileName.js " (to print in terminal/cmd)
    * " #! /usr/bin/env node " (after run/checking and completition of code, copy this code top of in .ts file.)
    * ' npm login ' (write in CMD/Terminal, before publishing) and then 'enter' for the login page webpage of npm.
    * ' npm publish ' (write in CMD/Terminal, for publishing)

AFTER PUBLISHING A PROGRAM TO NPM SITE:
    * ' npx fk89-simple-calculator2 ' (write in CMD/Terminal, for installation in system and run.)
    * Version Explaination: Ex.(1.0.2),     {1.(major update/release)0.(minor update/release)2(for minor bugs and typo fix)} 

    * Create README.md file in root directory and Save it. 
    * ' npm version patch ' (write in CMD/Terminal, for patching a version into root file)
    * ' npm publish ' (write in CMD/Terminal, for publishing)


CREATE A NEW GIT REPOSITORY ON THE COMMAND LINE:
    * ' echo "# npm-simple-calculator" >> README.md '
    * ' git init '
    * Creating ".gitignore" file (file names, for what not to add into repo)
    * ' git add README.md ' / ' git add . '(for all file add into repo)
    * ' git commit -m "push my calculator to github" OR "push message"'
        Author identity unknown
        *** Please tell me who you are.
            Run
            git config --global user.name "Fahad-FullStackDeveloper"
            git config --global user.email "fahad.dude2010@gmail.com"
            
        to set your account's default identity.
            Omit --global to set the identity only in this repository.
        fatal: unable to auto-detect email address (got 'Fahad@DESKTOP-KVJEOFQ.(none)')
    * ' git branch -M main '
    * ' git remote add origin https://github.com/Fahad-FullStackDeveloper/npm-simple-calculator.git '
    * ' git push -u origin main '
    * ' git add . '
…OR PUSH AN EXISTING REPOSITORY FROM THE COMMAND LINE:
    * ' git add . '
    OR
    * ' git remote add origin https://github.com/Fahad-FullStackDeveloper/npm-simple-calculator.git '
    * ' git branch -M main '
    * ' git push -u origin main '


