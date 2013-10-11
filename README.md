figlet
======


Ruby [FIGlet](http://www.figlet.org/) library.


Example usage
-------------

```ruby
require 'figlet'

font = Figlet::Font.new('big.flf')

figlet = Figlet::Typesetter.new(font)

puts figlet['hello world']
```
