## Day1.
**OBJECT-ORIENTED JAVASCRIPT**
- Introductory
- Introduction to Object-Oriented JavaScript
- Object-oriented programming
- Prototype-based programming
- JavaScript object oriented programming
- The class
- The object (class instance)
- The constructor
- The property (object attribute)
- The methods
- Inheritance and the prototype chain
- Encapsulation
- Abstraction
- Polymorphism
- Closures
- Strict mode

**NEW FEATURES IN ES6 (ES 2015)**
- Arrow Operator
- Classes
- Enhanced object literals
- Template strings
- Destructuring
- Default, rest and spread
- Let and const 
- Iterators and for..of
- Generators
- Modules
- Module loaders
- Map + set + weakmap + weakset
- Proxies
- Symbols
- Promises

## DAY-2
**INTRODUCTION TO TYPESCRIPT**
- Why use TypeScript?
- TypeScript Features
- TypeScript Syntax, Keywords, and Code Hierarchy
- Tooling and Framework Options
- Tooling and Framework Options - TypeScript Playground
- Tooling and Framework Options - Visual Studio
- Tooling and Framework Options - Web Essentials
- Tooling and Framework Options - Sublime Text
- Tooling and Framework Options - TypeScript Compiler
- Tooling and Framework Options - NodeJS
- Hello World Example
- Hello World Example - Creating a Class

**TYPING, VARIABLES, AND FUNCTIONS**
- Overview
- Grammar, Declarations, and Annotations
- Type Inference
- Grammar
- Static and Dynamic Typing
- Compile Time or Run Time
- Ambient Declarations and Type Definition Files
- The Any Type and Primitives
- Applying Types
- Objects
- Functions
- Arrow Functions and Debugging
- Functions and Interfaces
- Static Typing Recap
- Optional and Default Parameters
- Rest Parameters
- Demo: Defining Parameters
- Function Overloads
- Demo: Using Function Overloads

**CLASSES AND INTERFACES**
- Introduction
- Defining Classes
- Demo: Defining Classes
- Demo: Property Limitations
- Casting and Type Definition Files
- Demo: Casting and Type Definition Files
- Extending Types
- Demo: Extending Types
- Using Interfaces
- Demo: Using Interfaces
- Extending an Interface
- Demo: Extending an Interface

**MODULES**
- Overview
- Identifying a Module
- Creating an Internal Module
- Internal Module Accessibility and IIFE
- Named Modules
- Extending Modules and Importing Shortcuts
- Organizing Internal Modules
- Separating Internal Modules
- External Modules and Dependency Resolution
- Module Dependencies
- Importing External Modules Using AMD
- Importing 3rd Party Libraries Using AMD

**GENERICS**
- Introduction and Overview
- What are Generics and Type Parameters?
- Using Array
- Generic Functions
- Demo: Creating and Using Generic Functions
- Generic Interfaces and Classes
- Demo: Creating and Using a Generic Class
- Generic Constraints
- Demo: Applying Constraints to Generics

**COMPILER OPTIONS AND PROJECT CONFIGURATION**
- Introduction and Overview
- Specifying Compiler Options
- Demo: Using Compiler Options
- Role and Structure of tsconfig.json
- Demo: Managing a Project with tsconfig.json

**TYPE DEFINITIONS**
- Introduction and Overview
- What Are Type Definition Files?
- Ambient Modules
- DefinitelyTyped
- Demo: Using Definitions from DefinitelyTyped
- Managing Type Definitions with tsd
- Demo: Installing Type Definitions with tsd
- Managing Type Definitions with typings
- Demo: Installing Type Definitions with typings

**OTHER ARTIFACTS (OTHER CONCEPTS THAT ARE REQUIRED BEFORE CREATEION OF ANGUALR APPLICATION)**
- Babel compiler
- Module loader (ts-loader etc.)
- Light weight servers (lite-server, webpack-dev-server etc.)
- Bundlers (webpack etc.)

## DAY-3
**INTRODUCTION TO ANGULAR 6**
- Introduction
- Anatomy of an Angular 6 Application
- High-Level architectural Overview of Angular 6
- Code Simplification
- Performance Improvements
- Sample Application

**SETUP ENVIRONMENT AND PACKAGE REQUIREMENT, INSTALLTION ETC**
- Introduction
- Selecting a Language
- Selecting an Editor
- Setting up Our Environment
- Setting up an Angular 4 Application
- Running an Angular 4 Application
- About Modules
- Loading Modules and Hosting our Application

**INTRODDUCTION TO COMPONENT**
- Introduction
- What Is a Component?
- Creating the Component Class
- Defining the Metadata with a Decorator
- Importing What We Need
- Demo: Creating the App Component
- Bootstrapping the App Component
- Demo: Bootstrapping the App Component

**TEMPLATES, INTERPOLATION AND DIRECTIVES**
- Introduction
- Building a Template
- Building the Component
- Using a Component as a Directive
- Binding with Interpolation
- Adding Logic with Directives: ngIf
- Adding Logic with Directives: ngFor

## DAY-4
**DATA BINDING AND PIPES**
- Introduction
- Property Binding
- Handling Events with Event Binding
- Handling Input with Two-way Binding
- Transforming Data with Pipes

**MORE ON COMPONENTS**
- Introduction
- Defining Interfaces
- Encapsulating Component Styles
- Using Lifecycle Hooks
- Building Custom Pipes

**BUILDING NESTED COMPONENTS**
- Introduction
- Building a Nested Component
- Using a Nested Component
- Passing Data to a Nested Component Using @Input
- Passing Data from a Component Using @Output
- Child components
- Using @ViewChild()

**SERVICES AND DEPENDENCY INJECTION**
- Introduction
- How Does It Work?
- Building a Service
- Registering the Service
- Injecting the Service
- @Host, @Optional and @Self decorator functions

**RETRIEVING DATA USING HTTP**
- Introduction
- Observables and Reactive Extensions
- Setting Up
- Sending an Http Request using HttpClient in angular 5
- RxJS
- Subscribing to an Observable
- Pipe() method, map functionality

## DAY-5
**NAVIGATION AND ROUTING**
- Introduction
- Setting Up
- Configuring Routes
- Tying Routes to Actions
- Placing the Views
- Passing Parameters to a Route
- Activating a Route with Code
- Params, ActivatedRoute, ParamMap, Router service
- Router-outlet, routerLink
- Navigation using Router services navigate() method

**WORKING WITH FORMS**
- Angular Forms API
- Form Controls, Control groups
- FormBuilder
- Form Directives
- Forms Validation
- Programmatic Approach
- Custom Validators
- Custom Validation Directives
- Template-Driven Forms
- Model-Driven Forms

| ANGULAR V4 | ANGULAR V5 | ANGULAR V6 |
|--|--|--|
|Animations|HttpClient, HttpResponse etc. (Http of Angular 4 deprecated)|Ng-add, ng-update (CLI changes)|
|ngIf-else, ngStyle and ngClass|Support for Multiple Export Alias|Declaring the providers inside the service itself|
|Dynamic components|Internationalized Number, Date, and Currency Pipes|Using ng-template instead of template directive|
|Typescript support|Improved Decorator Support|Angular elements|
|Angular Universal|Build Optimization|Upgrading to RxJS 6.0.0|
|Flat ES modules|Faster Compilation||
|New View Engine|Angular Universal Transfer API||
||Forms Validation in Angular 5||
||New Router Lifecycle Events in Angular 5||
||Animations in Angular 5||
||Deprecations and Other Updates||


**TESTING ANGULAR APPLICATIONS**
- Unit Testing – Jasmine & Karma
- Test a Class
- Test a Component
- Test a Pipe
