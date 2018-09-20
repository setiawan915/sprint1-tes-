1. Download or clone file on your folder PC
2. Run in terminal "composer update"
3. Create a new database with the name "tesapi" on mysql
4. Edit ".env" and adjust to the settings on your PC
5. Run in terminal "php artisan migrate"
6. Run in terminal "php artisan fetch:create"

Search Province
 url : "/search/province?id={province_id}"
 
Search City
 url : "/search/city?id={city_id}"
