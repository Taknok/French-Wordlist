# French Wordlist

Wordlist from : https://www.freelang.com/download/misc/liste_francais.zip

Cleaned with :

    export LC_ALL=C.UTF-8
    iconv -f WINDOWS-1252 -t UTF-8 liste_francais.txt > utf.txt
    nano, ctrl + \, œ, [enter], oe, [enter], A
    iconv -f utf-8 -t ascii//TRANSLIT//IGNORE < utf.txt > francais.txt
