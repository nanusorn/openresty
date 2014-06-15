./configure --add-module=bundle/nginx-push-stream-module --with-luajit --with-cc-opt="-I/usr/local/include" --with-ld-opt="-L/usr/local/lib"

pcre lib need to be installed first, make install is needed.

clone push stream module into bundle folder
git clone https://github.com/wandenberg/nginx-push-stream-module.git

