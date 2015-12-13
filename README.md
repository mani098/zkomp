# Zkomp
[![Join the chat at https://gitter.im/Bash-it/bash-it](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/manikandancsea/zkomp)

Zkomp is a light weight command line archive manager for all linux distros.

  - Create archives.
  - Extract files from archive.

## How to use ?

Zkomp is very ease to use. 

- Download the [zkomp](https://github.com/manikandancsea/zkomp/archive/master.zip)
- Extract it and goto `zkomp` folder 
- run `./zkomp --help`

## Example

- Compress/Archive
  - `./zkomp -p ~/Downloads/gitbook`  Default format to archive is `.tar.gz`
  - `./zkomp -p ~/Downloads/gitbook -f iso` The default format can be overided by -f(or)--format
- Extract
  - `./zkomp -p ~/downloads/gitbook.tar.gz` <br/>
  - `./zkomp -p ~/downloads/gitbook.iso`

##### Task List

- [ ] &nbsp; Save the archive in a different format.      
- [x] &nbsp; Tar GZip (.tar.gz)              
- [x] &nbsp; Tar format (.tar)
- [x] &nbsp; Tar Bzip2 (.tar.bz2)
- [x] &nbsp; ISO format (.iso)
- [ ] &nbsp; ZIP Archive (.zip)
- [ ] &nbsp; Z format (.Z)
- [ ] &nbsp; 7-Zip Compressed File (.7z)