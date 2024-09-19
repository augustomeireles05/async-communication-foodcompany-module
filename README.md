# Async Communication FoodCompany Module

This repository contains the main module `async-communication-foodcompany-module`, which includes submodules for asynchronous communication between different microservices. Below are the steps required to clone the project and initialize the submodules.

## How to Clone the Project

Follow the steps below to correctly set up the repository and its submodules:

### 1. Clone the main repository

Clone the `async-communication-foodcompany-module` repository using the command below:

```bash
git clone https://github.com/augustomeireles05/async-communication-foodcompany-module.git
```

This command will download the main repository to your local environment.

### 2.  Access the cloned repository directory

```bash
cd async-communication-foodcompany-module
```

This ensures you are inside the repository directory to run the following commands.

### 3.  Initialize the submodules

The repository contains submodules that reference other Git repositories. To initialize these submodules, run the following command:

```bash
git submodule init
```

This command prepares Git to work with submodules, setting up references to the linked repositories.

### 4.  Initialize the submodules

After initializing, you need to update the submodules to download the referenced repositories' contents:

```bash
git submodule update
```

This command ensures the submodules are downloaded and available locally.

After following all these four steps, you'll have the entire project set up locally with the submodules correctly synchronized.