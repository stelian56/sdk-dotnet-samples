# Extract Mileage

 This example demonstrates how to get mileage for all vehilces using the MyGeotab API and save to a CSV or XML file.

Steps:

1. Create Geotab API object from supplied arguments and authenticate.
1. Get the odometer readings of each device and a VehicleWithMileage object.
1. Output the information to a CSV or XML file.

## Prerequisites

The sample application requires:

- [.Net core 2.0 SDK](https://dot.net/core) or higher

## Getting started

```shell
> git clone https://github.com/Geotab/sdk-dotnet-samples.git sdk-dotnet-samples
> cd sdk-dotnet-samples
> cd ExtractMileage
> dotnet run "my.geotab.com" "database" "user@email.com" "password" "mileage.csv"
```
