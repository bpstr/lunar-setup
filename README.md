# lunar-starter-php

Starter template for Lunar PHP projects.

## Usage

To set up a new project, create a new repository from this template.

## Development

Steps to start developing on this project:

### Prerequisites

Install colima on MacOS:

```bash
brew install colima
colima start
```

### Running the install script

```bash
cd /path/to/your/project
docker pull ubuntu:latest
docker run -it -v $(pwd):/app ubuntu:latest /bin/bash

# Inside the container
cd /app
chmod +x setup.sh   # Make sure the script is executable
./setup.sh




```bash


```

##
