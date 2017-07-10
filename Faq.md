# Faq

**What is Gtk#?**

Gtk# is a Graphical User Interface Toolkit for mono and .Net. The project binds the gtk+ toolkit and assorted GNOME libraries, enabling fully native graphical Gnome application development using the Mono and .Net development frameworks.

Features:

- Multi-platform (UNIX, Windows, MacOS).
- Wide range of Widgets/Controls.
- Accessible via the ATK accessibility toolkit.
- Internationalization.
- Available from C#, Java, Python, VB.Net and more.
- UI Builder support.
- Open Source, Free Software.

**What version of Gtk# is used?**

Gtk # 2.12 is used. There are differents Xamarin and community tools developed with Gtk# 2. 

**What platforms are supported?**

Linux, MacOS and Windows are supported. This includes not just diversity on desktop platforms. For example, Windows XP, Windows 7, Windows 8 or Windows 10 in the case of Windows. Also diversity of devices. Run a Xamarin.Forms app on a raspberry pi?. Yes!
Xamarin.Forms will support all major mobile platforms along with all major desktop platforms.

**What Xamarin.Forms support is included in the GTK backend?**

All pages, layouts and controls (including maps) are supported on the GTK backend.

**And what about new Xamarin.Forms options (Ex: Forms Embedding)?**

Effects, Platforms Specifics, or Forms Embedding are supported options.

**Can I extend functionallity to new platforms by creating new controls?**

Absolutely!. You can create effects or custom renders in the same way as iOS or Android.

**What has been used with the WebView control?**

Internally the browser control makes use of [webkit-sharp](https://github.com/mono/webkit-sharp).

**What has been used with the Map control?**

Internally the Map control makes use of [GMaps.NET](https://github.com/radioman/greatmaps).

**How can I use all this today?**

Is recommended reading the [Getting Started](Getting-Started.md) section. Basically, you need to sync and compile the repository to access to the `Xamarin.Forms.Platforms.GTK.dll` library.

**How will I use the Xamarin.Forms GTK Backend in the future?**

Like the rest of platforms. Using NuGet packages and project templates.