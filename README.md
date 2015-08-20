Portfolio
=========

Directory Structure
-------------------

/src holds the raw haml and scss
/site holds the generated html and css


Setting Stylesheet Order
------------------------

In the layout:

<pre>
  = stylesheet :first_stylesheet, :second_stylesheet
</pre>

Preview
-------

<pre>
  cd portfolio
  bundle exec staticmatic preview files
</pre>

Publish
-------
<pre>
  cd portfolio
  bundle exec staticmatic build files && \
  scp -r files/site/index.html files/site/stylesheets $jj:webapps/portfolio/. && \
  scp ~/r/resumes/jackdesert.pdf $jj:webapps/portfolio/.
</pre>

