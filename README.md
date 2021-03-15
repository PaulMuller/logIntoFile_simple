# logIntoFile_simple
simple js logs into txt file without depencies

use it simple as:
```javascript
const Log = require('./log').logToFile

Log('all ok!')
Log('all ok!', './IntoAnotherFile.log')
```
result is a text file with specified name (if not exist, no need create log file manually) thats receive new row on each `Log(str)` operation
```
[2021.03.15  03:12:32]: all ok!
[2021.03.15  03:13:45]: all ok!
[2021.03.15  03:18:18]: all ok!
```
