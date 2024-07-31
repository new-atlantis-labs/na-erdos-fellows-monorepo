## Models Folder

The `models` folder contains the various machine learning models that are to be developed by each team in the fellows program.

Each model script and team folder follows a specific naming scheme to maintain consistency and readability.

##

### Team Folders

Each team should have their own folder using the following naming format:

*team_name_models*

- **team_name**: The name of the team responsible for the model.
- **models**: A constant suffix indicating the folder is a container for trained models

##

### Naming Scheme

Each model script should be named using the following format:


*model_team_name_modelType.py*
- **model**: A constant prefix indicating the file contains a model.
- **team_name**: The name of the team responsible for the model.
- **modelType**: The type of the model, written in Upper Camel Case (also known as Pascal Case).

### Example

For instance, if team `chlorofish` trains an XGBoost model, the file should be named:

*model_chlorofish_XGBoost.py*

##

### Upper Camel Case Convention

Please ensure to use Upper Camel Case for the model name. 

For example, if team `chlorofish` trains a Support Vector Machine (SVM), the Python file should be named:

*model_chlorofish_SupportVectorMachine.py*

By following this naming convention, we can keep our repository well-organized and make it easier for everyone to identify and work with the models.

