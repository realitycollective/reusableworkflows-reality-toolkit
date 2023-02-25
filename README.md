# Reality Toolkit - GitHub actions reusable workflows for building Unity projects from UPM packages

A collection of reusable workflows deployed by the Reality Collective

See here for more detail on the [Reality Toolkit](https://github.com/realitycollective/com.realitytoolkit.dev)

## What's included?

Below is a list of the available workflows in this repository and their function.
For more details, see the [Automation](https://realitytoolkit.io/docs/category/automation/) documentation on the Reality Toolkit documentation site:

### [https://realitytoolkit.io/docs/category/automation/](https://realitytoolkit.io/docs/category/automation/)

### Build workflows

- buildupmpackages.yml - Example end to end workflow for building a UPM package

### Action Modules

- validateunityinstall.yml - Utility to check the build host has the Unity hub installed and a Unity Editor using the version supplied
- rununityUPMbuild.yml - Utility to clone the UPM repo and run Unity Editor unit tests on it with results
- rununityUPMbuildmultiversion.yml - Utility to clone the UPM repo and run Unity Editor unit tests on it with results, workd for multiple predefined versions of Unity.
- tagrelease.yml - Utility to Tag a UPM project for publishing.
- upversionandtagrelease.yml - Utility to correctly manage the versioning of a UPM package and generate a new tag on release.

### Build tools

- getpackageversionfrompackage.yml - Simple tool to get a the package version from a UPM Project.json file
- getunityversionfrompackage.yml - Simple tool to get a Unity version from a UPM Project.json file
- getunityversionfromproject.yml - Simple tool to get a Unity version fom a Unity project (projectversion.txt) file
- refreshbranch.yml - Workflow to update a target branch from its parent source branch automatically.
- testparams.yml - Simple tool to echo data being passed from Job Outputs, handy for testing to see if the outputs match your expectations

### deprecated workflows

- installunityeditor.yml - Utility to install a specific version of the Unity Editor (Requires Unity Hub)