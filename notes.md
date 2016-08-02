Chapter 1: The Basics of AngularJS
	How Web pages get to your browser:
		The internet is like a post office, sorting incoming mail and sending it out to the correct destination. 
		Routers are like an address, then IP address to seperate apartments, and THEN an inidividual, unique "internal IP address" acts like a person. Unique name, unique destination.
		There are two types of IP address:
			ipv4
				contain 4 divisions of numbers about 10 numbers total, seperated by periods
			ipv6
				contains way more than 9, sperates numbers with colons
	Browsers:
		examples: Chrome, Safari, Firefox, Explorer
		Gets HTML and parses it into a structure
	AngularJS
		official:
			Client side tech written in JavaScript. Works with the tech of the web to develope faster and easier than before
		framework for single-page web apps
	licsensed through GitHub
Chapter 2: Data Binding and Your first AngularJS Web App
	Hello WOrld:
		a simple app to build rudimentary Angular data binding
	Data binding - Angular, rather than old methods of merging data into a template and replace a DOM, creates a live template taht changes in real time
	Model View Controller (MVC): controller doesn't worry about bein in the mix of rendering, makes testing simple and enjoyable
	Seperated Presentation: Disvisiion between objects in the web app. Seperation of powers
	Dirty checking - efficient approch to checking for changes on a model - angular does a check inside its event loop




Chapter 3 Modules
	Module: efficient, production ready controllers that encapuslate functionality in a single core unit 
	Module is main way to define in angular
	Advantages:
		Keeps global namespace clean
		Makes tests easier to write and keep clean
		Easy to share code between apps
		allows app to load different parts in any order
		uses: angular.module() API method
		Properties: 
			Name: string, gives name of module
			requires: array of strings, list of modules as strings that the injector loads before module itself 
