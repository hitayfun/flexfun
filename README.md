# Flexfun 

Flexfun is a simple,flex based and easy to use css framework.It currently supports Chrome, Firefox, Safari, Opera and IE 11+, also supports major phone devices( İOS Safari 7.1+, Android Browser 4.4+, Blackberry Browser 10+) too.

## Demo

<a href="http://btayfun.github.io/flexfun/">See Demo</a>

## Installation

- clone : `git clone https://github.com/btayfun/flexfun.git`
- Easy Download : [https://github.com/btayfun/flexfun/archive/master.zip](https://github.com/btayfun/flexfun/archive/master.zip "Easy Download")

## Getting Started 

### Steps

##### 1. Add the flex stylesheet link in the `head` element


    <link stylesheet="rel" href="css/flexfun.css">

##### 2. Add the ViewPort Tag

Don't use to add the viewport meta tag for mobil using.Place in the `head` element.

	<meta name="viewport" content="width=device-width, initial-scale=1">

##### 3. Structure your html layouts

###### Create a Container with `frame` classname

    <div class="frame">

	</div>

###### Create a column

	<div class="frame">
	
		<div class="column">

		</div>
	
	</div>

####### Create Column Number

    <div class="frame">

		for four columns

		<div class="column">
		
			<div class="col-4"></div>
			<div class="col-4"></div>
			<div class="col-4"></div>
			<div class="col-4"></div>

		</div>

		for one column

		<div class="column">
			
			<div class="col-1"></div>

		</div>

	</div>


> That's it.There is no float,no boring clearfix class and bla bla...

> And Free to use 
