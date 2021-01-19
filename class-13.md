# Local Storage For Web Applications
## Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data
### Cookies downsides:
1. #### Cookies are limited to about 4 KB of data
2. #### Cookies are included with every HTTP request,thereby sending data unencrypted over the internet 
3. #### ookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over

## HTML5 STORAGE
### HTML5 Storage it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site.

### The data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype .
## interface Storage {
##   getter any getItem(in DOMString key);
##  setter creator void setItem(in DOMString key, in any data); };

### Calling setItem() with a named key that already exists will silently overwrite the previous value. Calling getItem() with a non-existent key will return null rather than throw an exception
 ## Example of deleting all the keys and values at once : 
 ### interface Storage {
 ##  deleter void removeItem(in DOMString key);

 ##  void clear();

## };
## SQLite
### SQLite 
### Web SQL Database (formerly known as “WebDB”) provides a thin wrapper around a SQL database, allowing you to do things like this from JavaScript . 
#### openDatabase('documents', '1.0', 'Local document storage', 5*1024*1024, function (db) {
 #### db.changeVersion('', '1.0', function (t) {
 ####   t.executeSql('CREATE TABLE docids (id, name)');
####  }, error);

#### });
#### As you can see, most of the action resides in the string you pass to the executeSql method. This string can be any supported SQL statement, including SELECT, UPDATE, INSERT, and DELETE statements.
### Web SQL Database specification has been implemented by :
1. ####  FIREFOX
2. #### SAFARI
3. #### CHROME
4. #### OPERA
5. #### IPHONE
6. #### ANDROID

