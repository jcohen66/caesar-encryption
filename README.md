# caesar-encryption

### Overview

Implements the techniques found in:

https://blog.sicara.com/perfect-python-command-line-interfaces-7d5d4efad6a2

### Usage

```python
python3 caesar_script.py --key 23 --decrypt my secret message

python3 caesar_script_using_sys_argv.py

python3 caesar_script_using_argparse.py --encode My message

python3 caesar_script_v2.py --decrypt --input_file wrong_file.txt

python3 caesar_script_v2.py --encrypt --key 2

python3 caesar_script_v2.py --encrypt --input_file pirate.txt --output_file ciphertext.txt   

python3 cypher_text_with_progress_bar.py  --input_file ciphertext.txt --output_file plaintext.txt

python3 caesar_breaker.py --input_file ciphertext.txt --output_file plaintext.txt

```