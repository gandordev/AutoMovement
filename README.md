<h1 align="center" id="title">AutoMovement</h1>

<p align="center"><img src="icons/AutoMovement.png" alt="AutoMovement icon" width="160"></p>

[![❓ Usage Instructions (EN/ES)](https://img.shields.io/badge/❓-Usage%20Instructions-yellow?style=flat)](#usage-instructions)
![💻 Built with C#](https://img.shields.io/badge/💻%20Built%20with-C%23-f08080?style=flat&logo=csharp&logoColor=white)
![🛡️ License: GNU GPL v3](https://img.shields.io/badge/🛡️%20License-GNU%20GPL%20v3-green?style=flat)



> [!WARNING]  
> This program was originally created for Fortnite, but it can be used with other applications that respond to simulated keyboard and mouse input. Its use may be subject to the terms of service of the application being controlled.



<h2>🧐 Features</h2>

Here're some of the project's best features:

*   Simulates key presses (W S Space) and random mouse clicks
*   Starts with two brief Space presses, waits 1 second, then holds Space for a configurable duration
*   Allows you to choose when to start the process by left-clicking on the desired window
*   Random wait times between actions (3-30 seconds)
*   Random key press durations (2-5 seconds)
*   Stop the process by setting a maximum duration (in minutes) or by configuring a custom key
*   Optionally shuts down the computer when the maximum duration is reached



<h2>📝 Requirements</h2>

These steps are required to make the program work properly:

* Windows

* .NET Framework 4.7.2 or higher

* Visual Studio 2019/2022 or .NET SDK for compilation



<h2>🚀 Release Build</h2>

To create a release version for distribution:

<p>1. Open a terminal in the repository root</p>

<p>2. From the repository root, run: `dotnet publish .\src\AutoMovement.csproj -c Release`</p>

<p>3. The compiled application will be available in `src\bin\Release\net472\publish` as `AutoMovement.exe`</p>

<p>4. Share the contents of this folder with users who want to run the application</p>

<p>5. Users only need to run the `AutoMovement.exe` file to start the application</p>

<p>Every time a pull request is merged into `main`, the workflow builds the app on Windows and creates a uniquely numbered GitHub Release with the executable and its configuration file attached.</p>



<h2>🛠️ Installation Steps:</h2>

<p>1. Clone or download this repository</p>

<p>2. Open a terminal in the project folder</p>

<p>3. Run: `dotnet build .\src\AutoMovement.csproj`</p>

<p>4. Run: `dotnet run --project .\src\AutoMovement.csproj`</p>



<h2 id="usage-instructions">❓Usage Instructions:</h2>

<h3>🇪🇳 English</h3>

<p>1. Start the application</p>

<p>2. Configure if you want to set a maximum duration</p>

<p>3. Configure if you want to use a key to stop the process, and optionally enable computer shutdown when the maximum duration is reached</p>

<p>4. Left-click on the window where you want to send input</p>

<p>5. At startup, the application taps Space twice with a brief release between presses, waits 1 second, then holds Space for the duration configured in the code before simulating movements automatically</p>

<h3>🇪🇸 Spanish</h3>

<p>1. Inicia la aplicación</p>

<p>2. Configura si quieres establecer una duración máxima</p>

<p>3. Configura si quieres usar una tecla para detener el proceso y, opcionalmente, marca la casilla para apagar el ordenador al alcanzar la duración máxima</p>

<p>4. Haz clic izquierdo en la ventana a la que quieras enviar las entradas</p>

<p>5. Al inicio, pulsará Espacio dos veces brevemente, soltándolo un instante entre pulsaciones; esperará 1 segundo y mantendrá Espacio durante el tiempo configurado en el código</p>
