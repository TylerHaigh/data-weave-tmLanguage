# Data-Weave-TmLanguage

This repository contains TmLanguage files that are consumed by DatWeave editors and plugins.

# Contributing

The XML files are generated from the YAML files, so contributors should hand-modify the YAML files, and XML files should only be generated by running build script.

## Build

Update the XML files from within the ```build``` folder

``` sh
cd build
npm install         # Installs dependencies required for building
npm start           # Compiles & builds the XML files
```

## Tests

Test are run from within the ```tests``` folder and depend on build to make sure XML files are upto date

``` sh
cd build
npm install         # Installs dependencies required for building

cd ../tests
npm install         # Installs dependencies required for testing
npm test            # Compiles & runs tests
```
