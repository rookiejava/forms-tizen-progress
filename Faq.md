# Faq

**What is Tizen?**

Tizen is an open source operating system based on Linux, hosted by the Linux Foundation, and open to all developers. For more details, please refer to [here](https://developer.tizen.org/tizen).

**What is Tizen .NET?**

With Tizen 4.0, Tizen .NET is introduced. Tizen .NET brings significant enhancements to the development environment: support for C# as an application programming language, Tizen .NET based on Microsoft's .NET Core and Xamarin.Forms, and Visual Studio Tools for Tizen. 

**What version of Tizen is used?**

Currently, Tizen 4.0 is used for the Tizen backend. 

**What Samsung products are supported?**

Basically, Tizen 4.0 based samsung products are supported. But, it varies depending on each product's plan and strategy. For an instance, a list of Samsung Smart TV that support Tizen 4.0 (Tizen .NET) can be found [here](https://developer.samsung.com/tv/develop/specifications/tv-model-groups).
Also, other product (such as smart watch, smart phone and FamilyHub) information will be updated in [here](https://developer.samsung.com/).
The eairler version before Tizen 4.0 cannot support the Tizen .NET. 

**What Xamarin.Forms support is included in the Tizen backend?**

All pages, layouts and controls (including maps) are supported on the Tizen backend. [Status](Status.md) and [Known Issues](Known-Issues.md) sections are also helpful to you. 

**And what about new Xamarin.Forms options (Ex: Forms Embedding)?**

Effects, Platforms Specifics, or Forms Embedding are supported options.

**Can I extend functionallity to new platforms by creating new controls?**

Absolutely!. You can create effects or custom renders in the same way as iOS or Android.

**What has been used with the WebView control?**

Internally the browser control makes use of [Tizen.WebView](https://developer.tizen.org/dev-guide/csapi/api/Tizen.WebView.html) from [TizenFX](https://github.com/Samsung/TizenFX).

**What has been used with the Map control?**

Internally the Map control makes use of [Tizen.Maps](https://developer.tizen.org/dev-guide/csapi/api/Tizen.Maps.html) from [TizenFX](https://github.com/Samsung/TizenFX).

**How can I use all this today?**

You've got nothing to do. Just like android and iOS, you just add Xamarin.Forms nuget package (should use [3.0.0-pre2](https://www.nuget.org/packages/Xamarin.Forms/3.0.0.296286-pre2) or higher) into your projects.

