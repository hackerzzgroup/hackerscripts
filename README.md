# hackerscripts

scripts and things

## audio
- twerk (formally ricenp)
    - supports many players
    - supports last.fm
    - can format output for xfce4-genmon-plugin if specified
    - has multiple formats
- toggle_vol
    - toggles volume between headphones and speakers
    - probably depends on your audio card

## fun
- jimmies
    - also known as the jimmy rustler 2000
    - takes two random words from dictionaries installed on ystem and rustles jimmies with them
    - providing all as an argument will make it look through all dictionaries in /usr/share/dict/, otherwise it will just use /usr/share/dict/words

## util
- takenotes
    - saves everything into ${XDG_CONFIG_HOME}/takenotes/
    - small note-saving program
    - sits in tray and waits for a left click or clicking Take Notes in the menu
    - requires [yad](https://code.google.com/p/yad/)
- brightness
    - changes monitor brightness
    - monitor used is customizable
    - requires sudo (blame good security)
- pwgen
    - generates a password, each repeat never repeats characters.
    - repeats and amount of characters is configurable

## web
- gmail_open
    - parses mailto links to work with gmail's web interface
        - parses cc, bcc, subject, body, and to
    - useful for setting as default email client
    - if given no url it just opens mail.google.com
- imgurdl
    - downloads each image in an imgur album
    - can download multiple albums, just provide multiple links
- pyfilesh
    - interfaces with a pyfileserv server
