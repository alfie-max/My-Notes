Enable Auto-Complete in Ruby Interpreter
---

First install `wirble`

`sudo gem install wirble`

Add following lines to `~/.irbrc`

```
#!/usr/bin/ruby 
require 'irb/completion'
require 'rubygems'
require 'wirble'
 
Wirble.init
Wirble.colorize
```

Next time when you use Ruby interpreter use `TAB` for auto-completion.
