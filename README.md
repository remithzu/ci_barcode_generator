# ci_barcode_generator
This is a barcode component of the Zend Framework modified for the Codeigniter libraries. This is made to be easier to use on codeigniter and easier to generate barcode.

### How to use
>Load library<br>
$this->load->library('zend');


>Load helper<br>
$this->load->helper('barcode');

```php
generate_barcode('code128','1234567890')
```


### Barcode Encoding
- std25
- int25
- ean8
- ean13
- upc
- code11
- code39
- code93
- code128
- codabar
- msi
- datamatrix


### Reference
- File issues at https://github.com/zendframework/zend-barcode/issues
- Documentation is at https://zendframework.github.io/zend-barcode/
