Ariadne
=======

> Remember, Ariadne, you are the dreamer, you build this world. I am the
> subject, my mind populates it.
>
> *-- Cobb, Inception*

 * Source: https://github.com/myplanetdigital/ariadne

Requirements
------------

### Xcode

### [RVM][about-rvm]

[Installation instructions][install-rvm]

### [Bundler][about-bundler]

Bundler will be install automatically by RVM.

### [Librarian][about-lib]

### [Vagrant][about-vagrant]

### [Capistrano][about-cap]

Quick Start
-----------

    $ git clone https://github.com/myplanetdigital/ariadne.git
    $ sh -c "cd ariadne && git checkout `git describe --tags`" # Checkout most recent tag (stable)
    $ cd ariadne
    $ librarian-chef install             # Install cookbooks from Cheffile.lock
    $ vagrant up                         # Spin up VM
    $ cap deploy                         # Deploy application to VM

Files
-----

### `.rvmrc`

### `Gemfile`

### `Cheffile`

### `Vagrantfile`

### `Capfile`

   [about-rvm]:     <http://beginrescueend.com/>
   [about-bundler]: <http://gembundler.com/>
   [about-lib]:     <https://github.com/applicationsonline/librarian>
   [about-vagrant]: <http://vagrantup.com/>
   [about-cap]:     <https://github.com/capistrano/capistrano/wiki>
   [install-rvm]:   <http://beginrescueend.com/rvm/install/>
