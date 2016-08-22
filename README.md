##English ~ Myanmar Dictionary For Fedora User
======================================
#About NET DciT Dictionary

NET DicT is a English to Myanmar dictionary that can be set up in minutes and enable searching the meaning of english word to myanmar meaning.


#System Requirements
	
	NET Dict only work at Ruby 1.9.3 because most of gems are stable and support at ruby version 1.9.3. It also need green_shoes gem.

#Installation guide

it work at ruby 1.9.*


#1) install rvm (ruby version manager)

	curl https://raw.github.com/…/rvm/master/binscripts/rvm-installer | bash -s stable

#2) install ruby 1.9.3

 rvm list known
 rvm install 1.9.3
 rvm use 1.9.3
 ruby -v
ruby 1.9.3p547 (2014-05-14 revision 45962) [x86_64-linux]

#3) install ruby gem ( Green Shoes) for gui (GTk2)

 gem update
 gem install green_shoes

#4) install netdict

 git clone https://github.com/DTherHtun/netdict.git

 tar -xvf netdict.tar
 cd netdict/
 ./install

 netdict or ALT+F2 ==> netdict
