# PyBitCrypt

This is an encrypting and decrypting module. 
It uses a key to shift the letters by the key.

Encoding:

```python
from PyBitCrypt import pbc
key = 'SampleKey1!'
text = 'SampleText1!'
encoded = pbc.encrypt(key, text)
```

Decoding:
```python
from PyBitCrypt import pbc
key = 'SampleKey1!'
text = 'SampleText1!'
encoded = pbc.encrypt(key, text)
```

Enjoy!
