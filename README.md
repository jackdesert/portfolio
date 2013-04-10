Portfolio
=========

Directory Structure
-------------------

/src holds the raw haml and scss
/site holds the generated html and css

Preview
-------

<pre>
  cd portfolio
  bundle exec staticmatic preview files
</pre>

Build
-----

<pre>
  cd portfolio
  bundle exec staticmatic build files
</pre>

Setting Stylesheet Order
------------------------

In the layout:

<pre>
  = stylesheet :first_stylesheet, :second_stylesheet
</pre>
