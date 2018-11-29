## Its Super Simple ##

Requirments:
* PHP, mysql, webserver (tested in apache2)
* mysqli PHP extension

Just drag the index.php file to an appropriate web directory on your web browser. Open it for editing to configure the following:

```php
///////////////////////////////////////////////////////////////////////////////////////
const Server = "localhost";////////////////////////////////////////////////////////  <--- set this to your db host
const Username = "DB_USERNAME";/////////////////////////////////////////////////  <--- set this to your db username
const Password = "DB_PASSWORD";//////////////////////////////////////////// <--- set this to your db password
const DBName = "characters";///////////////////////////////////////////  <--- set this to your character database name
///////////////////////////////////////////////////////////////////

// CHANGE THIS TO YOUR CUSTOM BOOST ITEM
const CUSTOM_BOOST_ITEMID = 90001;  <--- if you have a custom level up or boost item, you can set its itemid here
```
Thats it.
