energyhelpline's repository of Vagrantfiles
===

You know the drill: 

1. [Install vagrant ](https://www.vagrantup.com/downloads.html)
2. Copy the contents of the file in which your interested in to your Vagrantfile
3. `vagrant up` and away you go!

Vagrantfiles
---

1.  Vagrantfile-install-ruby-233-with-rbenv-and-run-bundle-install

    Installs everything needed to install Ruby 2.3.3 and bundler on a hashicorp/precise64 box and nothing more!

    So that's git, make, rbenv, rbenv-build and bundler.

    Runs bundle install on your /vagrant folder so you should be ready to go as soon as you `vagrant ssh` in.
