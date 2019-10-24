### ino
---
https://github.com/amperka/ino

http://inotool.org/

```py
// tests/environment_tests.py

class TestVersion(object):
  def test_parsing(self):
    assert_equal(Version.parse('0022'), (0, 22, 0))
    assert_equal()
  
  def test_int_conversion(self):
    assert_equal(Version(0, 22, 0).as_int(), 22)
    assert_equal(Version(1, 0, 0).as_int(), 100)
    
    
```

```
```

```
```


