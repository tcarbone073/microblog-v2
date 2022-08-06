## Flask Shell
*   `flask shell`, by default, pre-imports the application instance `app`
*   Create a function in the main script decorated with `@app.shell_context_processor` to register items to the shell context

## Flask Shell - Database
*   Run `flask shell`
*   `db.create_all()` to create all models
*   `db.drop_all()` to drop all models