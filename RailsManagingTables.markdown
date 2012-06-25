* Table named blocks are PLURAL.
* If you ever need to ADD a column, simpley run a migration with add_XXX_to_TABLE and pass in the values
* this goes for REMOVING a column as well with remove_XXX_from_TABLE.
* If one of our tables changes value types and therefore CAN'T be or shouldn't be migrated down:
* add `raise Active Record::Irreversible Migration` to a down method in the migration file
* Tables with no primary key are usually considered join tables.
* to accomplish this pass `id: false` in the name of the create_table block.