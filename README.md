# Welcome to nopApplicationInsightsTheme :wave:
![Version](https://img.shields.io/badge/version-0.1-blue.svg?cacheSeconds=2592000) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Volki312/ApplicationInsights#license)

> Theme that integrates Azure Application Insights client-side telemetry into your nopCommerce 4.20 web shop.
> Don't install if you don't have [Application Insights plugin](https://github.com/Volki312/nopApplicationInsights#readme) installed

### :house: [Homepage](https://github.com/Volki312/nopApplicationInsightsTheme#readme)

<br />

## [Install](https://docs.nopcommerce.com/developer/design/installing-theme.html "Install")

1. Paste "ApplicationInsights" folder into "Presentation/Nop.Web/Themes"
2. Add the following code to your Nop.Web.csproj:

```
  <ItemGroup>
    <PackageReference Include="Microsoft.ApplicationInsights.AspNetCore" Version="2.7.1" />
  </ItemGroup>
```
  
3. Reload Visual Studio or wait for the assembly reference to install
4. Go to the admin panel of your shop
5. Go to Configuration › Settings › General settings
6. Select new theme from the Default Store Theme and click Save.


<br />

## Author

:bust_in_silhouette: **Josip Volarevic**

* Github: [@Volki312](https://github.com/Volki312)

<br />

## Show your support

Give a :star: if this project helped you!

<br />

## :page_with_curl: License

Copyright :copyright: 2019 [Josip Volarevic](https://github.com/Volki312).

This project is [MIT](https://github.com/Volki312/nopApplicationInsightsTheme#license) licensed.