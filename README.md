*** OAUTH AUTHENTICATION TESTS - By. Anderson Santos ***

Gerar projeto utilizando do tutorial:
    https://docs.microsoft.com/pt-br/aspnet/core/security/authentication/social/?view=aspnetcore-5.0&tabs=visual-studio-code

    dotnet new webapp -o <nomeApp> Idividual -uld

    Configurando provedores de autenticação por logon: 
        Google:
            dotnet add package Microsoft.AspNetCore.Authentication.Google --version 5.0.6
            Client Id: 83849151947-lla6l5mrep1fsn0bpj8gvo098e4t6ldt.apps.googleusercontent.com
            UTILIZAR:
                dotnet user-secrets set "Authentication:Google:ClientId" "83849151947-lla6l5mrep1fsn0bpj8gvo098e4t6ldt.apps.googleusercontent.com"
            Client Key: M_GnWZ1VrBtP7KQXrmwk-xHu
            UTILIZAR:
                dotnet user-secrets set "Authentication:Google:ClientSecret" "M_GnWZ1VrBtP7KQXrmwk-xHu"

            https://console.cloud.google.com/apis/credentials?project=consumoviacep&folder=&organizationId=

        Facebook:
            dotnet add package Microsoft.AspNetCore.Authentication.Facebook --version 5.0.6
            Tuto:
                https://docs.microsoft.com/pt-br/aspnet/core/security/authentication/social/facebook-logins?view=aspnetcore-5.0
                App Id: 229464205283002
                UTILIZAR:
                    dotnet user-secrets set "Authentication:Facebook:AppId" "229464205283002"
                Secret Key: 24d4f5bab5fd0e4142eb55c22c3b94b7
                UTILIZAR:
                    dotnet user-secrets set "Authentication:Facebook:AppSecret" "24d4f5bab5fd0e4142eb55c22c3b94b7"
            
            https://developers.facebook.com/apps/

    ** VERIFICAR ERRO DE PERMISSÃO **
        Microsoft:
            dotnet add package Microsoft.AspNetCore.Authentication.MicrosoftAccount --version 5.0.6
            Tuto:
                https://docs.microsoft.com/pt-br/aspnet/core/security/authentication/social/microsoft-logins?view=aspnetcore-5.0
                App Id (cliente): f54ce8b2-a353-42fe-8ec4-f6247663ad07
                Objeto Id: 30d03016-7c67-4318-ab36-26f4c3b8d749
                Diretório Id (locatário): f8cdef31-a31e-4b4a-93e4-5f571e91255a
                Valor: 57hECE._Wr~-oTcH9RKJN8yc~V59H6m.w-
                Secret Key: 24b2e7f1-203a-426e-861f-cf789be97566
