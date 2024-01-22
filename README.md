# Klockan-App

## Overview

Welcome to the main repository of the Klockan Application. This repository serves as the central hub for the project, integrating three distinct submodules to collectively build the complete Klockan Application.

## Submodules:

- [Backend Respository](https://github.com/JU-DEV-LatamBootcamp/Klockan-Backend)
- [Frontend Repository](https://github.com/JU-DEV-LatamBootcamp/Klockan-Frontend)
- [Keycloak Server and Realm Config Repository](https://github.com/JU-DEV-LatamBootcamp/Klockan-Keycloak)

## Getting Started:

Follow these steps to initialize and update the submodules:

1. Add a submodule: ```git submodule add git@github.com:<github-username>/<repository-name>.git```
2. Init the submodule: ```git submodule init``` *This registers the paths to the repositories.*
3. Update the submodule: ```git submodule update``` *This updates the module with the latest changes from each repository.*
4. Access the submodule: ```cd <repository-name>```
   

When adding the submodule, a .gitmodules file is created, example::

```
[submodule "Klockan-Keycloak"]
	path = Klockan-Keycloak
	url = git@github.com:JU-DEV-LatamBootcamp/Klockan-Keycloak.git
[submodule "Klockan-Frontend"]
	path = Klockan-Frontend
	url = git@github.com:JU-DEV-LatamBootcamp/Klockan-Frontend.git
[submodule "Klockan-Backend"]
	path = Klockan-Backend
	url = git@github.com:JU-DEV-LatamBootcamp/Klockan-Backend.git
```

*To go to a specific branch within a submodule, specify it like this:*

```
[submodule "Klockan-Frontend"]
	path = Klockan-Frontend
	url = git@github.com:JU-DEV-LatamBootcamp/Klockan-Frontend.git
  branch = develop
```

Feel free to explore each submodule repository for more detailed information and development details.

