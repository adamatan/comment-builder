# Comment builder

## Simple

    $ comment "Builds nice comments"
    ############################# Builds nice comments #############################

## Java  
  
    $ comment --java "Nice Java comments"
    /***************************** Nice Java comments *****************************/
    
## XML
    
    $ comment --xml "Nice XML comments"
    <!--                           Nice XML comments                             -->

## Variable width
    
    $ comment --xml "And narrow comments, too" 30
    <!-- And narrow comments, too -->
    $ comment "Or very very very very very very very very very looooooooong comments" 100
    ############## Or very very very very very very very very very looooooooong comments ###############
