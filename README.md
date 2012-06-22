
pillars-grid. 
Inspired by the fantastic work that David Bushell http://dbushell.com/ did on Shiro http://dbushell.com/shiro/
============

Pillars Grid is a Responsive CSS Grid system that is loosely based on natural divisions of a container/window. 

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

For a customized column layout. You can also use the more commonplace one-of-three type of notation.

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

You can use both 

        <div class="col one-of-three">
    
Or the more verbose

        <div class="column one-of-three">
    
It works the same.

