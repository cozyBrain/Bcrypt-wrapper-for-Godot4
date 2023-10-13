# Bcrypt-wrapper-for-Godot4
Simple C# code. Able to use it in GDScript with Godot4(C# Support).  
  
var bcrypt := BCryptWrapper.new()  
bcrypt.HashPassword("password") # return string  
bcrypt.VerifyPassword("password", "PW_from_db") # return bool  
  
```xml
<Project Sdk="Godot.NET.Sdk/4.1.2">
  <PropertyGroup>
    <TargetFramework>net6.0</TargetFramework>
    <EnableDynamicLoading>true</EnableDynamicLoading>
  </PropertyGroup>
  <ItemGroup>
    <PackageReference Include="BCrypt.Net-Next" Version="4.0.3"/>
  </ItemGroup>
</Project>
