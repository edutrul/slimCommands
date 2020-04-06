# slimCommands
Generate classes for rest api.


Here's an attempt of the command:

$ slim-create rest-api
What is the main Class?
Pets
What methods do you want to implement? add comma
GET, POST
What are the attributes? <data_type>: $variable (follow with comman) hit enter when done
string $firstName, string $lastName

Do you want to include tests? 
Yes

Do you want to provide HardCodedData?
Yes


The following files have been created/updated

- app/dependencies.php
- app/routes.php
- src/Application/Actions/Pet/PetAction.php
- src/Application/Actions/Pet/ListPetsAction.php
- src/Application/Actions/Pet/ViewPetAction.php
- src/Domain/Pet/Pet.php
- src/Domain/Pet/PetNotFoundException.php
- src/Domain/Pet/PetRepository.php
- src/Infrastructure/Persistence/Pet/InMemoryPetRepository.php
- tests/Domain/Pet/PetTest.php
- tests/Application/Actions/Pet/ListPetsAction.php
- tests/Application/Actions/Pet/ViewPetAction.php
- tests/Infrastructure/Persistence/Pet/InMemoryPetRepository.php



@TODO: Implement commands
Resources:
https://codeinphp.github.io/post/creating-your-own-artisan-in-php/

Inspired commands from DrupalConsole project https://github.com/hechoendrupal/drupal-console
