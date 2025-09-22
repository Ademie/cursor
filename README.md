# cursor
cursor rules
cursor rules

	1.	Use meaningful widget, variable, and method names
	2.	Keep widgets small and focused
	3.	Follow the Single Responsibility Principle (1 widget = 1 purpose)
	4.	Avoid deeply nested widgets — extract into sub-widgets
	5.	Separate UI, business logic, and data layers (e.g., MVVM, Clean Architecture)
	6.	Do not mix UI logic with state management logic
	7.	Use const constructors where possible for performance
	8.	Avoid rebuilding entire widget trees unnecessarily
	9.	Avoid magic numbers and strings — use constants or enums
	10.	Keep build methods lean — extract heavy logic
	11.	Use immutable models and state
	12.	Avoid setState for complex state — prefer Provider, Riverpod, Bloc, etc.
	13.	Never perform async logic inside build()
	14.	Dispose controllers and streams properly
	15.	Keep business logic out of widgets — use services or view models
	16.	Avoid tight coupling between widgets and logic
	17.	Use dependency injection for testability (e.g., get_it)
	18.	Format code using flutter format
	19.	Use meaningful error messages for exceptions
	20.	Write unit and widget tests for reusable components
	21.	Use named routes or strongly typed navigation, not hardcoded strings
	22.	Keep all assets, styles, and themes centralized
	23.	Use lint rules to enforce style and avoid anti-patterns
	24.	Use late final only when necessary and safe
	25.	Avoid global variables — use scoped state or injection
	26.    Don’t repeat yourself - no duplicate logic, always extract common behavior
	27.   Always capitalize on reusabel widgets, anytime you want to create a widget, check entire codebase if it exists and 	reuse 	it, if you need new parameters you’re free to pass them as optional parameters 
	28.  Maintain UI consistencies, always use themes to manage ui stylings, fonts, colors, etc
	29.   Always Use flutter_screen_util package for responsiveness and adaptability.
         30.    Always debug errors 
{
  "rules": [
    "Use meaningful and descriptive variable, class, and method names",
    "Split large widgets into smaller, reusable components",
	"use gorouter to manage routes, and never use the redirect feature, instead use if statements or ternary operations to manage redirections"
    "Use const constructors where possible for better performance",
    "Avoid deeply nested widget trees – extract UI into separate widgets",
    "Separate UI, state, business logic, and data layers (Clean Architecture)",
    "Do not perform async logic in the build() method",
    "Use state management (Provider, Riverpod, Bloc) instead of setState for complex flows",
    "Centralize app-wide constants, strings, themes, and colors",
    "Dispose of all controllers, streams, and subscriptions properly",
    "Avoid global variables – use scoped state or dependency injection (get_it)",
    "Avoid magic numbers and strings – define constants or enums",
    "Use immutable data models where possible",
    "Write unit, widget, and integration tests with proper coverage",
    "Enforce code formatting with flutter format or a formatter plugin",
    "Avoid side effects in pure widgets – push logic to view models/services",
    "Use typed routing or navigation wrappers to avoid hardcoded strings",
    "Catch and log errors with detailed messages – don’t silently fail",
    "Minimize rebuilds using keys, consts, and granular widget trees",
    "Respect the Single Responsibility Principle in classes and files",
    "Inject services and dependencies for easier testing and mocking",
    "Use Dart lint rules and static analysis to catch anti-patterns early",
    "Never block the main isolate – move heavy work to compute() or isolate",
    "Secure APIs and auth tokens – never hardcode keys or secrets",
    "Avoid tight coupling between modules – keep layers swappable",
    "Keep all APIs modular and well-documented for team integration"
  ]
}

Remember I’m building as a senior software mobile engineer with 15 years experience and my code needs to be top notched, performance, reliability, scalability, modularity, quality, security and ease of integration with other developers are very important
