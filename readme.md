todo-lg
=======

Run
---

open ./index.html into a browser

Test
----

The below command has no real tests, mainly comments for implementations to be.

	$ protractor ut.js

To view the expected tests to be actioned @see {{unit-tests/index.spec.js}}

Method
------

Google'd for the type of implementation I wanted and found [todomvc.com|http://todomvc.com/architecture-examples/angularjs/], it did more than expected and fulfilled the brief.
Snag: there was no unit testing implemented into the originating code.

Implement custom tests using the {{protractor}} implementation, allowing an end to end test suit covering functionality.

Allocate grunt to minify JS for production use.

cons
----

Functionality consistency when deployed into a parent ecosystem are unknown.
Styling will be required for conversion into Sass.

pros
----

Speedy resolution for what was needed.
Detection of bugs assured when porting unit tests.

Outstanding
-----------

Implementation of Sass and the required build scripts, tasked through grunt allowing polling of file changes to trigger a compile.
