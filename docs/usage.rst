========
Usage
========

Kerberos is an authentication protocol using a combination of secret-key cryptography and trusted third parties to allow secure authentication to network services over untrusted networks.  

Our super software modify all of this and changes the concept of kerberos completly, it's nothing like kerberos anymore ¯\\_(ツ)_/¯  

Generate a ticket::

   $ kapt init

Delete a ticket::

   $ kapt destroy
   
List ticket::

   $ kapt list

Generate a ticket as an other user::

   $ kapt init -u [user]

Generate a ticket for an other location::

   $ kapt init -l "floor/row/place"
   (example for e2r5p1: $ kapt init -l "2/5/1")

Generate a ticket without prompt::

   $ kapt init -p user:pass

|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
magick, 698x100+0+115 is usually good :D  
  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  
|  




Rules and info for a valid ticket::

   The sum of all the numbers modulo 7 must be equal to 0  
   The 9th, 5th and 13th must be numeric  
   Character E and S must be present in the ticket  
   Character V and A must not be present   
