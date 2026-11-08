<style>
/* Keep project tables usable when their contents exceed the available width. */
.markdown-body table.project-table {
  display: block;
  width: 100%;
  max-width: 100%;
  overflow-x: auto;
}

.markdown-body .project-table th,
.markdown-body .project-table td {
  vertical-align: middle;
}

.markdown-body .project-table td:nth-child(2) {
  min-width: 9rem;
  overflow-wrap: anywhere;
}

.markdown-body .project-table td:nth-child(3) {
  min-width: 12rem;
}

/* Each badge stays intact; multiple links can wrap between badges. */
.markdown-body .project-table td:last-child a {
  display: inline-block;
  vertical-align: middle;
}

/* Override the theme's max-width: 100% only for Shields.io badges. */
.markdown-body .project-table img[src^="https://img.shields.io/"] {
  width: auto;
  height: 20px;
  max-width: none;
  vertical-align: middle;
}
</style>

Hello, I create stuff in .NET and C#. Visit my [GitHub profile page](https://github.com/sungaila) for more info.

## NuGet packages

|  | Project | Description | Links |
|---|---|---|---|
| <img src="https://raw.githubusercontent.com/sungaila/PDFtoImage/master/etc/Icon.svg" alt="PDFtoImage logo" width="48" height="48" style="min-width: 48px"> | [PDFtoImage](https://github.com/sungaila/PDFtoImage) | A .NET library to render [PDF files](https://en.wikipedia.org/wiki/PDF) into images. | [![NuGet version](https://img.shields.io/nuget/v/PDFtoImage.svg?style=flat-square&logo=nuget&logoColor=white)](https://www.nuget.org/packages/PDFtoImage/) [![Website](https://img.shields.io/website?up_message=online&down_message=offline&url=https%3A%2F%2Fwww.sungaila.de%2FPDFtoImage%2F&style=flat-square&label=website)](https://www.sungaila.de/PDFtoImage/) |
| <img src="https://raw.githubusercontent.com/sungaila/PDFtoImage/master/etc/Icon_Parallel.svg" alt="PDFtoImage.Parallel logo" width="48" height="48" style="min-width: 48px"> | [PDFtoImage.Parallel](https://github.com/sungaila/PDFtoImage/tree/master/src/Parallel) | A .NET library for parallel PDF rendering using separate PDFium worker processes. | [![NuGet version (including prereleases)](https://img.shields.io/nuget/vpre/PDFtoImage.Parallel.svg?style=flat-square&logo=nuget&logoColor=white)](https://www.nuget.org/packages/PDFtoImage.Parallel/) |
| <img src="https://raw.githubusercontent.com/sungaila/PDFtoZPL/master/Icon.png" alt="PDFtoZPL logo" width="48" height="48" style="min-width: 48px"> | [PDFtoZPL](https://github.com/sungaila/PDFtoZPL) | A .NET library to convert [PDF files](https://en.wikipedia.org/wiki/PDF) (and bitmaps) into [Zebra Programming Language commands](https://en.wikipedia.org/wiki/Zebra_(programming_language)). | [![NuGet version](https://img.shields.io/nuget/v/PDFtoZPL.svg?style=flat-square&logo=nuget&logoColor=white)](https://www.nuget.org/packages/PDFtoZPL/) [![Website](https://img.shields.io/website?up_message=online&down_message=offline&url=https%3A%2F%2Fwww.sungaila.de%2FPDFtoZPL%2F&style=flat-square&label=website)](https://www.sungaila.de/PDFtoZPL/) |
| <img src="https://raw.githubusercontent.com/sungaila/pdfium-binaries/master/nuget/icon.svg" alt="Sungaila.PDFium.BlazorWebAssembly logo" width="48" height="48" style="min-width: 48px"> | [Sungaila.PDFium.BlazorWebAssembly](https://github.com/sungaila/pdfium-binaries) | This is a fork of [bblanchon/pdfium-binaries](https://github.com/bblanchon/pdfium-binaries) that provides [PDFium](https://pdfium.googlesource.com/pdfium/) builds for [ASP.NET Core Blazor WebAssembly](https://dotnet.microsoft.com/en-us/apps/aspnet/web-apps/blazor). | [![NuGet version](https://img.shields.io/nuget/v/Sungaila.PDFium.BlazorWebAssembly.svg?style=flat-square&logo=nuget&logoColor=white)](https://www.nuget.org/packages/Sungaila.PDFium.BlazorWebAssembly/) |
| <img src="https://raw.githubusercontent.com/sungaila/InlineTest/master/etc/Icon.svg" alt="InlineTest logo" width="48" height="48" style="min-width: 48px"> | [InlineTest](https://github.com/sungaila/InlineTest) | A [C# source generator](https://devblogs.microsoft.com/dotnet/introducing-c-source-generators/) for quick creation of simple unit tests. | [![NuGet version](https://img.shields.io/nuget/v/Sungaila.InlineTest.svg?style=flat-square&logo=nuget&logoColor=white)](https://www.nuget.org/packages/Sungaila.InlineTest/) |
| <img src="https://raw.githubusercontent.com/sungaila/Cdelta/master/etc/Icon.png" alt="Cdelta logo" width="48" height="48" style="min-width: 48px"> | [Cdelta](https://github.com/sungaila/Cdelta) | A [C# source generator](https://devblogs.microsoft.com/dotnet/introducing-c-source-generators/) for [finite-state machines](https://en.wikipedia.org/wiki/Finite-state_machine) ‐ easily referenced as a [Roslyn analyzer](https://github.com/dotnet/roslyn-analyzers). | [![NuGet version](https://img.shields.io/nuget/v/Cdelta.svg?style=flat-square&logo=nuget&logoColor=white)](https://www.nuget.org/packages/Cdelta/) |
| <img src="https://raw.githubusercontent.com/sungaila/PresentationBase/master/Icon.png" alt="PresentationBase logo" width="48" height="48" style="min-width: 48px"> | [PresentationBase](https://github.com/sungaila/PresentationBase) | A lightweight MVVM implementation for WPF ([Windows Presentation Foundation](https://en.wikipedia.org/wiki/Windows_Presentation_Foundation)) targeting both **.NET Framework** and **.NET**. | [![NuGet version](https://img.shields.io/nuget/v/PresentationBase.svg?style=flat-square&logo=nuget&logoColor=white)](https://www.nuget.org/packages/PresentationBase/) |
| <img src="https://raw.githubusercontent.com/sungaila/PresentationBase.Core/master/Icon.png" alt="PresentationBase.Core logo" width="48" height="48" style="min-width: 48px"> | [PresentationBase.Core](https://github.com/sungaila/PresentationBase.Core) | A lightweight MVVM implementation targeting **.NET Standard 2.0** and **.NET 6.0**. | [![NuGet version](https://img.shields.io/nuget/v/PresentationBase.Core.svg?style=flat-square&logo=nuget&logoColor=white)](https://www.nuget.org/packages/PresentationBase.Core/) |
| <img src="https://raw.githubusercontent.com/sungaila/RedditQuoteBot/master/Icon.png" alt="RedditQuoteBot logo" width="48" height="48" style="min-width: 48px"> | [RedditQuoteBot](https://github.com/sungaila/RedditQuoteBot) | A reddit bot scanning comments for trigger phrases to reply with predefined quotes. | [![NuGet version](https://img.shields.io/nuget/v/RedditQuoteBot.svg?style=flat-square&logo=nuget&logoColor=white)](https://www.nuget.org/packages/RedditQuoteBot/) |
| <img src="https://raw.githubusercontent.com/sungaila/ImmersiveDarkMode/master/etc/ImmersiveDarkMode.svg" alt="Sungaila.ImmersiveDarkMode logo" width="48" height="48" style="min-width: 48px"> | [Sungaila.ImmersiveDarkMode](https://github.com/sungaila/ImmersiveDarkMode) | Applies a dark theme to the titlebar of Win32 windows. Can also be toggled automatically whenever the system-wide application theme changes. | [![NuGet version](https://img.shields.io/nuget/v/Sungaila.ImmersiveDarkMode.svg?style=flat-square&logo=nuget&logoColor=white)](https://www.nuget.org/packages/Sungaila.ImmersiveDarkMode/) |
{: .project-table}

## Programs to download

|  | Project | Description | Links |
|---|---|---|---|
| <img src="https://raw.githubusercontent.com/sungaila/SurvivalNotRequired/master/etc/Icon.png" alt="Survival Not Required logo" width="48" height="48" style="min-width: 48px"> | [Survival Not Required](https://github.com/sungaila/SurvivalNotRequired) | A mod for the game [Oxygen Not Included](https://www.klei.com/games/oxygen-not-included) from Klei Entertainment. Its goal is to lower the difficulty for the first few day cycles and thus make the game more accessible for beginners. | [![Steam Views](https://img.shields.io/steam/views/2840201171?style=flat-square&logo=steam&logoColor=white&label=views)](https://steamcommunity.com/sharedfiles/filedetails/?id=2840201171) |
| <img src="https://raw.githubusercontent.com/sungaila/NewDarkGlobalServer/master/Icon.png" alt="NewDarkGlobalServer logo" width="48" height="48" style="min-width: 48px"> | [NewDarkGlobalServer](https://github.com/sungaila/NewDarkGlobalServer) | A global server providing a game server list for [Thief 2](https://en.wikipedia.org/wiki/Thief_II) Multiplayer. | [![Website](https://img.shields.io/website?up_message=online&down_message=offline&url=https%3A%2F%2Fwww.sungaila.de%2FNewDarkGlobalServer%2F&style=flat-square&label=website)](https://www.sungaila.de/NewDarkGlobalServer/) |
| <img src="https://raw.githubusercontent.com/sungaila/Quipbot/main/Icon.png" alt="Quipbot logo" width="48" height="48" style="min-width: 48px"> | [Quipbot](https://github.com/sungaila/Quipbot) | Runs multiple bots to play [Jackbox Games](https://www.jackboxgames.com/) autonomously. Uses [WebView2](https://aka.ms/webview) (hosted inside of [WPF](https://github.com/dotnet/wpf)) for rendering and controlling the bots. |  |
{: .project-table}

## Available in digital stores

|  | Project | Description | Links |
|---|---|---|---|
| <img src="https://raw.githubusercontent.com/sungaila/SUBSTitute/master/src/Assets/Icon.png" alt="SUBSTitute logo" width="48" height="48"> | [SUBSTitute](https://github.com/sungaila/SUBSTitute) | A GUI for mapping directories to virtual drives (see SUBST command). It is built on top of .NET and Windows UI Library 3 (WinUI 3). | <a href="https://apps.microsoft.com/store/detail/9NGPRNJJKLBG?launch=true"><img alt="Get it from Microsoft Store" src="https://get.microsoft.com/images/en-us%20dark.svg" width="128" /></a> |
| <img src="https://raw.githubusercontent.com/sungaila/SoundReaver/master/src/Assets/Icon.png" alt="Sound Reaver logo" width="48" height="48"> | [Sound Reaver](https://github.com/sungaila/SoundReaver) | A music playback app for the Legacy of Kain: Soul Reaver soundtrack. It is built on top of .NET and Windows UI Library 3 (WinUI 3). | <a href="https://apps.microsoft.com/store/detail/9pc9xxbc2wb9?launch=true"><img alt="Get it from Microsoft Store" src="https://get.microsoft.com/images/en-us%20dark.svg" width="128" /></a> |
| <img src="https://play-lh.googleusercontent.com/BXpjktDDtoOsqmoMr_L1hZVQpMROV0VsTMGAmjM4OQuuVt5U3QilPht8bO8J-eCiFfXI" alt="Roboto Digital logo" width="48" height="48" style="min-width: 48px; border-width: 0; box-shadow: 0 1px 2px 0 rgba(60,64,67,.3), 0 1px 3px 1px rgba(60,64,67,.15); background-color: #fff; border-radius: 20%;"> | [Roboto Digital](https://play.google.com/store/apps/details?id=de.sungaila.robotodigital) | A simple digital watch face using the Roboto font family. | <a href='https://play.google.com/store/apps/details?id=de.sungaila.robotodigital'><img alt='Get it on Google Play' src='https://upload.wikimedia.org/wikipedia/commons/7/78/Google_Play_Store_badge_EN.svg' width="128"/></a> |
| <img src="https://play-lh.googleusercontent.com/k6hlXb62kpGWAXbF0B4bIJm15-qAdlLXWDwUyfo4JID2uygs7jHJlnL2w_EDCJqIno0" alt="3D Animated Emoji logo" width="48" height="48" style="min-width: 48px; border-width: 0; box-shadow: 0 1px 2px 0 rgba(60,64,67,.3), 0 1px 3px 1px rgba(60,64,67,.15); background-color: #fff; border-radius: 20%;"> | [3D Animated Emoji](https://play.google.com/store/apps/details?id=de.sungaila.animateddigital) | A digital clock with a 3D animated emoji in the center. | <a href='https://play.google.com/store/apps/details?id=de.sungaila.animateddigital'><img alt='Get it on Google Play' src='https://upload.wikimedia.org/wikipedia/commons/7/78/Google_Play_Store_badge_EN.svg' width="128"/></a> |
| <img src="https://raw.githubusercontent.com/sungaila/PDFtoImage/master/src/WebConverter/wwwroot/icon-maskable.svg" alt="PDFtoImage logo" width="48" height="48" style="min-width: 48px; border-width: 0; box-shadow: 0 1px 2px 0 rgba(60,64,67,.3), 0 1px 3px 1px rgba(60,64,67,.15); background-color: #2F7D31; border-radius: 20%;"> | [PDFtoImage](https://github.com/sungaila/PDFtoImage) | A .NET library to render [PDF files](https://en.wikipedia.org/wiki/PDF) into images. | <a href='https://play.google.com/store/apps/details?id=de.sungaila.pdftoimage'><img alt='Get it on Google Play' src='https://upload.wikimedia.org/wikipedia/commons/7/78/Google_Play_Store_badge_EN.svg' width="128"/></a> <a href="https://apps.microsoft.com/store/detail/9NKMFPQKXGR8?launch=true"><img alt="Get it from Microsoft Store" src="https://get.microsoft.com/images/en-us%20dark.svg" width="128" /></a> |
| <img src="https://raw.githubusercontent.com/sungaila/PDFtoZPL/master/WebConverter/wwwroot/icon-512-maskable.png" alt="PDFtoZPL logo" width="48" height="48" style="min-width: 48px; border-width: 0; box-shadow: 0 1px 2px 0 rgba(60,64,67,.3), 0 1px 3px 1px rgba(60,64,67,.15); background-color: #37474F; border-radius: 20%;"> | [PDFtoZPL](https://github.com/sungaila/PDFtoZPL) | A .NET library to convert [PDF files](https://en.wikipedia.org/wiki/PDF) (and bitmaps) into [Zebra Programming Language commands](https://en.wikipedia.org/wiki/Zebra_(programming_language)). | <a href='https://play.google.com/store/apps/details?id=de.sungaila.pdftozpl'><img alt='Get it on Google Play' src='https://upload.wikimedia.org/wikipedia/commons/7/78/Google_Play_Store_badge_EN.svg' width="128"/></a> <a href="https://apps.microsoft.com/store/detail/9P5XMPR5MFDF?launch=true"><img alt="Get it from Microsoft Store" src="https://get.microsoft.com/images/en-us%20dark.svg" width="128" /></a> |
{: .project-table}
