## alg-names - Arrays of strings.

Written in Algol 68. 

Generates random names and stores them in an array.
 
Depending on size of the array it may be necessary to increase the heap size. 

On VAX/VMS compile and run using:
  
    $ algol names /heap=10000000
    $ link names
    $ run names
          1 Robert TAYLOR
          2 Mary WILSON
          3 Richard ROBERTS
          4 Elizabeth WHITE
          5 Susan JONES
          6 Particia WILLIAMS
            :
            :
            :
     174995 James GREEN
     174996 John WALKER
     174997 Elizabeth WILSON
     174998 Elizabeth EVANS
     174999 John ROBINSON
     175000 Karen JONES
    $
