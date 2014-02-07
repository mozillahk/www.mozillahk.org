# Git Repo of mozillahk.org

This is the git repo of mozillahk.org main website based on moztw.org git. If you are interested to contribute, please feel freely to fork, modify and send pull request to us.

## Installation

### Nginx

Example of site configuration with SSI module enabled:   

    server {   
      listen 80;   
      server_name mozillahk.yourdomain.name;   

      location / {   
        root /path/to/this/repo/;   
        ssi on;   
        ssi_types text/shtml;   
        index index.html index.htm index.shtml index.php;   
      }    
    }   

## Thanks

MozTW   
http://www.moztw.org   
https://github.com/moztw/www.moztw.org
