# CarzCo (A sample car dealership website)

This is a sample project for a car dealership website using MySQL and Laravel.

## Installation

> We assume that you have a web server and MySQL installed in your device

> You might need to set permissions to the storage directory in Linux

1. Run these lines of code to your web server's root
```
git clone https://github.com/locwa/The-Vault.git 
git submodules update --init --recursive
```
2. Go to the `The-Vault-Customer-Facing` directory and configure your `.env` file. An `.env.example` file is provided, edit that and change the file name to `.env` when you're done
3. Run these lines of code to install all dependencies
```
composer install
npm install
php artisan migrate
```
4. Repeat steps 2 and 3 for `The-Vault-Collection-Portal`

5. (OPTIONAL) Import all tables from The-Vault-SQL-Tables after migration to use the sample photos here : https://drive.google.com/uc?export=download&id=1j6vKoP436jSr_F1gFgjqdkwPAqjljyti
   
6. Open the public folder of `The-Vault-Collection-Customer-Facing` or `The-Vault-Collection-Portal` in your web server

7. To register an account, go to <link to The-Vault-Collection-Portal>/public/register
