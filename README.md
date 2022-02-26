# Imagick-Window
Install Imagick extension on PHP for Window

## Check PHP Version

- Determine the PHP version

```
php -i|find "PHP Version"
```

- Determine the thread safety either TS or NTS
```
php -i|find "Thread Safety"
```

- Determine the architecture either 64 bits or 32 bits
```
php -i|find "Architecture"
```

- Download Imagick Extension from here - https://mlocati.github.io/articles/php-windows-imagick.html

## Manage Download File

- Extract the zip file and put the *php_imagic.dll* file to the *ext* folder of your PHP installation folder.

- Move all the other *.dll* files to your main PHP installation folder where *php.exe* is located.

- Add these code to *php.ini* to enable the extension.
```
extension=php_imagick.dll
```

- Restart your local server Apache/NGINX.

Credit : [mlocati](https://github.com/mlocati?tab=overview&from=2022-02-01&to=2022-02-26)
