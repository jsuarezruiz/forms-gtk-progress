# Building Xamarin.Forms GTK Backend

## Linux

**Install the latest version of Mono**

Mono is a cross-platform, open source .Net platform.To build Xamarin.Forms under Linux, you need to have a recent version of Mono installed. You can find a great [installation instructions](http://www.mono-project.com/docs/getting-started/install/linux/) for many popular Linux distros.

Once you have your package manager configured for the Mono repository, install the `mono-devel` package, for example on ubuntu:

    sudo apt-get install mono-devel

**Clone the repository**

    git clone https://github.com/jsuarezruiz/Xamarin.Forms.git
    git submodule update --init

**Restore NuGet packages**

    cd Xmarin.Forms
    mkdir -p .nuget
    wget -O .nuget/nuget.exe https://dist.nuget.org/win-x86-commandline/latest/nuget.exe
    mono .nuget/nuget.exe restore Xamarin.Forms.sln

**Build and Run**

To build in the `Debug` configuration:

    xbuild /p:Platform=Mono /p:Configuration=Debug Xamarin.Forms.sln

## MacOS

Xamarin.Forms GTK Backend requires Visual Studio for MacOS to build on MacOS.

## Windows

Xamarin.Forms GTK Backend requires at least Visual Studio 2015 to build on Windows.

**Install GTK Sharp**

For the moment under windows, you must have [gtk-sharp](http://www.mono-project.com/download/#download-win) installed. Note that after installing the package your machine may require a restart before GTK# is added to your path. We hope to remove or make this dependency optional at some point in the future.

**Clone the Xamarin.Forms GTK Backend repository**

    git clone https://github.com/jsuarezruiz/Xamarin.Forms.git
    git submodule update --init

**Open in Visual Studio**

Open the Xamarin.Forms.sln solution in Visual Studio 2015 or newer. The free Visual Studio Community edition works fine.

