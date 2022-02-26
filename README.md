# Reality Toolkit - GitHub actions reusable workflows for building Unity projects from UPM packages

A collection of reusable workflows deployed by the Reality Collective

See here for more detail on the [Reality Toolkit](https://github.com/realitycollective/com.realitytoolkit.dev)

## What's included?

### Build workflows

- buildupmpackages.yml - Example end to end workflow for building a UPM package

### Action Modules

- validateunityinstall.yml - Utility to check the build host has the Unity hub installed and a Unity Editor using the version supplied
- installunityeditor.yml - Utility to install a specific version of the Unity Editor (Requires Unity Hub)
- rununityunittests.yml - Utility to clone the UPM repo and run Unity Editor unit tests on it with results
- upmrelease.yml - Utility to package a UPM project and publish to a target NPM server

### Build tools

- getunityversionfrompackage.yml - Simple tool to get a Unity version from a UPM Project.json file
- getunityversionfromproject.yml - Simple tool to get a Unity version fom a Unity project (projectversion.txt) file
- testparams.yml - Simple tool to echo data being passed from Job Outputs, handy for testing to see if the outputs match your expectations

## Getting Started

tbc