# MyGit

A simplified Git implementation written in Python that recreates core Git functionality using content-addressable storage.

## Features

- init
- add
- commit
- status
- log
- branch
- checkout

## Internals

- Blob objects
- Tree objects
- Commit objects
- SHA-1 hashinghttps://github.com/shirshak-18/myGit
- Object storage in .mygit/objects
- Branch references
- Working directory restoration

## Example

python main.py init
python main.py add hello.txt
python main.py commit -m "Initial commit"

## Future Improvements

- diff
- merge
- gitignore support
