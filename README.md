# megeosx_fix

Many issues in macOS.
1. Solved third-part issues, like use the latest crpto++ on macOS. 
2. Solved curl issue. doc/OSX is a little bit out-of-date. Like this cannot work with the latest curl. 
   brew install --with-openssl curl
3. Added namespace since I use the latest crpto++. 
4. osx/megafs.h has dependency problems. Solved them. 
