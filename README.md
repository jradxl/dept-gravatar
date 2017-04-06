# dept-gravatar
DEPT gravatar server

Forked, with thanks, from:-
https://github.com/deptagency/dept-gravatar
https://blog.deptagency.com/console-applications-in-net-core-684fcfd9a6e8

Other references:-
http://stackoverflow.com/questions/38706959/net-core-console-applicatin-configuration-xml/38713604#38713604
http://stackoverflow.com/questions/39573571/net-core-console-application-how-to-configure-appsettings-per-environment
http://stackoverflow.com/questions/38114761/asp-net-core-configuration-for-net-core-console-application
https://andrewlock.net/using-dependency-injection-in-a-net-core-console-application/
https://weblogs.asp.net/ricardoperes/net-core-console-applications
http://michaconrad.com/Documentation/Blog/aspnet_5_accessing_environment_variables
https://docs.microsoft.com/en-us/aspnet/core/fundamentals/environments
https://docs.microsoft.com/en-us/aspnet/core/fundamentals/environments
https://blogs.msdn.microsoft.com/luisdem/2016/06/01/creating-a-net-core-application-in-just-5-minutes/



User Secrets:
http://asp.net-hacker.rocks/2016/07/11/user-secrets-in-aspnetcore.html

Program.cs, line 97, this "configuration.AddUserSecrets();" is deprecated.
Suggests configuration.AddUserSecrets(string userSecretsId);

In D.Applications.GravatarImporter.csprog, on line 8, edit
<UserSecretsId>Your Secret ID</UserSecretsId>
Microsoft.Extensions.SecretManager.Tools version 1.0.0 changed to 1.0.0-msbuild3-final


Facebook Graph API
https://graph.facebook.com/ suggest you go to:-
https://developers.facebook.com/docs/graph-api

See:-
https://developers.facebook.com/docs/graph-api/overview

To get an Access Token, start the Graph Explorer
https://developers.facebook.com/tools/explorer
from the blue button in the Overview. You don't need to use Facebook at this point.

Then I gave up....
