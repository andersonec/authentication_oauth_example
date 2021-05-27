*** OAUTH AUTHENTICATION TESTS - By. Anderson Santos ***

Gerar projeto utilizando do tutorial:
    https://docs.microsoft.com/pt-br/aspnet/core/security/authentication/social/?view=aspnetcore-5.0&tabs=visual-studio-code

    dotnet new webapp -o <nomeApp> Idividual -uld

    Configurando provedores de autenticação por logon: 
        Google:
            dotnet add package Microsoft.AspNetCore.Authentication.Google --version 5.0.6

        Microsoft:
            dotnet add package Microsoft.AspNetCore.Authentication.MicrosoftAccount --version 5.0.6

        Facebook:
            dotnet add package Microsoft.AspNetCore.Authentication.Facebook --version 5.0.6
            Tuto:
                https://docs.microsoft.com/pt-br/aspnet/core/security/authentication/social/facebook-logins?view=aspnetcore-5.0
                App Id: 229464205283002
                Secret Key: 24d4f5bab5fd0e4142eb55c22c3b94b7
