<p align="center">
<a href="https://laravel.com"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" height="70" alt="Laravel Logo"></a>
</p>
<p align="center">
<a href="https://tailwindcss.com/">
<picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/tailwindlabs/tailwindcss/HEAD/.github/logo-dark.svg" height="20">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/tailwindlabs/tailwindcss/HEAD/.github/logo-light.svg" height="20">
    <img alt="Tailwind CSS" src="https://raw.githubusercontent.com/tailwindlabs/tailwindcss/HEAD/.github/logo-light.svg"  height="20">
</picture>
</a>
</p>
<p align="center">
  <a href="https://vuejs.org" target="_blank" rel="noopener noreferrer">
        <img height="60" src="https://vuejs.org/images/logo.png" alt="Vue logo">
    </a>
    <a style="position: relative;">
        <img height="75" src="https://vitejs.dev/logo-with-shadow.png" alt="Vite logo" />
    </a>
</p>

# laravel-vue-tailwind-modules-starterkit   
This starter kit with Vue, Tailwindcss, Laravel modular architecture

## Create modules
Creating modules with `composer` package `nWidart/laravel-modules` with custom `stubs`

See module **documentation [here](https://docs.laravelmodules.com/v9/introduction)**
## Run Locally  
1. Clone the project

~~~bash  
git clone https://github.com/HamasakiBrain/laravel-vue-tailwind-modules-starterkit.git
~~~

2. Go to the project directory  

~~~bash  
cd laravel-vue-tailwind-modules-starterkit
~~~

3. Install all dependencies  
~~~bash  
npm run init
~~~
4. Copy .env.example to .env
~~~bash
cp .env.example .env
~~~
5. Create key for app
~~~bash
php artisan key:generate
~~~
6. Configure db connection in `.env`
7. Migrate migrations
~~~bash
php artisan migrate
~~~
8. Start the server  

~~~bash  
npm run dev
~~~

7. Build the server  

~~~bash  
npm run build
~~~
## Run Production  
1. Build your modules 

*Example*

```bash
cd /Modules/{Blog}/ && npm run build
```
*where **{Blog}** - your module name*

Then, go to root folder your project and run **build** app
```bash
cd /project/ && npm run build
```
And change **`local`** to **`production`** in **`.env`** const **`APP_ENV`**

*Example*
```bash
APP_ENV=production
```
## License  
[MIT](https://choosealicense.com/licenses/mit/)  
 
