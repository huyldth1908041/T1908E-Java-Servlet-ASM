# HM RESTAURANT

Hm restaurant is a web app allow user to add, modify, delete food in restaurant


## Instalations

Edit database configurations in uttil/ConnectionHelper.java

```java
    private final static String DATABASE_SERVER = "your_database_serve";
    private final static int DATABASE_PORT = "your_database_port";
    private final static String DATABASE_NAME = "your_database_name";
    private final static String DATABASE_USER = "your_database_username";
    private final static String DATABASE_PWD = "your_database_password";
```

Run migration and seed method when first time run the application

```java
   InitDatabase.init();
```

## Usages
Run web app in localhoast use tomcat server

type /admin to go to dashboard page

Use left menu to navigate in web sites Or:

To create new food go to /admin/food/create

To manage list food navigate to /admin/food

To create new food category go to /admin/category/create

To manage list food category navigate to /admin/category

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
