# Git Secrets
_A naive way of using credentials without tracking it on github._
## Procedure
Create new file in *src* called *Credentials.h*. Example:

```
#include <Arduino.h>
extern const String PASSWORD = "adfkasdf";
extern const String IP = "192.168.1.1";
```

You can now use these variables if you import Credentials. Credentials.h is added to the _.gitignore_-file ensuring that this info will not be tracked.