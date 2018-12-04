# laravel-mix-v4-test

After running `npm run dev`, it shows

```
ERROR in ./resources/assets/sass/app.scss
Module build failed (from ./node_modules/css-loader/index.js):
ModuleNotFoundError: Module not found: Error: Can't resolve './images/a.png' in '/home/user/laravel-mix-v4-test/resources/assets/sass'
    at factory.create (/home/user/laravel-mix-v4-test/node_modules/webpack/lib/Compilation.js:821:10)
    at factory (/home/user/laravel-mix-v4-test/node_modules/webpack/lib/NormalModuleFactory.js:397:22)
    at resolver (/home/user/laravel-mix-v4-test/node_modules/webpack/lib/NormalModuleFactory.js:130:21)
    at asyncLib.parallel (/home/user/laravel-mix-v4-test/node_modules/webpack/lib/NormalModuleFactory.js:224:22)
    at /home/user/laravel-mix-v4-test/node_modules/neo-async/async.js:2825:7
    at /home/user/laravel-mix-v4-test/node_modules/neo-async/async.js:6886:13
    at normalResolver.resolve (/home/user/laravel-mix-v4-test/node_modules/webpack/lib/NormalModuleFactory.js:214:25)
    at doResolve (/home/user/laravel-mix-v4-test/node_modules/enhanced-resolve/lib/Resolver.js:184:12)
    at hook.callAsync (/home/user/laravel-mix-v4-test/node_modules/enhanced-resolve/lib/Resolver.js:238:5)
    at _fn0 (eval at create (/home/user/laravel-mix-v4-test/node_modules/tapable/lib/HookCodeFactory.js:32:10), <anonymous>:15:1)
    at resolver.doResolve (/home/user/laravel-mix-v4-test/node_modules/enhanced-resolve/lib/UnsafeCachePlugin.js:37:5)
    at hook.callAsync (/home/user/laravel-mix-v4-test/node_modules/enhanced-resolve/lib/Resolver.js:238:5)
    at _fn0 (eval at create (/home/user/laravel-mix-v4-test/node_modules/tapable/lib/HookCodeFactory.js:32:10), <anonymous>:15:1)
    at hook.callAsync (/home/user/laravel-mix-v4-test/node_modules/enhanced-resolve/lib/Resolver.js:238:5)
    at _fn0 (eval at create (/home/user/laravel-mix-v4-test/node_modules/tapable/lib/HookCodeFactory.js:32:10), <anonymous>:12:1)
    at resolver.doResolve (/home/user/laravel-mix-v4-test/node_modules/enhanced-resolve/lib/DescriptionFilePlugin.js:42:38)
    at hook.callAsync (/home/user/laravel-mix-v4-test/node_modules/enhanced-resolve/lib/Resolver.js:238:5)
    at _fn43 (eval at create (/home/user/laravel-mix-v4-test/node_modules/tapable/lib/HookCodeFactory.js:32:10), <anonymous>:402:1)
    at hook.callAsync (/home/user/laravel-mix-v4-test/node_modules/enhanced-resolve/lib/Resolver.js:238:5)
    at _fn0 (eval at create (/home/user/laravel-mix-v4-test/node_modules/tapable/lib/HookCodeFactory.js:32:10), <anonymous>:12:1)
    at resolver.doResolve (/home/user/laravel-mix-v4-test/node_modules/enhanced-resolve/lib/DescriptionFilePlugin.js:42:38)
    at hook.callAsync (/home/user/laravel-mix-v4-test/node_modules/enhanced-resolve/lib/Resolver.js:238:5)
    at _fn1 (eval at create (/home/user/laravel-mix-v4-test/node_modules/tapable/lib/HookCodeFactory.js:32:10), <anonymous>:24:1)
    at hook.callAsync (/home/user/laravel-mix-v4-test/node_modules/enhanced-resolve/lib/Resolver.js:238:5)
    at _fn0 (eval at create (/home/user/laravel-mix-v4-test/node_modules/tapable/lib/HookCodeFactory.js:32:10), <anonymous>:15:1)
    at fs.stat (/home/user/laravel-mix-v4-test/node_modules/enhanced-resolve/lib/DirectoryExistsPlugin.js:22:13)
    at process.nextTick (/home/user/laravel-mix-v4-test/node_modules/enhanced-resolve/lib/CachedInputFileSystem.js:73:15)
    at process._tickCallback (internal/process/next_tick.js:61:11)
 @ ./resources/assets/sass/app.scss

ERROR in ./resources/assets/sass/app.scss (./node_modules/css-loader??ref--5-2!./node_modules/postcss-loader/src??postcss!./node_modules/sass-loader/lib/loader.js??ref--5-4!./resources/assets/sass/app.scss)
Module not found: Error: Can't resolve './images/a.png' in '/home/user/laravel-mix-v4-test/resources/assets/sass'
 @ ./resources/assets/sass/app.scss (./node_modules/css-loader??ref--5-2!./node_modules/postcss-loader/src??postcss!./node_modules/sass-loader/lib/loader.js??ref--5-4!./resources/assets/sass/app.scss) 7:67-92
 @ ./resources/assets/sass/app.scss
```