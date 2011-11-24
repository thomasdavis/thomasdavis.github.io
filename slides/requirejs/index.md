# requirejs

!SLIDE

# A Title Slide

## me@example.com

!SLIDE

# Some sample code

``` javascript
require(
	{
		paths: {
			"cdn-jquery": "http://cdnjs.cloudflare.com/ajax/libs/jquery/1.6.2/jquery.min"
			"cdn-backbone": "http://cdnjs.cloudflare.com/ajax/libs/backbone.js/0.5.3/backbone-min",
			"cdn-underscore": "http://cdnjs.cloudflare.com/ajax/libs/underscore.js/1.1.7/underscore-min"
		}
		
	},
    [
        "require",
		"order!backbone",
		"text!2.tpl"


    ], 
    function (require, Backbone, templates ) {
		$("body").append(templates);
        require(["app"], function (app) {
                  var appview = new AppView();
              });
    }
);
```

!NOTES

 * a note

!SLIDE

# With a Background Image

}}} images/test.png