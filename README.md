## GUI CALCULATOR
A sample calulator using ASP.NET

### Steps to setup the calculator (using vs-code)
1. Clone the above using `git-clone` or using `zip` files.
2. Download and install .NET depending on OS
   1. Windows OS
      - Install `choco`. (refer the [choco documentation](https://chocolatey.org/install))
      - Install dotnet-sdk using choco: `choco install dotnetcore-sdk` in powershell.
      - Install 'C#' extensions in vs-code
        - Install `C#(omnisharp)`, `C# XML Documentation Comments` and `ASP.NET Core Snippets`.
      - Create a directory for the project `mkdir ~/Calculator`
      - Navigate to the created directory `cd ~/Calculator
      - Execute the dotnet application `dotnet run`
    2. Linux OS
       - Install thye dotnet-sdk using `sudo dnf install dotnet-sdk-2.1`
       - Follow the same steps as for windows to run.
    3. Mac OS(**not tested**)
       - Install `Homebrew`. (refer the [Brew documentation](https://brew.sh))
       - Install it via `cask`
       - `brew cask install dotnet-sdk`
       - create a *dir* and execute the dotnet as explained previously.
    
