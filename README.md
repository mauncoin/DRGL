{Dragonglass} kills white walkers.


It is more valuable to us now.. than gold.

We need to find it-

We need to MINE it-

We need to MAKE weapons from it


The ONLY thing now that stands between us.. 
and the Army of the dead - 
Is one last and Final season..
        Season  8 
of   GAME OF THRONES.

It is @ that time when we shall start the trading of {DRAGONGLASS} with every man, woman, and child- whilst crowning only the most rightful heir of Exchange(s).. once our 8th and Final Season arrives.
_________________________________________________

As for now, every House shall be called upon to join in alliance. We must fight together- alongside one another, to defeat our common enemy.  
Any contributions to all future {Dragonglass} developments are not only welcomed, but encouraged. There is much, still, that remains to be done...For the Night is Dark, and Full of Terrors.

This process of mining , however..
begins...Now.
__________________________________________________________________

CPU/GPU only egalitarian proof-of-work algorithm.

~80% of all Dragonglass is set to be mined by FINAL season's debut.

( 8000008 )  max supply (Eight million eight*)   *actual total supply [8000008.8000008]
_________________________________________________


THERE  IS  ONLY  ONE  WAR  THAT  MATTERS..

The Great War.



And it is here.
________________________________________________________________________________________________________

{Dragonglass} is a next-generation anonymous cryptocurrency built upon Cryptonote technologies.
Read Cryptonote white paper at https://cryptonote.org/whitepaper.pdf



________________________________________________________________________________________________________________
_______________________________________________________________________________________________________________
## Building Dragonglass 

### On *nix

1. Dependencies: GCC 4.7.3 or later, CMake 2.8.6 or later, and Boost 1.55.

You may download them from:

* http://gcc.gnu.org/
* http://www.cmake.org/
* http://www.boost.org/



*** Alternatively, it may be possible to install them using a package manager by
executing the following command.     {Tested using Ubuntu 14.04}
 
 sudo apt-get install build-essential git cmake libboost1.55-all-dev
____________________________________________________________________

2. Clone {dragonglass} repository

*** Execute the following command to copy a desired repository

git clone https://github.com/ZirtysPerzys/dragonglass

______________________________________________________

3. Open folder with copied repository

*** Execute the following command to get into the directory with copied repository

cd dragonglass
______________________________________________________

4. Building (Compiling)

*** Execute the following command to compile

make -j4  

__________________________________________________
The resulting executables can be found in `build/release/src`.
________________________________________________

5. Starting {dragonglass} daemon
*** Execute the following command to navigate to resulting executables

cd dragonglass/build/release/src 



*** Start daemon, typing the following command-


  ./dragonglassd 


_______________________________________________
for a list of commands type  --help
_______________________________________________



After you are have very success!!!!

Next see {DragonglassWallet} 

https://github.com/ZirtysPerzys/Dragonglasswallet


______________________________________________________________________________________________________
**Advanced options:**

* Parallel build: run `make -j<number of threads>` instead of `make`.
* Debug build: run `make build-debug`.
* Test suite: run `make test-release` to run tests in addition to building. Running `make test-debug` will do the same to the debug version.
* Building with Clang: it may be possible to use Clang instead of GCC, but this may not work everywhere. To build, run `export CC=clang CXX=clang++` before running `make`.




### On Windows
Dependencies: MSVC 2013 or later, CMake 2.8.6 or later, and Boost 1.55. You may download them from:

* http://www.microsoft.com/
* http://www.cmake.org/
* http://www.boost.org/

To build, change to a directory where this file is located, and run these commands: 
```
mkdir build
cd build
cmake -G "Visual Studio 12 Win64" ..
```

And then do Build.
Good luck!
