# Custom MyGet feed

Add the [nuget.config](nuget.config) in the same folder as the `.sln` file to access my nuget feed (hosted at MyGet).

Or you can add one of the feed urls manually:
- Nuget V3 feed: `https://www.myget.org/F/coenm/api/v3/index.json`
- Nuget V2 feed: `https://www.myget.org/F/coenm/api/v2`


# User Nuget.Config

You can edit your user `nuget.config` file (`%APPDATA%\NuGet\NuGet.Config`) to specify a location for all downloaded packages.

I've added the following sample to the `<configuration>` item:
```  
<config>
  <add key="repositoryPath" value="C:\packages" />
</config>
```  

The full source is [here](user.nuget.config).

