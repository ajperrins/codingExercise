# Coding Exercise


|Requirements        |             |
|--------------------|-------------|
|Language            |C#           |
|Expected duration   |1 to 2 hours |

## Spec

For this exercise, you will use the REST API defined at [swapi.co](http://swapi.co/)

Implement a console application which takes the following command line arguments, in order:

1. A film title, enclosed in double-quotes
2. A property name on the [film entity](http://swapi.co/documentation#films) which represents a collection of other entities. For example, a film has a property named "characters" which is a JSON array with references to the set of [people](http://swapi.co/documentation#people) that appear in the film. The value for this second command line argument will be one of the following: "characters", "planets", "starships", "vehicles", "species".
3. A property name, which will exist on the entity identified in number 2 above, and that propety will be a string property, not an array.

For the film identified in the first argument, your application should retrieve all related entities in the collection identified by the second argument, and write the values of the property identified in the third argument to the console. The order of the output does not matter.

For example, the command line invocation and output below yields a correct result:

```
C:\> MyApp.exe "Return of the Jedi" starships name
Millennium Falcon
Y-wing
X-wing
Executor
Imperial shuttle
EF76 Nebulon-B escort frigate
Calamari Cruiser
A-wing
B-wing
Star Destroyer
Rebel transport
CR90 corvette
```

## Priorities and constraints

This is an open-ended exercise; you can use nuget packages, google, and any version of the compiler or framework. Feel free to demonstrate your knowledge of compiler technology or libraries that might simplify your code, improve performance, provide for extensibility, etc.

If you spend much more than two hours on the exercise, then be careful that you are not providing a solution that is more complex than the problem calls for.

Make your priorities the following:

* Clean, comprehensible code
* Performance (consider asynchrony)
* Demonstrate your experience by providing professional quality work and leveraging of skills or tools that are well suited to the problem

If you have any questions about this problem, feel free to ask by email.

## Submission
Preferably, post your solution on a public repository like Github or Bitbucket.

Alternatively, post an archive or zip of your solution on the web or ftp (you can use a public dropbox/box URL, or your personal web-site, etc), and email us with the location.

If you cannot do either of these, let us know, and we will set up a web location for you to upload an archive of your code.