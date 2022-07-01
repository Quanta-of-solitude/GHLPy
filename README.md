# GHL v1 Python Wrapper
> A GHL Python wrapper for persomal use, doesn't contain all the methods as of now.
> May not be stable xd

<br/>

## Table of Content 

- [Installation](#installation)
- [Requirements](#requirements)
- [Available Methods](#available-methods)
- [Example](#example)
- [Contribute](#contribute)

<br/>

### Installation
---

Available at [PyPI](https://pypi.org/project/GHLPy/)
```
pip install GHLpy
```

<br/>
### Requirements
---
> Used runtime: Python 3.8

```
requests
json
```

<br/>

### Available methods
---

```
 'add_contactTag', 'bookAppointment', 'contact_appointments', 'create_contactByName', 'delete_appointmentById', 'endpoint', 'get_appointmentById', 'get_calendarBookedSlots', 'get_calendarFreeSlots', 'get_calendars', 'headers', 'lookup_contactByEmail', 'lookup_contactById', 'remove_contactTag', 'token', 'update_appointmentById', 'update_appointmentStatusById'

```

There is no documentation as of now for this package, you can use help() to get information

```python
from GHL import GHLPy

print(help(GHLPy))
```

The official API Reference for GHL v1 Endpoint is extensive and detailed as well. It can be found [here](https://public-api.gohighlevel.com/)

<br/>

### Example
---

To get information on calendars associated:
```python
from GHL import GHLPy

client = GHLPy("mytoken")

r = client.get_calendars(type="service") #type="teams" Default: services

print(r)
```

<br/>

### Contribute
---

Well, this was just for personal use, but if you wish to contribute, you are welcome to make PRs 

<br/>

>To be updated
<br/>
Have Fun!
