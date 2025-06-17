# Jupyter Workshop

Welcome to the Jupyter Workshop for OpenMC, Sandy, and NJOY! This workshop is designed to provide participants with hands-on experience using these powerful tools for nuclear science and engineering.

## Overview

This repository contains a Dockerized environment that includes OpenMC, Sandy, and NJOY, along with Jupyter notebooks for both introductory content and practical exercises.

## Contents

- `notebooks/introduction.ipynb`: An introductory notebook that provides background information on OpenMC, Sandy, and NJOY, as well as instructions on how to navigate the workshop materials.
- `notebooks/DataLab_1.ipynb`: A practical exercise notebook that contains examples and tasks related to using OpenMC, Sandy, and NJOY.

## Getting Started

### Prerequisites

- Docker installed on your machine.

### Building the Docker Image

To build the Docker image, navigate to the root of the project directory and run the following command:

```
docker build -t sandy-workshop .
```

### Running the Docker Container

Once the image is built, you can run the Docker container with the following command:

```
docker run -p 8888:8888 jupyter-workshop
```

After running the container, you will see a URL in the terminal that you can use to access Jupyter Notebook in your web browser.

## Accessing the Notebooks

Once Jupyter Notebook is running, you can access the following notebooks:

- **Introduction**: `notebooks/introduction.ipynb`
- **Data Lab**: `notebooks/DataLab_1.ipynb`

## Conclusion

We hope you find this workshop informative and engaging. Happy coding!