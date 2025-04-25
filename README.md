# Razor Pages CRUD Application

[![.NET](https://img.shields.io/badge/.NET-6.0-purple)](https://dotnet.microsoft.com/)
[![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-6.0-blue)](https://docs.microsoft.com/aspnet/core)

## Installation
```bash
git clone https://github.com/yourusername/yourrepo.git
cd CrudRazorApp
dotnet restore
```

## Project Structure
```
CrudRazorApp/
├── Pages/
│   └── Products/
│       ├── Index.cshtml
│       ├── Create.cshtml
├── Models/
│   └── Product.cs
└── appsettings.json
```

## Code Example
```csharp
// Product model
public class Product
{
    public int Id { get; set; }
    
    [Required]
    public string Name { get; set; }
}
```

## Screenshots
| List View | Create View |
|-----------|-------------|
| ![List](screenshots/list.png) | ![Create](screenshots/create.png) |
