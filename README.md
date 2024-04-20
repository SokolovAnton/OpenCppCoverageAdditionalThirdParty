# OpenCppCoverageAdditionalThirdParty
Additional packages for OpenCppCoverage fork

## How to install
1. Download packages from this repository
2. Clone OpenCppCoverage
3. Install packages in `packages` directory
```cmd
> cp LevelDB.1.23.0.nupkg nlohmann_json.3.11.3.nuget /path/to/OpenCppCoverage/sources
> cd /path/to/OpenCppCoverage/sources
> nuget.exe install LevelDB -Source /path/to/OpenCppCoverage/sources -OutputDirectory packages
> nuget.exe install nlohmann_json -Source /path/to/OpenCppCoverage/sources -OutputDirectory packages
```
