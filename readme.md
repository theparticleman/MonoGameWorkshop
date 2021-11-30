
## Getting Started

1. Install the MonoGame templates. Run the command `dotnet new --install MonoGame.Templates.CSharp`.
1. Install the MonoGame content tool. Run the command `dotnet tool install -g dotnet-mgcb-editor`.
1. Register the MonoGame content tool. Run the command `mgcb-editor --register`. If the `mgcb-editor` command can't be found, it may be because the dotnet global tools directory isn't in your path. The mgcb-editor tool should get installed in the `~/.dotnet/tools` directory. You may need to run it using a fully qualified path.
1. Create a new MonoGame project. Run the command `dotnet new mgdesktopgl -o PathWhereYouWantYourProjectToBeCreated`. Alternatively, you can manually create the directory where you want you project to go, then `cd` to that directory and run the command `dotnet new mgdesktopgl`.
1. Add the Aether.Physics2D package to your project. When in the directory where your project is located, run the command `dotnet add package Aether.Physics2D.MG`.
1. Make sure your project compiles and runs. Run the command `dotnet run` when in your project directory. Your program should launch as a MonoGame window with a blue background.

