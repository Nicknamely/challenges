# WebDevLab

## Overview

This repository is a collection of experiments and challenges that I'm working on to improve my skills in web development.

## Key Features
* Each challenge is a standalone Git repository, making it easier to work on them individually.
* All challenges are neatly organized under the main repository for easy navigation.

## Usage

### Cloning the Repository

* Clone the entire repository to access all projects (Not recommended)
* Use sparse checkout to clone a specific project (see instructions below)

### Sparse Checkout Instructions

```bash
git clone --filter=blob:none --sparse https://github.com/Nicknamely/challenges.git
cd challenges
git sparse-checkout set <project-name>/
```
Replace `<project-name>` with the name of the project you want to clone

## Contributing
Have ideas or improvements? Open an issue or submit a pull request to discuss them.

## License
This repository is licensed under `MIT License`. Feel free to use it, but give credit where it's due.


