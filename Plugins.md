# Getting Started With RocketMod4

  1. Download Visual Studio Community from https://visualstudio.microsoft.com/vs/
  2. When installing Visual Studio make sure to pick package options shown that involve .NET
  3. Create a new class library project with a .NET Framework version of 4.6.1
  
Once you have created your project go to the Solution Explorer window normally on the right side of your screen and right click on References > Add Reference. Once in the add references tab click on Browse and go to Unturned Local Game Files > Unturned_Data > Managed and select/import these .dll files listed below.

```
Assembly-CSharp.dll
SDG.NetTransport.dll
Steamworks.NET.dll
UnityEngine.dll
UnityEngine.CoreModule.dll
```

Once you have imported those files go back to Browse and go to Unturned Local Game Files > Extras > Rocket.Unturned and select/import these .dll files listed below.

```
Rocket.API.dll
Rocket.Unturned.dll
Rocket.Core.dll
```

You have now set up your very first plugin project in Visual Studio!

### Guides

[Executing Code On Plugin Load](ExecuteLoad.md)
