dotnet new sln -n 20230810

dotnet new console -o A1TypeCastingDemo
dotnet sln add .\A1TypeCastingDemo\A1TypeCastingDemo.csproj
dotnet add reference ../../Common/HeaderFooter/HeaderFooter.csproj

dotnet new console -o A2VarsDemo
dotnet sln add .\A2VarsDemo\A2VarsDemo.csproj
dotnet add reference ../../Common/HeaderFooter/HeaderFooter.csproj