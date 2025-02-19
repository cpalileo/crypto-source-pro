# Crypto Source Pro

## USER STORY

Crypto Source Pro Updates
In order to add value to Crypto Source is included which will allow registered users to privately track their crypto assets in a "wallet snapshot". The tracking features that will be included are asset name, asset amount, asset value, and total wallet snapshot value.

Crypto Source Pro Basic
Given that cryptocurrencies are extremely volatile, prior to making an impulse buy I want to read up to the minute news that may affect the price of various coins or tokens. In order to do this, I need a quick and reliable way to pull headlines regarding specific coins or tokens.

## TECHNOLOGY USED

HTML, CSS, Bulma, Javascript, Sequelize, Sequelize CLI

## HOW TO SEED COIN TABLE

To seed the coin table, first install the sequelize CLI by running the command 'npm install --save-dev sequelize-cli' from your terminal. Next, type 'npx sequelize db:seed --seed 20220403004935-coin-seeder.js' to seed the table. If you accidentally run the seeder more than once simply type the command 'npx sequelize db:seed:undo:all' to undo your changes. If you undo the seeds you need to flush the table data by changing the force: false to force: true in server.js and run the command node server.js. Then change the force: true back to force: false to keep any new data. To reseed the Coin table re-enter the command 'npx sequelize db:seed --seed 20220403004935-coin-seeder.js'.

## Link:

https://github.com/cpalileo/crypto-source-pro

## Deployed App:

https://stark-badlands-81113.herokuapp.com/

## Link to Class Presentation:

https://docs.google.com/presentation/d/1Qkd8uBPnljyhYmo6u-wyBETnMA80Xuhq44f4U2-b6uU/edit?usp=sharing

## Draft Concepts:

https://miro.com/app/board/uXjVO_-AvgM=/?share_link_id=399106040098

https://miro.com/app/board/uXjVOACT98A=/?share_link_id=728404784014

## Screenshot

![ScreenShot](https://raw.githubusercontent.com/cpalileo/crypto-source-pro/main/public/assets/images/CSP-Screen.jpg)

## Contributors

Jason Greena, Devin Reina, Christopher Palileo, Giang Nguyen, Andrew Nohr, Sally Chan

## Updated Portfolio for Christopher Palileo

https://cpalileo.github.io/cpalileo-portfolio/
