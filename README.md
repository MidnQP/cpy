# 🇨libavoidrepetition 

##### Built-in methods of   <img src=https://emoji.gg/assets/emoji/1887_python.png height=15 width=16> implemented in 🇨 for reducing sophistication, and blazing-fast performance.
<br>

#### GETTING INVOLVED
Some implementations being simple & stupid is always acceptable, unless they _degrade performance_ or _cause security issues_. To contribute code to the upstream:
1. Fork this project.
2. Make implementations that cover multiple data types.
3. Pull request.
4. Code review + Merge!!
<br>

#### ROAD-MAP
`✅`&nbsp;&nbsp;Implemented<br>
`☐` &nbsp;&nbsp;Yet to implement<br>
`::`&nbsp;Return value<br>
`[!]`Needs to support multiple data type 

```C
✅ assert(expression)        :: "True" | "False"
☐  getarg("c", "-o", "def")  :: Parses cmdline "c" of a program, and returns value against the option "-o". If not found, default value is "def"
☐  file_read(filename)       :: File's content
☐  in(arr, item)             :: 0 | 1 [!]
☐  isequal(any, any, ...)    :: 0 | 1 [!]
☐  len(any)                  :: Length of any data type [!]  
✅ max(arr, len(arr))        :: Item with the maximum value
✅ min(arr, len(arr))        :: Item with the minimum value
☐  print(any, any, ...)      :: Writes to stdout [!]
☐  self_document(__FILE__)   :: Self-documents source code, following a simple format
☐  sorted(arr, len(arr))     :: An array with the items sorted
☐  str(any)                  :: Converts any data type to str [!]
☐  str_split(str, delim)     :: An array of strings, separated by delim.
✅ substr(str, substr)       :: substring up to matched
✅ sum(arr, len(arr))        :: Sum of the array of numbers
☐  sys_out("command")        :: Unlike os.system(), this returns the output
☐  type(variable name)       :: TYPE_INT | TYPE_CHAR | TYPE_DOUBLE | ... [!]


//Let's make C behave like a scripting language!
//Unsophisticated to write, neat to read.
```
<br>

#### SPECIAL GRATITUDE

- @ahmfuad
- @koreaneggroll
- [r/coolgithubprojects](https://www.reddit.com/r/coolgithubprojects/)  &nbsp;(The subreddit with the most enthusiastic people!)
