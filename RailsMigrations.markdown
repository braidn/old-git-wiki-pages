Basically how Rails knows how to form a database. Can be generated in two different ways

1. `rails g migration name_using_underscores`
   * Builds only the migration file, no models or tests
2. `rails g model modelName`
   * Builds model, migration file, and tests
   * Pass `--skip-migration` to bypass the migration and just create the model
3. Rails also knows and implements a clever way to deal with RailsSessions
4. [Running Migrations][1]
5. [Migration Anatomy][2]
6. [Managing Tables][3]
7. [Advanced Migrations][4]

###Best Practices

* If a migration has been pushed/commited, it's best not to modify it.

[1]: /RailsRunningMigrations
[2]: /RailsMigrationAnatomy
[3]: /RailsManagingTables
[4]: /RailsAdvancedMigrations