# The responsive toggle object

Hides element and adds button to toggle visibility on small viewports.

See also: http://blog.lavoie.sl/2013/11/responsive-menu-in-pure-css.html , https://coderwall.com/p/sujd_w

Example HTML markup:

    <label for="toggle-responsive__checkbox" class="toggle-responsive__label" onclick>Toggle</label>

    <input type="checkbox" id="toggle-responsive__checkbox" />
    <div class="toggle-responsive__content">
        <p>Toggled content</p>
    </div>

Install using Bower:

    $ bower install --save inuit-toggle-responsive

Sass import:

    @import "bower_components/toggle-responsive/_objects.toggle-responsive.scss";
