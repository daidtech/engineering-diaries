
# Model!

## 1. What is ActiveRecord in Rails?
ActiveRecord is the object-relational mapping (ORM) framework in Ruby on Rails that provides an interface between the Ruby code and the database. It provides easy-to-use methods for reading, writing, querying, and manipulating data stored in the database. The models in the Rails application are mapped to the corresponding database tables using ActiveRecord. It also provides features such as validations, associations, callbacks, and migrations to simplify the management of database-related tasks.

## 2. Explain the use of validations in ActiveRecord
The use of validations in ActiveRecord is to ensure that the data stored in the database meets certain rules or conditions. Validations are defined in the model class using various validation methods available in ActiveRecord, which help to maintain the data's consistency and integrity by preventing the storage of invalid data in the database.

## 3. How does ActiveRecord manage database migrations?
ActiveRecord is a tool in the Ruby on Rails framework that helps manage changes to a database's structure, such as creating or deleting tables and columns. It does this through a system of migration files which contain instructions for making these changes. To create a migration, you use a command to create a new migration file and then add the instructions for what changes should be made to the database. Finally, you run the migration command to apply the changes to the database. If you need to undo a migration, there's a command for that too.

## 4. What is a callback in ActiveRecord and what are the types of callbacks available?
Callbacks in ActiveRecord are methods that get called at specific moments of an object's lifecycle. They allow developers to trigger certain behavior before or after specific events, such as validation, creation, update, or destruction of an ActiveRecord object. The types of callbacks available in ActiveRecord are:
> 1. `before_validation` : triggered before validation occurs.
> 2. `after_validation` : triggered after validation occurs.
> 3. `before_save` : triggered before an object is saved, both on create and update.
> 4. `after_save` : triggered after an object is saved, both on create and update.
> 5. `before_create` : triggered before a new object is created.
> 6. `after_create` : triggered after a new object is created.
> 7. `before_update` : triggered before an existing object is updated.
> 8. `after_update` : triggered after an existing object is updated.
> 9. `before_destroy` : triggered before an object is destroyed.
> 10. `after_destroy` : triggered after an object is destroyed.

By using these callbacks, developers can perform additional actions such as logging, sending emails, updating associated records, etc.

## 5. Explain the difference between has_one and belongs_to associations in ActiveRecord.

## 6. What is the difference between eager loading and lazy loading in ActiveRecord?

## 7. What is the use of scope in ActiveRecord and how would you define a scope?

## 8. Explain the difference between find and find_by methods in ActiveRecord.

## 9. How can you fetch the last record added to the database using ActiveRecord?

## 10. What is the use of transactions in ActiveRecord and how does it ensure data consistency?

## 11. What are nested attributes in ActiveRecord and how do you use them?

## 12. How can you query data from the database using ActiveRecord?

## 13. Explain the difference between a database column and a database index.

## 14. What is the use of touch method in ActiveRecord?

## 15. How would you define a one-to-many association in ActiveRecord?

## 16. What is the use of polymorphic associations in ActiveRecord?

## 17. Explain the use of the has_many :through association in ActiveRecord.

## 18. What is the use of counter_cache in ActiveRecord and how do you implement it?

## 19. How would you define a many-to-many association in ActiveRecord?

## 20. What is the use of dependent option in ActiveRecord associations and how do you use it?