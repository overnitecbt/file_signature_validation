# file signature validation


Comprehensive tests to validate a file based on file signature. For a Django uploaded file.


## Usage

`pip install file-signature-validation`

## Methods

Tests the file name to ensure it is allowed.

`regex_file_name_test(uploaded_file, allowed_extensions, regex)`

Tests the file to ensure the file signature matches with the corressponeding mime type, extension and given size.

`file_type_test(uploaded_file, allowed_type, allowed_mimes, allowed_extensions, allowed_size)`

Runs the file through all of the above tests.

`acceptable_file(uploaded_file, allowed_types, allowed_mimes, allowed_extensions, allowed_size, regex)`


## Disclaimer

The authors and contributors of this package can not be held liable for any false positives or damage caused by the use of the file signature validation package.