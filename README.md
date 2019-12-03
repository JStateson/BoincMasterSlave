# Status
WARNING - USE THIS PROGRAM AT YOUR OWN RISK.  If you use the bunkering feature be aware that you must only crunch the project you want to bunker and no others.  Questions to josephy@stateson.net.  
The sources here are based on 7.14.2 with changes to implement the following features

Usage: boinc [options]

    --set_hostname <name>          use this as hostname
    
    --set_password <password>      rpc gui password
    
    --set_backoff N                set backoff to this value
    
    --spoof_gpus N                 fake number of gpus
    
    --set_bunker_cnt <project> N   bunker this many workunits for given project then quit
    
    --mw_bug_fix                   delay attaching output to allow new work to download (Milkyway only)

This project is named master - slave as the intent is to use the project information at \ProjectData\Boinc (or /var/lib/boinc) as
a master and make copies of it using an incrementing hostname, same password, and incrementing RPC port to create and run multiple
clients.  This is useful if a project goes offline and spoofing the number of GPUs does not provide an adaquate number of work units
to continue crunching during the outage.  The scripts, bash and cmd, to perform this function are under construction.
 

[![Build Status](https://travis-ci.org/BOINC/boinc.svg?branch=master)](https://travis-ci.org/BOINC/boinc) [![Build status](https://ci.appveyor.com/api/projects/status/9dgoc9h5ppos8vcy/branch/master?svg=true)](https://ci.appveyor.com/project/BOINC/boinc/branch/master) [![Coverity Scan Build Status](https://scan.coverity.com/projects/4226/badge.svg)](https://scan.coverity.com/projects/boinc-boinc) [![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/BOINC/boinc/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/BOINC/boinc/?branch=master)

# BOINC

Project Website: https://boinc.berkeley.edu

## Want to create a project
See: https://boinc.berkeley.edu/trac/wiki

## Want to help translate
See: https://boinc.berkeley.edu/trac/wiki/TranslateIntro

## Want to contribute
See: https://boinc.berkeley.edu/trac/wiki/SoftwareDevelopment

### Note

The University of California holds the copyright on all BOINC source code. By 
submitting contributions to the BOINC code, you irrevocably assign all right, 
title, and interest, including copyright and all copyright rights, in such 
contributions to The Regents of the University of California, who may then 
use the code for any purpose that it desires. 

# License
BOINC is free software; you can redistribute it and/or modify it
under the terms of the GNU Lesser General Public License
as published by the Free Software Foundation,
either version 3 of the License, or (at your option) any later version.

BOINC is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
See the GNU Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public License
along with BOINC.  If not, see <https://www.gnu.org/licenses/>.
