# elastic-sort

An element that creates an ejs.Sort() object to pass onto elastic-client-search
based on user input.

Example:

    <elastic-sort input-string="Sort('_score').order('desc')"></elastic-sort>

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install
    
To run the demo, you will need a local elasticsearch instance and the mockads data referenced on elastic-client-search.

#### WCT Tips

`wct -l chrome` will only run tests in chrome.

`wct -p` will keep the browsers alive after test runs (refresh to re-run).

`wct test/some-file.html` will test only the files you specify.
