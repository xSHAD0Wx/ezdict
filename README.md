# EasyDictionary

A tool for generating passwords word lists

## Usage:
### Person Dictionay:
  ```
  ./ezdict/main.py person_dict [options...]
  ```

You can see each command help by using the following syntax:
```
./ezdict/main.py <command> --help
```

### Examples:
#### Dictionay containing names and phone numbers:
  ```
  ./ezdict/main.py person_dict -n names.txt -p phones.txt -o dict.txt
  ```
### Dictionay with switched-case names:
  ```
  ./ezdict/main.py person_dict -n names.txt -s -o dict.txt
