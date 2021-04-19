Rent A Car Project BackEnd


Entity Framework is used.

Layers

Business: It is the layer created to process and process the incoming information according to the required conditions. The Abstract folder keeps the abstract objects (interface), the Concrete folder, the concrete objects (class), the ValidationRules and Utilities folders in the classes that perform the validation operations.

ConsoleUI: It contains the ConsoleApp that enables the application to run on the console.

Core: It contains the DataAccess folder, which is related to the DataAccess layer and the DataAccess folder, which does the job of the DataAccess layer, and the Entites Folder that does the job of the Entity layer, and much more. Some companies have an infrastructure team that only writes the Core layer.

DataAccess: Database performs CRUD operations. The Abstract folder interfaces, Concrete folder holds classes.

Entities: This layer holds the data in the database table.

WebAPI:
