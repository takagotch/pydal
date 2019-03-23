### pydal
---
https://github.com/web2py/pydal

```py
from pydal import DAL, Field
db = DAL('sqlite://storage.db')
db.define_table('thing', Field('name'))
db.thing.insert(name='Chair')
query = db(query).name.startswitch('C')
rows = db(query)select()
print rows[0].name
db.commit()
```

```sh
pip install pyDAL

```

```
```


