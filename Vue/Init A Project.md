name: test

author: SAMPUNG

email: illhyearn@163.com>

1. Init project with vue-cli@3 and webpack

```shell
vue init webpack test
```
  1. When: 

  ```shell
  ? Project name (test)
  ```
  Press 【Enter】, result:

  ```shell
  ? Project name test
  ```

  2. When: 

  ```shell
  ? Project description (A Vue.js project)
  ```
  Press 【Enter】, result:

  ```shell
  ? Project description A Vue.js project
  ```

  3. When: 

  ```shell
  ? Author (SAMPUNG <illhyearn@163.com>)
  ```
  Press 【Enter】, result:

  ```shell
  ? Author SAMPUNG <illhyearn@163.com>
  ```

  4. When: 

  ```shell
  ? Vue build (Use arrow keys)

  ? Install vue-router? Yes

  > Runtime + Compiler: recommended for most users

    Runtime-only: about 6KB lighter min+gzip, but templates (or any Vue-specific HTML) are ONLY allowed in .vue files - render functions are required elsewhere
  ```
  Press 【Enter】, result:

  ```shell
  ? Vue build standalone
  ```

  5. When: 

  ```shell
  ? Install vue-router? (Y/n)
  ```

  Press 【Enter】, result:

  ```shell
  ? Install vue-router? Yes
  ```

  6. When: 

  ```shell
  ? Use ESLint to lint your code? (Y/n)
  ```

  Press 【Enter】, result:

  ```shell
  ? Use ESLint to lint your code? Yes
  ```

  7. When: 

  ```shell
  ? Pick an ESLint preset (Use arrow keys)

  > Standard (https://github.com/standard/standard)

    Airbnb (https://github.com/airbnb/javascript)

    none (configure it yourself)
  ```

  Press 【Enter】, result:

  ```shell
  ? Pick an ESLint preset Standard
  ```
  
  8. When: 

  ```shell
  ? Set up unit tests (Y/n)
  ```

  Press 【n】 then 【Enter】, result:

  ```shell
  ? Set up unit tests No
  ```

  Or press 【Enter】, result:

  ```shell
  ? Set up unit tests Yes
  ```

  Then when: 

  ```shell
  ? Pick a test runner (Use arrow keys)

    Jest

  > Karma and Mocha

    none (configure it yourself)
  ```
  Press 【Enter】, result:

  ```shell
  ? Pick a test runner karma
  ```

  9. When: 

  ```shell
  ? Setup e2e tests with Nightwatch? (Y/n)
  ```

  Press 【Enter】 , result:

  ```shell
  ? Setup e2e tests with Nightwatch? Yes
  ```

  Or press 【n】 then 【Enter】, result:

  ```shell
  ? Setup e2e tests with Nightwatch? No
  ```

  10. When：

  ```shell
  ? Should we run `npm install` for you after the project has been created? (recommended) (Use arrow keys)

  > Yes, use NPM

    Yes, use Yarn
 
    No, I will handle that myself
  ```

  Press 【Enter】, result:

  ```shell
  ? Should we run `npm install` for you after the project has been created? (recommended) npm
  ```

3. For axios

```shell
vue add axios
```

4. For view-design(iview)

```shell
vue add iview
```

  1. When: 

  ```shell
  ? How do you want to import ViewUI(iView)? (Use arrow keys)

    Fully import

  > Import on demand
  ```

  Press 【↓】 to select "Import on demand", then press【Enter】, result:

  ```shell
  ? How do you want to import ViewUI(iView)? Import on demand
  ```

  2. When: 

  ```shell
  ? Choose the locale you want to load (Use arrow keys)

  > zh-CN

    zh-TW

    cs-CZ

   de-DE

   el-GR

   en-US

   es-ES
 
  (Move up and down to reveal more choices)
  ```

  Press 【Enter】, result:

  ```shell
  ? Choose the locale you want to load zh-CN
  ```

  3. Then input: 

  ```shell
  npm add babel-plugin-import
  ```

5. For Promise

```shell
npm install --save babel-polyfill
```
