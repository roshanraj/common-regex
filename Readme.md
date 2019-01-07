# Common Regex List



| Regex  | Usages |
| ------------- | ------------- |
| /\{(.+?)\}/gm   | This is used to extract any string that starts with *'{'* and *'}'* |
| /(?<=this is)(.*)(?=sentence)/ig   | This is used to extract any string in between *this is* and *sentence*  |
| /<[^>]*>/ig | matches anything enclosed between *< and >* |
|/\{.*\:\{.*\:.*\}\}/ig | matches json |  
|/(func )([a-zA-z]+\((.*?)\))/gm | get all functions name and signature used in a file |
|/src=\"data:image\/([a-zA-Z]*);base64,([^\"]*)\"/gm | finds base64 images out of text |

