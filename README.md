lightworks-arch - [UNMAINTENED]
===============

Lightworks arch PKGBUILD

How to
======

Clone this repo
  
    $ git clone git://github.com/bhush9/lightworks-arch.git

Download lightworks package from [here](http://www.lwks.com/index.php?option=com_docman&gid=19&task=cat_view&Itemid=199) and put it inside lightworks-arch/lightworks folder.

Change directory to lightworks
  
    $ cd lightworks-arch/lightworks
    
Make package using makepkg command.

    $ makepkg
    
Install newly created package.

    $ sudo pacman -U *.pkg.tar.xz
    
TO DO
=====

1. Examine dependancy and update PKGBUILD
2. Upload this to AUR (Am I lazy?)
