TiAlloy-TDD
===========

Titanium Alloy Jasmine Unit Test Widget

## TiTDD 

A TDD Alloy Widget for Appcelerator Titanium that is based on Jasmine 1.3.1 . 

## Info

- This is a complete Alloy Test Application. The only thing you need to do is to add your test specs to the project and then indicate in the widget which specs you want to execute.
  
- The spec files must be added/created in the project app/lib dir under the spec directory. The example specs that come with Jasmine 1.3.1 are already in the project and set up ready to run.
  
- To specify which specs to use just add them to the widget xml in the spec attribute. This is just a comma separated list of specs

```
<Widget src=“limited.spiralarmconsulting.jut" spec="PlayerSpec,SpecHelper"/>  
```
		
 Just see the main project index.xml for an example.
 
 
## Notes

- This is a test project that I created after looking at Bill Dawson's TiJasmine module and using it to understand more about Jasmine and how it could be used in a TiAlloy app.
  The result is this project that I hope may be of use to others. 

 - Basic documentation for this project is now auto generated  and place in the project root **docs** directory.

## Updates

- 27 Aug 2013 - added  a CommonJS module that simulates a simple vending machine along with a test Spec for the module
- 8 Aug 2014 - widget re-written using name spacing. Updated the Reporter and Logger. Added [sa.duckandcover](https://github.com/magnatronus/sa.duckandcover) to generate basic project documentation


## Credits

- Based on the TiJamine module code by Bill Dawson.


## [Licence](http://creativecommons.org/licenses/by-nc/3.0/)