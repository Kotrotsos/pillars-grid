Pillars Grid 
============

Inspired by the fantastic work that David Bushell did on Shiro. http://dbushell.com/ | http://dbushell.com/shiro/

Pillars Grid is a Responsive CSS Grid system that is loosely based on natural divisions of a container/window. 

For a live example: http://dabblet.com/gist/2972031

Please note: Currently working out the kinks, there are alot of cases where the grid will break- or loose ends (like the rounding issues)

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

However- for a customized column layout. You can also use the more commonplace one-of-three type of notation.

        <div class="row">
            <div class="col one-of-three">
                ...
            </div>
            <div class="col one-of-three">
                ...
            </div>
            <div class="col one-of-three">
                ...
            </div>
        </div>
        
Or

        <div class="row">
            <div class="col one-of-three">
                ...
            </div>
            <div class="col two-of-three">
                ...
            </div>
        </div>

You can use both 

        <div class="col one-of-three">
    
Or the more verbose

        <div class="column one-of-three">
    
It works the same.

