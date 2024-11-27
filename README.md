2.How Did You Run the Code?
Provide clear steps on how you executed the code. Example response:

Open the project in Visual Studio.
Restore NuGet packages if needed.
Ensure the database connection string is configured correctly in the Web.config or appsettings.json file.
Run the SQL scripts provided to create the database and tables.
Build the solution (Ctrl + Shift + B) to ensure there are no errors.
Run the project (F5) to start the application.
Use a browser to access the application at http://localhost:<port>.

3.How Did You Run the Machine Test?
Explain how you tested the application to verify it met the requirements. Example response:
Created two tables in the database: Category and Product.
Populated the Category table with sample data.
Used the CategoryController to test CRUD operations for categories.
Used the ProductController to test CRUD operations for products.
Added products linked to categories.
Verified that the Product List displayed Pid, Pname, Cid, and Cname correctly.
Tested server-side pagination by navigating through product pages (page size set to 10).
Verified that only relevant records were fetched from the database for each page.
Used browser developer tools to confirm proper HTTP requests and server responses.


