:title: Développement Android avancé
:data-transition-duration: 1250
:author: Frédéric CHAMP
:description: test
:keywords: presentation
:css: css/presentation.css
:skip-help: true

.. role:: bordeaux

----

:id: first_slide

|
|
|
|
|

Hovecraft presantation test
========================================

Testing and demo
-------------------------

**Frederic CHAMP**

----

:data-x: r2000

.. role:: align-center 

Are you ready ?

Let's make some test :)
========================================

----

:data-x: r2000

Slide styles
========================================

The difference with a classic presentation that's you can have different :bordeaux:`slide styles` ...

----

:data-x: r2000

:id: circle-no-background

|
|
|
|
|

Look that !
========================================

A :bordeaux:`circle` shape :)
-----------------------------

----

:data-x: r2000

:id: circle-background

|
|
|
|
|

Look again !
========================================

A :bordeaux:`circle` shape with :bordeaux:`background` :)
---------------------------------------------------------

----

:data-rotate-y: 90
:data-x: r2000

You don't like cirlce slide ? :(

Ok, I have something for you... :)
========================================

----

:data-y: r2000

:id: square-no-background

|
|
|

Do you like this ?

A :bordeaux:`square` shaped slide ;)
========================================


----

:data-y: r2000

:id: square-background

|
|
|

Or maybe you prefer this:

A :bordeaux:`square` slide with :bordeaux:`background` ;)
=========================================================

----

:data-rotate-x: 90
:data-y: r2000

Ready for the next step ?

Let's add some pretty stuffs :)
========================================

----

:data-y: r2000

CSS shapes
========================================

You can include some :bordeaux:`CSS shapes` ...

----

:data-y: r2000

Look at those...

Simple tiny :bordeaux:`shapes` !
========================================

.. raw:: html

    A triangle pointing down:
    <span class="delta_down"></span><br>
    A triangle pointing up:
    <span class="delta_up"></span><br>
    A triangle right up:
    <span class="delta_right"></span><br>
    A  Circle:
    <span class="circle"></span><br>

----

:data-y: r2000

Let's see the trick...

CSS code example:
========================================

.. code:: CSS

    span.circle {
         border-radius: 50%;
         width: 20px;
         height: 20px;
         display: inline-block;
         background-color: #a4a4a4;
         position: relative;
         top: 2px;
    }

Html code in the rst file
========================================

.. code:: html

    A triangle pointing down:
    <span class="delta_down"></span><br>
    A triangle pointing up:
    <span class="delta_up"></span><br>
    A triangle right up:
    <span class="delta_right"></span><br>
    A  Circle:
    <span class="circle"></span><br>

