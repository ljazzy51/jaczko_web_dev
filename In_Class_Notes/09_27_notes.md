# 09/27/2023 In Class Notes

    - Using responsive sizing and media quereys you can view the same page well on any size screen
    - Flex containers can be used in this to justify content either with space around or between 
        - 4 wide on desktop 
        - 2 wide on tablet 
        - 1 wide on phone
    - Doing desktop styling is doing the default styling for desktop and we override for smaller screens 
    - In row mode justify content is horizontal and align items is vertical alignment 
    - There should only be one h1 per page 
    - Telling the anchor tags of the nav to display block gives you a larger clickable area. Text by default only wants to take up as much space as it is and telling it to display block makes it take up as much space as it can 
    - When you want things to start stacking you want to specify a default width 

    /* smartphones, iPhone, portrait 480x320 phones */ 
	    @media (min-width:320px) { 

	    }
    /*portrait e-readers (Nook/Kindle), smaller tablets @ 600 or @ 640 wide. */
        @media (min-width:481px) {  

        }
    /* portrait tablets, portrait iPad, landscape e-readers, landscape 800x480 or 854x480 phones */
        
        @media (min-width:641px) { 

        }
    /* tablet, landscape iPad, lo-res laptops ands desktops */
        
        @media (min-width:961px) { 

        }
    /* big landscape tablets, laptops, and desktops */
        
        @media (min-width:1025px) {  

        }
    /* hi-res laptops and desktops */
        
        @media (min-width:1281px) {

        }
    
    - Flex grow is the ability to grow if necessary (0 is no 1 is yes)
    - Flex shrink is the ability to shrink if necessary 
    - MIDTERMS SHOULD BE RESPONSIVE FOR THE FINAL PROJECT 
        - DO A MIN WIDTH media query thats above the standard desktop size for the overrides so that it displays on the 4k tv in class properly 