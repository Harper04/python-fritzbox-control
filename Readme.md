This is a library to programmagicly control your fritzbox.

A short example.
```python
from lib import FritzControl
fC = FritzControl(conf="./conf.json")
fC.setWifiPassword("safePassword")
```
```bash
./fritzcontrol.py -c ./conf.json setWifiPassword safePassword
```


Feel free to implement your own commands and offer pull requests.