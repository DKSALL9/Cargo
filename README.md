# Cargo
 This Perl script processes URLs by modifying their query parameters based on command-line options. It handles a variety of tasks like appending or replacing query parameters, customizing the port and scheme, ignoring the path during duplicate detection, and optionally checking if the modified links work.

# Install
```
git clone https://github.com/DKSALL9/Cargo.git
```

# Usage
```
   ___    __ _   _ __    __ _    ___  
  / __|  / _` | | '__|  / _` |  / _ \ 
 | (__  | (_| | | |    | (_| | | (_) |
  \___|  \__,_| |_|     \__, |  \___/ 
                        |___/     

Usage: cargo.pl [-a] [--ignore-path] [-p PORT] [-s SCHEME] [--check-links] [-h]
-a            Append the value instead of replacing it
--ignore-path Ignore the path when considering what constitutes a duplicate
-p PORT       Specify a custom port number
-s SCHEME     Specify a custom scheme (http/https)
--check-links Check if the modified link works or not
-h            Display this help message

```
