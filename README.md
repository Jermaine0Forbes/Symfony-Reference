# Symfony-Reference
Just a reference for me to understand the fundamentals of the Symfony framework


## Entities

- [how to create an entity/model][create-ent]


## Controllers

## Events

## Services Containers

## Message Queuing 

[create-ent]:#how-to-create-an-entity


### how to create an entity

<details>
<summary>
View Content
</summary>

1. In order to create an entity/model with symfony, you just need to type this in console
```
php bin/console make:entity
```
2. It will allow you to add different properties and define their data types. Once you're done (hitting enter), the entity file will be created
3. Next you need to create a migration file to move the newly created or updated entity like so

```
php bin/console make:migration
```
4.  This will create a migration file in the `migrations` directory. You can migrate the SQL to the database by running this command
```
php bin/console doctrine:migrations:migrate
```
5.  and that's about it

</details>

[go back :house:][home]


:link: **Reference**

- []()
