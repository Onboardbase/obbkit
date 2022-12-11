# Overview

obbkit is a CLI tool for generating boilerplates with onboardbase preconfigured in them as a SecretOps infrastucture.

# Usage
We would be creating a reactjs project that has onboardbase preconfigured.

![image](https://user-images.githubusercontent.com/65312338/183244277-d032a954-c369-4f34-9da2-b5b8682bf48c.png)

It automatically opens the created project in vscode.

![image](https://user-images.githubusercontent.com/65312338/183387559-7c19ada9-2164-4f16-9a47-651a1ebfde70.png)

You can start building 😍😍

# Installation

Also, check out our [YouTube](https://www.youtube.com/watch?v=NmXLDEeabLA) for getting started with obbkit cli.

### Go
 
Install
 
```
go install github.com/onboardbase/obbkit@v0.8.0
```
### npm (coming soon)

```
npm i -g obbkit
```

### macOS

Install

```
$ brew tap onboardbase/obbkit
$ brew install onboardbase/obbkit
```

Update

```
brew upgrade obbkit
```

Uninstall

```
brew remove obbkit
```

### Version

```
obbkit --version
```
# Commands 

### `obbkit help`        
Help about any command

### `obbkit init`        
Initialize or create your project

### `obbkit list`        
List all available project types that onboardbase provides.

# Flags 

###  `-h, --help`      
help for obbkit

###  `-v, --version`   
version for obbkit  

# Contribute 

## Requirements

* Go >= 0.18

## Clone Repository

```sh
git clone <repo>
```

After setting up obbkit run the command below to test the project

```sh
$ go build
$ go install
```
# License

obbkit is released under the MIT license. See [LICENSE.txt](https://github.com/Onboardbase/obbkit/blob/main/LICENSE)
