# bt-file-search
Node JS async file search.

## Installation

``$ [sudo] npm install -g bt-file-search``

## Usage:
    
##### CLI   

    Usage:
        bt-file-search [OPTION]=[ARG]
    
    Options: 
        --DIR (required) base lookup directory
        --TYPE (optional) [D|F] D - directory, F - file
        --PATTERN (optional) regular expression to test file/directory name
        --MIN-SIZE (optional) minimum file size [B|K|M|G], skipped for directories
        --MAX-SIZE (optional) maximum file size [B|K|M|G], skipped for directories 
        
    (B - bytes, K - kilobytes, M - megabytes, G - gigabytes)    
    
##### Example:  

> The order of the parameters is NOT strict. 

``bt-file-search --DIR=./ --TYPE=F --MIN-SIZE=100M --MAX-SIZE=1G --PATTERN=\.js`` 

### License and Copyright
This software is released under the terms of the [ISC license](https://github.com/tokarskyibogdan/bt-file-search/blob/master/LICENSE.md).