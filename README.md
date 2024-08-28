Intro
Purpose
Install .NET, Visual Studio Code, and create your first application.

Prerequisites
500 MB of available hard-drive space.

Time to complete
5 minutes + download/installation time

Scenario
A simple application written in C# that prints Hello, World! to your VS Code console.

Not ready to install anything?
You can try our in-browser tutorial instead.
Download and install
To build your first .NET application with Visual Studio Code, set up your environment:

Download and install the .NET SDK:

Download .NET 8 SDK (64-bit) 

Download and install VS Code:

Download VS Code 

Open VS Code and select the Extensions button in VS Code's Activity Bar to the left. Type C# in the search bar, select C# Dev Kit, and then select the Install button on the C# Dev Kit extension page.

VS Code's C# Dev Kit'

Check everything installed correctly
Once you've set up your environment, open a new VS Code terminal. In the toolbar, select Terminal, then New Terminal.

VS Code New Terminal

In your terminal, run the following command to check your installation.

Terminal
dotnet
Run dotnet command in VS Code Terminal

If the installation succeeded, you should see an output similar to the following:

Terminal
Usage: dotnet [options]
Usage: dotnet [path-to-application]

Options:
-h|--help         Display help.
--info            Display .NET information.
--list-sdks       Display the installed SDKs.
--list-runtimes   Display the installed runtimes.

path-to-application:
The path to an application .dll file to execute.
If everything looks good, select the Continue button below to go to the next step.

Got an error?
If you receive a 'dotnet' is not recognized as an internal or external command error, make sure you opened a new VS Code terminal. If restarting VS Code or restarting your machine doesn't resolve the issue, use the I ran into an issue button to get help fixing the problem.
Create your app
Open the command palette in VS Code by pressing CTRL+SHIFT+P.
Type .NET: to see the commands you can run with C# Dev Kit!
Find and select .NET: New Project to create a new .NET project.
Scroll down and select Console App.
Choose the folder location you'd like to save your project.
Name the project MyConsoleApp in the command palette when prompted.
If you have a Visual Studio Subscription, sign into your account. If you do not see a prompt pop up, click on the C# icon in VS Code's Status Bar towards the bottom right of your window.

Sign in with VS Subscription

In VS Code's Side Bar, make sure the Explorer is open. Here you should see a folder and the Solution Explorer. If you've opened a new instance of VS Code, the Solution Explorer may be near the bottom of the sidebar.

VS Code's Solution Explorer

The main file in the MyConsoleApp folder is called Program.cs. By default, it already contains the necessary code to write Hello, World! to the terminal. Click on the file to see the code created by the template:

Program.cs in Solution Explorer

Select the Continue button below to go to the next step.

Got an error?
If you can't resolve the issue you're having, select the I ran into an issue button below to get help fixing the problem.
Run your app
To run your application, select the dropdown menu to the right of the run button in the top right, and select Run project associated with this file.

Run application using VS Code run button

You should see Hello, World! in your VS Code terminal.

Terminal
Hello, World!
Congratulations, you've built and run your first .NET app! Select the Continue button below to go to the next step.
Edit your code
In the Program.cs file, add the highlighted line after the code that prints Hello, World!, like the following:

Program.cs

Copy
// See https://aka.ms/new-console-template for more information
Console.WriteLine("Hello, World!");
Console.WriteLine("The current time is " + DateTime.Now); 
Save the Program.cs file and select Run project associated with the file again. If you succeed, you should see an output similar to the following:

Terminal
Hello, World!
The current time is 8/28/2024 5:15:09 PM
Next steps
Congratulations, you've built and run your first .NET app!

Keep learning
To keep learning general .NET skills, try our tutorials on Microsoft Learn where you'll learn about .NET, dependencies, working with files, debugging, and more:

Build .NET applications learning path 

Learn C#
C# is .NET's modern, innovative, open-source programming language for building all your apps. Get started by trying our C# interactive tutorials on Microsoft Learn:

Take your first steps with C# on Microsoft Learn 

.NET for Beginners
Let Claudia walk you through the basics of .NET with her beginner video series:

