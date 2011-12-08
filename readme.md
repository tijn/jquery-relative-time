jQuery Relative Date
====================

A jQuery plugin adapted from DHH's relative date helper for JS.
I got tired of this not being a jQuery plugin, so here it is.

Usage:
------
    
    <ul>
        <li><a href="#">Item 1</a> <span class="timestamp">12/05/2010 05:06:47</span></li>
        <li><a href="#">Item 2</a> <span class="timestamp">12/04/2010 00:16:38</span></li>
        <li><a href="#">Item 3</a> <span class="timestamp">12/02/2010 07:37:29</span></li>
    </ul>
    ...
    $('.timestamp').relativeTime();


    <article class='relative_times'>
         <time datetime="0">Unix epoch</time>
         <time>2011-12-08</time>
    </article>


    $(".relative_times time, time.relative").relativeTime();
