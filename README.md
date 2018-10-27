### Paint
---
.rb
https://github.com/janlelis/paint

.js


```ruby
gem 'paint'
require 'paint'

Paint['Ruby', :red]
Paint['Ruby', :red, :bright]
Paint['Ruby', :brigth, :red]
Paint['Ruby', :red, :bright, :underline]
Paint['Ruby', :red, :blue]
Paint['Ruby', nil, :blue]
Paint['Ruby', [100, 255, 5]]

Paint['Ruby', "gold", "snow"]

Paint['Ruby', '#123456']
Paint['Ruby', "fff"]
Paint['Ruby', :inverse]
Paint['Ruby', :italic, :encircle, :rapid_blink, :overline]
Paint['Ruby']

Paint%['Yello string with a %[blue_text] in it', :yellow,
  blue_text: ["blue text", :blue]
]

Paint['Ruby', Paint.random]
Paint['Ruby', Paint.random(true)]

Paint.unpaint( Paint['Ruby', :red, :bright] ).should == 'Ruby'

require 'paint/pa'
pa "Ruby", :red, :underline


```


```
```

```
```
