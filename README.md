# nlp-playground

## Common Regex Patterns
| pattern       | matches                              | example        |
| -------       | -------------------------------------| -------        |
| \w+           | word                                 | 'Magic'        |
| \d            | digit                                | 9              |
| \s            | space                                | ''             |
| .*            | wildcard                             | 'username74'   |
| + or *        | greedy match                         | 'aaaaa'        |
| \S            | *not* space                          | 'no_spaces'    |
| [a-z]         | lowercase group                      | 'abcdefg'      |
| [A-Za-z]+     | upper and lowercase English alphabet | 'ABCDefghij'   |
| [0-9]         | numbers from 0 to 9                  |  9             |
| [A-Za-z\-\.]+ | upper and lowercase English, - and . | My-website.com |
| (a-z)         | a, - and z                           | 'a-z'          |
| (\s+|,)       | spaces or a comma                    | ','            |