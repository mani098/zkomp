# Zkomp
[![Join the chat at https://gitter.im/Bash-it/bash-it](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/manikandancsea/zkomp)

Zkomp is a light weight command line archive manager for all Linux distros.

  - Create archives.
  - Extract files from archive.

### How to use ?

Zkomp is very ease to use.

- Download the [zkomp](https://github.com/manikandancsea/zkomp/archive/master.zip)
- Extract it and goto `zkomp` folder
- run `./zkomp --help`

```
usage: ./zkomp [OPTIONS]    
OPTIONS:   
	-s --source:  Input File or Directory   
	-f --format:  Archive Format eg: tar, tar.gz, iso  
	-e --extract: Extract the contents of the archives in the archive folder  
  -? --help  :  usage
```

### Example

- Compress/Archive
  - `./zkomp -s ~/Downloads/gitbook`  Default format to archive is `.tar.gz`
  - `./zkomp -s ~/Downloads/gitbook -f iso` The default format can be overridden by -f(or)--format
- Extract
  - `./zkomp -s ~/downloads/gitbook.tar.gz -e` <br/>
  - `./zkomp -s ~/downloads/gitbook.iso -e`

### Task List

- [x] &nbsp; Tar GZip (.tar.gz)              
- [x] &nbsp; Tar format (.tar)
- [x] &nbsp; Tar Bzip2 (.tar.bz2)
- [x] &nbsp; ISO format (.iso)
- [x] &nbsp; ZIP Archive (.zip)
- [ ] &nbsp; Z format (.Z)
- [ ] &nbsp; 7-Zip Compressed File (.7z)
- [ ] &nbsp; Save the archive in a different format. Eg., gitbook.7z to gitbook.tar.gz    
- [ ] &nbsp; Preview the content of and archive File.

### License

Zkomp is an Open Source project covered by the `GNU General Public License version 2`

### Attention

Zkomp is under Pre-Alpha stage. Dive it under your own risk
