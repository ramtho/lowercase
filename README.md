## How did I create this project?

#### Project Setup
1. Created project directory and change the directory


    $>`mkdir lowercase`


    $>`cd lowercase`
2. Created folder structure


    $>`mkdir src`


    $>`mkdir test`
3. Created README.md file
4. Initialised Git Repository and added remote repositiry


    $>`git init`


    $>`git remote add origin https://github.com/ramtho/lowercase.git`
5. Open Git Bash and add .gitignore file


    $>`touch .gitignore`

#### Package setup
1. Create a scoped package


    $>`cd src`


    $>`cd npm init --scope=ramtho`


    Followed command line instructions
2. Created a module

#### Testing module
1. Test the created module


    $>`cd test`
2. Create test file/project
3. Install the package


    $>`npm install /path/to/package`
4. Run test


    $>`node test-file-name`

#### Push code to git Repository
#### Publish package to registry
1. Login to npm registry user account


    $>`npm login`
2. Publish package to registry with public access


    $>`npm publish --access public`
