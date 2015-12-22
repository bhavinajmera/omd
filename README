

   Warning this is not a offical OMD Release
   
    OMD - the Open Monitoring Distribution
      <http://omdistro.org/>


OMD:- Based on OMD 1.30 <http://omdistro.org/> customized with Graphios.
Thanks to shawn-sterling for <https://github.com/shawn-sterling/graphios>.
Graphios is a script to emit nagios perfdata to various upstream metrics
processing and time-series (graphing) systems. It's currently compatible
with [graphite], [statsd], [Librato] and [InfluxDB]. Once need to install
backend and graphs seperately on other server, till the time I am 
integrating it with OMD.

What OMD contains
-----------------

OMD is no new Linux distribution. It is a collection of different software
packages round about Nagios:

  * nagios
  * NagVis
  * PNP4Nagios
  * Graphios
  * rrdtool including rrdcached
  * nagios-plugins
  * Check_MK
  * Check_MK Multisite
  * MK Livestatus
  * dokuwiki
  * NSCA
  * check_nrpe
  * Thruk
  * check_oracle_health
  * check_mysql_health
  * check_multi
  * check_webinject
  * Shinken (still experimental)
  * MOD Gearman
  * jmx4perl
  * others...

Installation
------------

* 1) git clone https://github.com/bhavinajmera/omd
* 2) cd omd
* 3) ./configure
* 4) make
* 5) make pack
* 6) cd /
* 7) tar -xvzf /path/to/omd/source/dir/omd-bin-1.30.tar.gz 
* 8) omd setup

RPM Build
---------
Use rpmbuild -tb on the tar.gz file to create a .rpm file

DEB build guide
---------------
After step 4 use command checkinstall to create a deb file

Configure Graphios
------------------
Please make necessary changes in 
/opt/omd/sites/sitename/etc/graphios/graphios.cfg 
to enable the backend and configure the backend settings.

