# Integrity-check-and-Authenticity-check-

- https://chat.openai.com/c/61d7abe1-3aee-4666-acb4-12ae95fe92c9
- https://stackoverflow.com/questions/21956954/how-to-check-the-checksum-through-commandline
- https://stackoverflow.com/questions/48972597/how-to-use-sha256sum-check-option-to-fail-if-incorrect-hash-on-a-docker-script


```
shasum -a256 nmap.exe
shasum -a256 nmap.exe > checksum
shasum -c checksum
```
