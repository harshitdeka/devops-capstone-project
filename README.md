# \# devops-capstone-project

# 

# !\[CI Build](https://github.com/harshitdeka/devops-capstone-project/actions/workflows/ci-build.yaml/badge.svg)

# 

# This project is an account microservice for an e-commerce website. The service provides REST API endpoints to create, read, update, delete, and list customer accounts. It is developed as part of the IBM DevOps and Software Engineering Capstone Project.

# 

# \# DevOps Capstone Template

# 

# \[!\[License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

# \[!\[Python 3.9](https://img.shields.io/badge/Python-3.9-green.svg)](https://shields.io/)

# 

# This repository contains the starter code for the project in \*\*IBM-CD0285EN-SkillsNetwork DevOps Capstone Project\*\* which is part of the \*\*IBM DevOps and Software Engineering Professional Certificate\*\*.

# 

# \## Usage

# 

# You should use this template to start your DevOps Capstone project. It contains all of the code that you will need to get started.

# 

# Do Not fork this code! It is meant to be used by pressing the \*\*Use this Template\*\* button in GitHub. This will copy the code to your own repository with no connection back to the original repository like a fork would.

# 

# \## Development Environment

# 

# These labs are designed to be executed in the IBM Developer Skills Network Cloud IDE with OpenShift.

# 

# Initialize the environment:

# 

# ```bash

# source bin/setup.sh

# ```

# 

# After sourcing it, your prompt should look like:

# 

# ```bash

# (venv) theia:project$

# ```

# 

# \## Useful Commands

# 

# \### Activate the Python 3.9 virtual environment

# 

# ```bash

# source \~/venv/bin/activate

# ```

# 

# \### Install dependencies

# 

# ```bash

# make install

# ```

# 

# \### Start PostgreSQL

# 

# ```bash

# make db

# ```

# 

# \## Project Layout

# 

# ```text

# ├── service

# │   ├── common/

# │   ├── config.py

# │   ├── models.py

# │   └── routes.py

# ├── setup.cfg

# └── tests

# &#x20;   ├── factories.py

# &#x20;   ├── test\_cli\_commands.py

# &#x20;   ├── test\_models.py

# &#x20;   └── test\_routes.py

# ```

# 

# \## Data Model

# 

# | Name         | Type        | Optional |

# | ------------ | ----------- | -------- |

# | id           | Integer     | False    |

# | name         | String(64)  | False    |

# | email        | String(64)  | False    |

# | address      | String(256) | False    |

# | phone\_number | String(32)  | True     |

# | date\_joined  | Date        | False    |

# 

# \## Features Implemented

# 

# \* Create customer accounts

# \* Read customer accounts

# \* Update customer accounts

# \* Delete customer accounts

# \* List all customer accounts

# \* Docker containerization

# \* Kubernetes/OpenShift deployment

# \* GitHub Actions CI pipeline

# \* Tekton CD pipeline

# \* Security headers and CORS policies

# 

# \## Local Kubernetes Development

# 

# Bring up a local K3D Kubernetes cluster:

# 

# ```bash

# make cluster

# ```

# 

# Install Tekton:

# 

# ```bash

# make tekton

# ```

# 

# Install ClusterTasks:

# 

# ```bash

# make clustertasks

# ```

# 

# \## Author

# 

# IBM DevOps and Software Engineering Capstone Project

# 

# \## License

# 

# Licensed under the Apache License. See LICENSE.

# 

# © IBM Corporation 2022. All rights reserved.



