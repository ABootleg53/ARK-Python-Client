# ARK Python Client

## Installation

```bash
yarn add github:arkecosystem/ark-js#master
pip3 install https://github.com/faustbrian/ARK-Python-Client/archive/master.zip
```

## Usage

```python
from park.park import Park

park = Park(
    '127.0.0.1',
    4002,
    '578e820911f24e039733b45e4882b73e301f813a0d2c31330dafda84534ffa23',
    '1.1.1'
)

transaction = park.transactions().create('address', 'amount', 'vendor', 'secret', 'second secret')
```

## Security

If you discover a security vulnerability within this package, please send an e-mail to Brian Faust at hello@brianfaust.me. All security vulnerabilities will be promptly addressed.

## Credits

- [Brian Faust](https://github.com/faustbrian)
- [All Contributors](../../contributors)

## License

[MIT](LICENSE) © [Brian Faust](https://brianfaust.me)
