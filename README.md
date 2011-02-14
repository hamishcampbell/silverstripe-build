# SilverStripe - Standard Build

This is a standard build of the SilverStripe web development
framework and Content Management System.

## Secure Files Build

This build is for testing and demonstration of the [Secure Files](https://github.com/hamishcampbell/silverstripe-securefiles)
module. It is currently based of the 2.4 branch of the SilverStripe
framework and CMS.

Secure Files adds file security controls to your websites `assets/` folder. See
the Secure Files documentation for more information.

## Installation

Note that the SilverStripe installer has not been included
in this project. To install SilverStripe:

  1. Checkout or copy the contents of this project your web root
  2. Add the appropriate environment configuration files (see [Environment Management](http://doc.silverstripe.org/sapphire/en/topics/environment-management))
  3. Edit your `mysite/_config.php` file with `$database` and other
relevant settings.
  4. If you have checked out the project with Git you will then need to run:
         git submodule update --init

## Usage Notes

This build contains git submodule links to SilverStripe Ltd's GitHub
repositories for Sapphie, CMS and the BlackCandy theme. Modules can
be updated to their latest revisions with Git with the following
process:

    cd sapphire
    git checkout master
    cd ..
    git commit -a -m "Updated sapphire module version"

If you've forked your own version of this repository you can then
push the change:

    git push

Or submit a pull request to have to entered into the parent project.

For more information on using Git submodules see http://book.git-scm.com/5_submodules.html.

## License

	Copyright (c) 2007-2011, SilverStripe Limited - www.silverstripe.com
	All rights reserved.

	Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

	    * Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
	    * Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the 
	      documentation and/or other materials provided with the distribution.
	    * Neither the name of SilverStripe nor the names of its contributors may be used to endorse or promote products derived from this software 
	      without specific prior written permission.

	THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE 
	IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE 
	LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE 
	GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, 
	STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY 
	OF SUCH DAMAGE.
