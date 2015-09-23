############################
Font Factory
############################

This repo contains various of collective font faces used by web applications. Use one or couple of them, just include the css files 
which are compiled by scss.

Fonts including:

- `Montserrat`_
- `Open Sans`_

.. _`Montserrat`: montserrat
.. _`Open Sans`: open-sans


*******************************
Compiling scss files to css
*******************************

Prequisition: we need ruby, gem and sass before compiling scss files.

::

    $ ruby -v
    $ gem -v
    $ sudo gem install sass

Compiling scss files to css

::

    $ ./compile.sh

After compiling, you can check the css files in the specific font folders.

******************************
Usage
******************************

For the usage, you can include the supplied css files in your html or css file.

HTML

::

    <link rel="stylesheet" type="text/css" href="https://raw.githubusercontent.com/KellyChan/font-factory/master/open-sans/open-sans.css">

CSS

::

    @import url("https://raw.githubusercontent.com/KellyChan/font-factory/master//open-sans/open-sans.css");

******************************
Configuration
******************************
 
**_config.scss**: update the **$fontRoot**, and then run **./compile.sh**.


******************************
LICENSE
******************************

- `LICENSE`_

.. _`LICENSE`: LICENSE.rst


