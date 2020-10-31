# Vismit-pip

![pip version](https://img.shields.io/pypi/v/vismit-python) ![license](https://img.shields.io/pypi/l/vismit-python) [![Downloads](https://pepy.tech/badge/vismit-python)](https://pepy.tech/project/vismit-python)  


An application that uses hashing and encoding for generating a random password. 

Read more about this - http://ijsrset.com/paper/6777.pdf

### Installation
`
$ pip install vismit-python
`
### Usage

```
>> from vismit.PasswordGenerator import PasswordGenerator  
>> pass_gen_obj = PasswordGenerator("facebook","random",13)
>> gen_pass = pass_gen_obj.get_secret_key()
```

### Contributing

All contributions and suggestions are welcome!

1.  Fork it!
2.  Create your feature branch: git checkout -b my-new-feature
3.  Commit your changes: git commit -am 'Add some feature'
4.  Push to the branch: git push origin my-new-feature
5.  Submit a pull request

### Getting Help

If you have questions or need further guidance on using this template, please [file an issue](https://github.com/aman-roy/Extended-Substitution-Cipher/issues). I will do my best to respond to all issues in a timely manner.
