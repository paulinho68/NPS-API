# NPS - Net Promoter Score
Net Promoter Score is a metric that aims to measure customer satisfaction and loyalty with companies. Organizations of all sizes and places in the world use NPS as it is a practical and effective method during periodic surveys conducted with their customers.

### Project To Construct API

    - Techs:
        - Express: <https://expressjs.com/pt-br/guide/routing.html>
        - TypeOrm: <https://typeorm.io/#/>
        - Sqlite3: <https://www.sqlite.org/index.html>
        - Jest: <https://jestjs.io/>
        - Typescript: <https://www.typescriptlang.org/docs/>


## How can i start this project?

1.  Clone this project
2.  Into terminal
3.  Execute this steps:
    - yarn install
    - yarn typeorm migration:run
    - yarn dev

    **OBS:** If you want use test. pay attention:
        
        Change your package.json if necessary

        Windows: 

        "scripts": {
            "test": "set NODE_ENV=test&&jest",
            "posttest": "rimraf ./src/database/database.test.sqlite"
        }

        Linux:
        
        "scripts": {
            "test": "NODE_ENV=test jest",
            "posttest": "rm ./src/database/database.test.sqlite"
        }
        