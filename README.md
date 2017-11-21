
1.	install the ruby first 32/64 bit according to your PC
2.	open ruby command prompt from start
3.	then run the command: "gem install sass"
if facing problem to install like:
"Unable to download data from https://rubygems.org/ - SSL_connect retur ned=1 errno=0 state=SSLv3 read server certificate B: certificate verify failed ( https://rubygems.org/latest_specs.4.8.gz)"

then run these two commands below:
gem sources --remove https://rubygems.org/
gem sources -a http://rubygems.org/

Now run "gem install sass"

run the command to compile the sass files in below format:

sass --watch input-dir:output-dir

sass --watch main.scss:style.css 
