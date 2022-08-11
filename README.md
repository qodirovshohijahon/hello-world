# c-labs
This for my c codes which written in c lessons

```python
# import datetime
# # Write Python 3 code in this online editor and run it.
# data = datetime.datetime.now()
# print(data.isoformat())

import datetime
from dateutil.parser import parse

def age_days(data):
    parsed = parse(data).replace(tzinfo=None)
    print(parsed)
    diff = datetime.datetime.now() - parsed
    return diff.days
    
# age_days(datetime.datetime.now().isoformat()) == 0



```
