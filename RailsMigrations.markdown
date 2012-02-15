Basically how Rails knows how to form a database. Can be generated in two different ways

1. `rails g migration name_using_underscores`
   * Builds only the migration file, no models or tests
2. `rails g model modelName`
   * Builds model, migration file, and tests
   * Pass `--skip-migration` to bypass the migration and just create the model
3. Rails also knows and implements a clever way to deal with RailsSessions



* RailsRunningMigrations
* RailsMigrationAnatomy
* RailsManagingTables
* RailsAdvancedMigrations
