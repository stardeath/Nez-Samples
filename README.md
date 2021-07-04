# Nez-Samples

Samples and demos of various [Nez](https://github.com/prime31/Nez) features. The Samples repo is built against MonoGame 3.5.


Setup
----
- Pull a fresh copy of the Nez-Samples repository. The samples repository has the base Nez repository as a submodule so to fully download everything you need add the `--recursive` parameter when cloning:

`git clone --recursive https://github.com/prime31/Nez-Samples.git`

- now you can open the `Nez.MG17.Samples.sln` (for MonoGame 1.7) or the `Nez.MG18.Samples.sln` (for MonoGame 1.8 and NET Core 3) and run the project (for NET Core 3 you can also run with the command `dotnet run --project Nez.MG18.Samples.csproj`)


Sample Scenes
----
You can click on any of the sample scene buttons on the right of the screen to load samples. If you are running a debug build, you can press the backtick key to open the debug console. Type "help" and press enter to see a list of available commands. You can type "help COMMAND" to see additional help text. Entering the "toggle-imgui" command will open an ImGui inspector letting you play around with the various entities in the scene.


Setup FNA
----
- download the latest release of FNA from [here](https://github.com/FNA-XNA/FNA/releases/tag/19.09) and put it into a folder named `FNA` in the Nez-Samples folder
- download the native libs FNA requires from [here](http://fna.flibitijibibo.com/archive/fnalibs.tar.bz2) into the `fnalibs` folder in the Nez-Samples folder
- open the `Nez.FNA.Samples.sln`


Assets License
----
Unless otherwise noted, the assets in the Nez Samples repo project are not MIT licensed. They should not be used in any project. Most are of unknown copyright/origin so assume they are all off limits and use them only for your own personal amusement.
