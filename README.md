1. intro to course
2. install dev tools
3. create angular app
   - create project's folder
   - install @angular/cli
   - create app as frontend
4. add header
   - generate component
   - add html
   - add scss
5. list foods
   - create food model
   - create data.ts
     - add sample foods
   - add images to assets
   - create food service
   - create home component
     - add ts
     - add html
     - add scss
6. search
   - add method to food service
   - add search route
   - show search result in home component
   - generate search component
     - add ts
     - add html
     - add scss
7. tags bar
   - create tag model
   - add sample tags to data.ts
   - food service
     - add get all tags method
     - add get all tags by tag method
   - add tags route
   - show tag result in home component
   - generate tags component
     - add ts
     - add html
     - add scss
8. food page
   - add method to food service
   - generate food pag component
     - add route
     - add ts
     - add html
     - add scss
9. cart page
   - create CartItem model
   - create cart model
   - generate cart service
   - add to cart button in food page
   - generate cart page component
     - add route
     - add ts
     - add html
     - add scss
10. not found!
    - generate component
      - add ts
      - add html
      - add scss
    - add to pages
      - home page
      - cart page
      - food page
11. connect to backend
    - create backend folder
    - npm init -y
    - npm install typescript
    - create tsconfig.json (tsc --init)
    - create .gitignore
    - copy data.ts to backend/src
    - npm install express/cors
    - create server.ts
      - install @types
      - add apis
    - npm install ts-node --save-dev & nodemon --save-dev
    - add urls.ts to frontend
    - add HttpClient method
    - update food servicee
12. login page
    - generate login component
      - add to routes
      - add ts
      - add html
        - import reactive forms module
      - add scss
    - add login api
      - add josn
      - add jsonwebtoken
      - test using postman
    - generate user service
      - generate user model
      - add user subject
      - add login model
        - add user urls
        - generate iuserlogin interface
        - add ngx-toastr
          - import module
          - import browseranimationsmodule
          - add styles in angular.json
        - add to header
      - add local storage methods
      - add logout method
        - add to header
13. make components for login page
    - input container
    - input validation
    - text input
    - default button
14. connect login api to mongodb atlas
    - moving apis into routers
    - create mongodb atlas
    - create .env file
    - install the ff:
      - mongoose
      - dotenv
      - bcryptjs
      - jsonwebtoken
      - express-async-handler
    - connect to mongodb atlas
    - use mongodb instead of data.ts in apis
