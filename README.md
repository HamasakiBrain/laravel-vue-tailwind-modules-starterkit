<p style="display: flex; align-items:center; flex-wrap: wrap; max-width: 500px; justify-content: center; width: 100%;">
    <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" height="80" alt="Laravel Logo"></a>
    <a href="https://tailwindcss.com/" target="_blank">
        <picture>
            <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/tailwindlabs/tailwindcss/HEAD/.github/logo-dark.svg">
            <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/tailwindlabs/tailwindcss/HEAD/.github/logo-light.svg">
            <img alt="Tailwind CSS" src="https://raw.githubusercontent.com/tailwindlabs/tailwindcss/HEAD/.github/logo-light.svg"  height="30">
        </picture>
    </a>
</p>
<p style="display: flex; align-items:center; max-width: 500px; justify-content: center; width: 100%; ">
    <a href="https://vuejs.org" target="_blank" rel="noopener noreferrer">
        <img height="80" src="https://vuejs.org/images/logo.png" alt="Vue logo">
    </a>
    <a style="position: relative;">
        <img height="100" src="https://vitejs.dev/logo-with-shadow.png" alt="Vite logo" />
    </a>
</p>
<div style="z-index: -1;position: fixed;top: 0%;left: 0%;border-radius: 50%;width: 100%;height: 100%;background-image: linear-gradient(-45deg, rgb(189, 52, 254) 50%, rgb(71, 202, 255) 50%);filter: blur(300px);"></div>


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


4. Start the server  

~~~bash  
npm run dev
~~~

5. Build the server  

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
 
