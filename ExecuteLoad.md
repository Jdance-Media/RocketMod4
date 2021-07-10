# Executing Code on Plugin Load

Create a class script named after your plugin by going to the Solution Explorer > Right Click > Add > Class. Your new class script should now look like this shown below.

```csharp
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace TutorialPlugin
{
    class TutorialPlugin
    {
    }
}
```

This will be the main script for the plugin, so we need to add a "RocketPlugin" interface. Shown below, add your "RocketPlugin" interface to the class. The class also needs to be public in order for other scripts to access it.

```csharp
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace TutorialPlugin
{
    public class TutorialPlugin : RocketPlugin
    {
    }
}
```

Notice how Visual Studio will tell you theres an error near where the "RocketPlugin" interface is stated? Thats because we haven't stated that we are using Rocket.Core.Plugins namespace yet. Lets add that in at the top of of script.

```csharp
using Rocket.Core.Plugins;
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace TutorialPlugin
{
    public class TutorialPlugin : RocketPlugin
    {
    }
}
```



