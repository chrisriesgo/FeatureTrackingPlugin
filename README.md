# Feature Tracking Plugin

This plugin was created using the bait-and-switch approach. 

> _Note - this plugin isn't published on NuGet._ 

- **Plugin.FeatureTracking** - source code for my _Plugin.FeatureTracking_ plugin that was created using the bait-and-switch approach.

## Packaging the NuGet

### Configure the .nuspec

Edit the `Package.nuspec` file to change the package details.

### Execute the pack command

####Mac:
[Download](https://dist.nuget.org/index.html) a command line NuGet executable.

```
/path/to/bin/mono $MONO_OPTIONS /path/to/NuGet.exe pack Package.nuspec -BasePath ./
```

####PC:

```
nuget pack Package.nuspec
```
