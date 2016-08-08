---------------------------------------------
    Sample Java ME client for twitter.com
---------------------------------------------

1. Introduction

   This project contains a sample client for twitter.com. It uses the public
   twitter API. This is an example of how a Web 2.0 RESTful web service
   could be invoked from Java ME.
      
   For more information please see:
     https://meapplicationdevelopers.dev.java.net/mobileajax.html

2. Required APIs

   JSR 30 - Connected Limited Device Configuration (CLDC) 1.0
   JSR 37 - Mobile Information Device Profile (MIDP) 1.0

3. Tools

   The project can be built easily using the following tools -

   1. Java SE version 6.0 or higher
   2. NetBeans IDE 5.5.1 or higher
   3. NetBeans Mobility Pack 5.5.1 for CLDC or higher

4. Setup

   1. Launch NetBeans.

   2. Open the project in NetBeans.

   3. Resolve dependencies, if necessary. If the project name is in red,
      resolution is needed. Right-click on the project name and select
      Resolve Reference Problems (towards the bottom of the menu).

      Resolve the location of the request project. Click Resolve,
      navigate to the request project directory and select it. This
      should fix the reference problem.

      Resolve the location of builtin.ks, if necessary. Click Resolve,
      navigate to the NetBeans user directory and select Open. This
      directory is usually $HOME/.netbeans on Solaris and Linux and
      something like C:\Documents and Settings\<user>\.netbeans on
      Windows. This should fix the reference problem.

   4. Right-click on the project and select Build All Project
      Configurations.
