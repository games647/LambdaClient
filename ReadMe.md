# LambdaClient

## Description

TODO

## Project aims

* Easy project setup for easy contributions to this project
* Help server administrators and normal users to have a better play experience
* Make use of the newest libraries (i.e. Java 8)
* Open Source

## Features

* None ;(

## How to install 

If you just want to run this project, you could download the latest release from the Github releases and drop the
folder into your /.minecraft/versions folder. Restart your launcher and select lambdaclient.

## Setup

This project uses Gradle for automatic, OS- (Linux, Unix, Windows) and IDE-independent project setup. 
All three leading IDEs supports gradle (Netbeans, Jetbrains, Eclipse). 

1. Run `gradlew downloadMcp decompile applyPatch`

### Update

Every time you update your setup against the source code you should run `gradlew applyPatch` to apply the modifications 
of the Minecraft to yours.

### Other useful Gradle commands

* `gradlew install` - Installs the version into your local Minecraft installation
* `gradlew run` - Starts the Minecraft client like it would from MCP
* `graldew updatePatch` - Updates the diff file in the root folder if you did modification on the Minecraft-Code