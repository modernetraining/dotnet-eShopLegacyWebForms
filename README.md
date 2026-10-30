# eShopLegacyWebForms: legacy ASP.NET Web Forms app

The ASP.NET Web Forms catalog app from Microsoft's
[dotnet-architecture/eShopModernizing](https://github.com/dotnet-architecture/eShopModernizing)
(MIT licensed, archived), on its own. It is a starting point for Moderne demos that migrate
.NET Framework code to modern .NET with OpenRewrite recipes and agents.

## What's included

| Solution | Project | Framework |
|---|---|---|
| `eShopLegacyWebFormsSolution` | `eShopLegacyWebForms`: Web Forms, EF6, Autofac, log4net | 4.7.2 |

## What's removed

Everything else in the upstream repo: the MVC and N-Tier apps, the modernized and ported
copies (`eShopModernized*`, `eShopPorted`), and the container, Kubernetes, Azure and
Service Fabric material. The content matches upstream `main` at
[`63bc9ec`](https://github.com/dotnet-architecture/eShopModernizing/commit/63bc9ec4414d7e281dc9f9d7bdcf70030950457d)
apart from those removals and this README. Upstream history is not included.

## Running the app

Open `eShopLegacyWebFormsSolution/eShopLegacyWebForms.sln` in Visual Studio on Windows. It
uses mock data by default (`UseMockData` in `Web.config`); set it to `false` to use SQL
Server LocalDB.

## Branches

`main` is the baseline and does not change.
