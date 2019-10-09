# Todo

Test drive a program that keeps a list of todos.

As soon as a new test is passing, `git commit`.

## User stories

```
* As a user
* So that I can keep track of what to do
* I want to create a todo with a description
```
```
* As a user
* So that I can organize my tasks into different categories
* I want to add a todo to a specific list
```
```
* As a user
* So that I can see what to do
* I want to print my todo list
```

It should:
* Have two classes:
 * `Todo`
   * which has two methods:
     * `initialize`: Creates a new todo object. Takes one parameter, a description (string), and stores it on the todo object.
     * `description`: Takes no parameters. Returns the description that was
       stored when the todo was created.
 * `TodoList`
   * which has three methods:
     * `initialize`: Creates a new todo list object. Takes no parameters.
     * `add`: Takes a todo object as a parameter. Stores it on the
       todo list object.
     * `print`: Takes no parameters. Creates a string of all the
       stored todos, one per line. Each line should start with a bullet `* `.
       * e.g.
         ```
         * get milk
         * get the papers
         * pat the dog
         ```