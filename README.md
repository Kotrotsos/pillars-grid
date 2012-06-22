pillars-grid
============

Pillars Grid is a CSS Grid system that is loosely based on natural divisions of a container/window. 

For four columns do:

        <div class="four columns">
            <div class="col">
                ...
            </div>
            <div class="col">
                ...
            </div>
            <div class="col">
                ...
            </div>
            <div class="col">
                ...
            </div>
        </div>

And for three columns you can do:

     <div class="three columns">
        <div class="col">
                ...
        </div>
        <div class="col">
                ...
        </div>
        <div class="col">
                ...
        </div>
    </div>
    
Etc.

Breakpoints uses natural divisions as well. The current big issue with this is that it is hard to divide something cleanly 
in thirds for instance (1/3 or 33.33333%) There will alway's be a remainder. 

