
# Setting up C# Function App in Azure Function App using Visual Studio Code

1. Install the below extensions in VSCode:

    - Azure Functions
    - C# Dev Kit
    - Azure Resources
    - Azurite

2. Open VSCode and search for "Azure Functions: Install or Update Azure Function Core Tools"

- Install it manually, if the installation fails through VSCode.

3. Check the version

    ```sh
    func --version
    ```

4. Run the below commands and follow the promt

    ```sh
    func init
    func new
    ```

5. Install dotnet & releated packages, if they are not present

    ```sh
    choco install dotnet
    dotnet add package Microsoft.NET.Sdk.Functions
    ```
