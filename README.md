 
##########################################################

FluidPhp 1 open source project user agent helper

A powerfull framework based on the phptoolcase library.

##########################################################

FluidPhp is a framework based on the PhpToolCase library.

Visit phptoolcase.com for complete guides and examples.

== PROJECT INFO ===================================

== Project Home: http://phptoolcase.com

== Requirements: php version 5.3+

== INSTALLATION WITH COMPOSER ========================
	
	Add the following to your composer.json file:
	
	- WITH FLUIDPHP FRAMEWORK:

		"require": 
		{
			"mnsami/composer-custom-directory-installer": "1.0.*" ,
			"fluidphp/useragent-helper": "~1.0"
		} ,
		"extra": 
		{
			"installer-paths": 
			{
				"./vendor/fluidphp/helpers/UserAgent": ["fluidphp/useragent-helper"]
			}
		}
	
	- STAND-ALONE:
		
		"require": 
		{
			"fluidphp/useragent-helper": "~1.0"
		}