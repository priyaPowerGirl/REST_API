PHP REST API 
1. Folder Structure
    There are 3 Folders in REST API are api, class and config
    
    1.1 api folder has all CRUD Operation of one table. If you have more table you can repeat/copy these folder.
    
    1.2 class folder file inlude all operations of one table that used in CRUD.

    1.3 config folder are only create connections of mysql database and return that connections for further use.

2. Api Call like

    2.1 GET	http://localhost/api/employees/read.php

    2.2 GET	http://localhost/api/employees/single_read.php/?id=2

    2.3 POST http://localhost/api/employees/create.php

    2.4 POST http://localhost/api/employees/update.php

    2.5 DELETE http://localhost/api/employees/delete.php