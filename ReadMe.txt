CMD RUN => composer create-project codeigniter4/appstarter crud-app
CMD RUN => cd crud-app

CMD RUN => php spark serve

CMD RUN => php spark make:model UserModel
CMD RUN => php spark make:controller UserController

CMD RUN => php spark migrate:create CreateUsersTable
CMD RUN => php spark migrate


CMD RUN => php spark serve

http://localhost:8080