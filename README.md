# Phusion Passenger: a fast and robust web server and application server for Ruby, Python and Node.js

[Phusion Passenger™](https://www.phusionpassenger.com/) is a web server and application server, designed to be fast, robust and lightweight. It takes a lot of complexity out of deploying web apps, adds powerful enterprise-grade features that are useful in production, and makes administration much easier and less complex. Phusion Passenger supports Ruby, Python, Node.js and Meteor, and is being used by high-profile companies such as **Apple, Pixar, New York Times, AirBnB, Juniper** etc as well as [over 350.000 websites](http://trends.builtwith.com/Web-Server/Phusion-Passenger).

What makes it so fast and reliable is its **C++** core, its **zero-copy** architecture, its **watchdog** system and its **hybrid** evented, multi-threaded and multi-process design.

**Learn more:** [Website](https://www.phusionpassenger.com/) | [Documentation](https://www.phusionpassenger.com/documentation_and_support) | [Support resources](https://www.phusionpassenger.com/documentation_and_support) | [Github](https://github.com/phusion/passenger) | [Twitter](https://twitter.com/phusion_nl) | [Blog](http://blog.phusion.nl/)

<center><img src="http://blog.phusion.nl/wp-content/uploads/2012/07/Passenger_chair_256x256.jpg" width="160" height="160" alt="Phusion Passenger"></center>

## Installation

Please follow [the installation instructions on the website](https://www.phusionpassenger.com/download).

### Installing the source directly from git

If you mean to install the latest version of Passenger directly from this git repository, then you should run one of the following commands. Installing from the git repository is basically the same as the tarball installation method, as [described in the manual](http://modrails.com/documentation/Users%20guide.html#installation).

    ./bin/passenger-install-apache2-module

-OR-

    ./bin/passenger-install-nginx-module

-OR-

    # From your application directory
    ~/path-to-passenger/bin/passenger start

For troubleshooting, configuration and tips, please also refer to the above documentation. For further support, please refer to [the Phusion Passenger support page](https://www.phusionpassenger.com/support).

Ruby users can also build a gem from the Git repository and install the gem.

    gem build passenger.gemspec
    gem install passenger-x.x.x.gem

## Further reading

 * The `doc/` directory.
 * CONTRIBUTING.md.
 * https://www.phusionpassenger.com/support

## Legal

Phusion Passenger is a trademark of Hongli Lai & Ninh Bui.
