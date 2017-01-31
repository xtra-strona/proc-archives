"# proc-archives" 
## Simple Archive To Processwire

#### 1- Copy archive.php to your project
#### 2- In archive.php line 13 change your blog name Which is Page Like Home/Blog/ => where is => Settings => Name 
#### $blog = $pages->get("/your-blog-name/"); //Add your blog name
#### 3- In line 49 change to your template Hildren Blog Page => template=single-blog 
#### 4- CREATE TEMPLATE archive.php
#### 5- In your Setup/Templates/archive/URLs => you must select Allow URL Segments?
#### 6- CREATE PAGE WITH NAME LIKE Archive and select template archive
#### 7- CREATE DATE TIME FIELD => date_time With Date Output Format => 2016/06/03
#### 8- Add Field date_time to your blog single post item and select date
#### My Video with Polish Language:
### => 