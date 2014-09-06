

This is a library to programmagicly control your fritzbox.

Installation
------------
```bash
pip install fritzcontrol
```


Usage
-----

A short example.
```python
from lib import FritzControl
fC = FritzControl(conf="./conf.json")
fC.setWifiPassword("safePassword")
```
```bash
./fritzcontrol.py -c ./conf.json setWifiPassword safePassword
```

A short example if installed by pip.
```python
from fritzcontrol.lib import FritzControl
fC = FritzControl(conf="./conf.json")
fC.setWifiPassword("safePassword")
```

Feel free to implement your own commands and offer pull requests.
