# Recipes API
This API was created with the Gin framework.

# Local Setup
Use ```bash go mod download``` to install the required dependencies after cloning the project.

# HTTP endpoints
| HTTP Method | Resource | Description |
|:-----------:|:--------:|:-----------:|
| GET | /recipes | Returns a list of recipes |
|:----:|:-------:|:--------------------------:|
| POST | /recipes | Creates a new recipe |
|:----:|:--------:|:--------------------:|
| PUT | /recipes/{id} | Updates an existing recipe | 
|:---:|:-------------:|:--------------------------:|
| DELETE | /recipes/{id} | Deletes an existing recipe |
|:------:|:-------------:|:--------------------------:|
| GET | /recipes/search?tag=X | Searches for recipes by tags |
|:---:|:---------------------:|:----------------------------:|