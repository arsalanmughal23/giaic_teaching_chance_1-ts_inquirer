# GIAIC Teaching Content
> ## Inquirer with Nodejs & Typescript 

> [!NOTE]
> ## How to Run Project
> Run the project by using given below command
  > ```
  > tsc && node .
  > ```

> [!TIP]
> ## Step by Step Guide
  - **Install inquirer** by using given command: ```npm i inquirer```
  - Then **import inquirer**
      - **Problem:**
        - ![image](https://github.com/arsalanmughal23/giaic_teaching_chance_1-ts_inquirer/assets/50748011/64d0a6d7-692d-4863-8654-df0adc7de24a)
      - **Solution:**
        - copy command (```npm i --save-dev @types/inquirer```) from error message, paste & run this cmd on your terminal.
  - Now we **Implement Inquirer**
      - ![image](https://github.com/arsalanmughal23/giaic_teaching_chance_1-ts_inquirer/assets/50748011/9459ac17-d22c-4145-9361-41bb8ae49ca0)
      - It looks fine no error is appering on the code
  - Now we are going to **Run the Code**
      - **Problem:**
        - ![image](https://github.com/arsalanmughal23/giaic_teaching_chance_1-ts_inquirer/assets/50748011/dda60fb1-a1f9-4121-87fe-3e946e2735bf)
      - **Solution:**
        - ![image](https://github.com/arsalanmughal23/giaic_teaching_chance_1-ts_inquirer/assets/50748011/57f9bc68-d3cd-45b6-8a0b-d617c697f6d6)
  - **Run After Fix ERR_REQUIRE_ESM**
      - **Problem:**
        - ![image](https://github.com/arsalanmughal23/giaic_teaching_chance_1-ts_inquirer/assets/50748011/4fdfc3b1-f18e-4569-ab04-3507847ced0c)
      - **Solution:**
        - add this line ```"type": "module",``` in the package.json file after the line of main property
        - then run the project again
  - **Run After Adding type:module in package.json**
      - **Problem:**
        - ![image](https://github.com/arsalanmughal23/giaic_teaching_chance_1-ts_inquirer/assets/50748011/0650a60b-8e01-46da-8fb4-a142f6e7887d)
      - **Solution:**
        - write await keyword before inquirer.prompt(
  - **Run After Write await keyword**
      - **Problem:**
        - ![image](https://github.com/arsalanmughal23/giaic_teaching_chance_1-ts_inquirer/assets/50748011/123888ee-7e74-4ad2-b151-c55d70e9f1db)
      - **Solution:**
        - set module to es2022 & set target to es2017 or higher
  - **Run After set tsconfig changes**
      - Great, it's successfully run
      - ![image](https://github.com/arsalanmughal23/giaic_teaching_chance_1-ts_inquirer/assets/50748011/54e33e1d-1b5a-44bf-9d74-3f6b98859971)
