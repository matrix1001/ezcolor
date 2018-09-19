# ezcolor
very simple color module with several lines.
# install
python setup.py install
# useage
supported color:
`black` `red` `green` `yellow` `blue` `purple` `cyan` `white`

supported stype:
`default` `bold` `underline` `on` `on2`

api:

llegal format: 
    - `color.[style]_[fg_color]_bg_[bg_color](msg)`
    - `color.[fg_color](msg)`
    - `color.bg_[bg_color](msg)`
```
from ezcolor import color
print(color.on_red('test red'))
print(color.bold_red_bg_white('test 2'))
```