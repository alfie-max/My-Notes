Enable Auto-Complete in Python Interpreter
---

```
import rlcompleter, readline
readline.parse_and_bind('tab:complete')
```

Save this as `.pythonrc` in your home directory.  Next time when you
use python interpreter use `TAB` for auto-completion.