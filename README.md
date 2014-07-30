# The responsive toggle object

Hides an element and adds a button to toggle visibility for small viewport widths.
Original idea see: http://blog.lavoie.sl/2013/11/responsive-menu-in-pure-css.html

Example HTML markup:

    <label for="toggle-responsive__checkbox" class="toggle-responsive__label" onclick>Toggle</label>

    <input type="checkbox" id="toggle-responsive__checkbox" />
    <div class="toggle-responsive__content">
        <p>Toggled content</p>
    </div>

Install using Bower:

    $ bower install --save inuit-toggle-responsive

Import in Sass file:

    @import "bower_components/toggle-responsive/_objects.toggle-responsive.scss";
