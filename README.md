# Introduction

A simple app that converts a number to written text.
The text represents an amount. Negative amounts are not honoured.

## Getting Started

Go to https://benbos67.github.io and enter a number; click [convert]

That's it.

## Explanation

Yes. I did read the documentation - and I had a thought:
Use the tool for the job. Flutter shines in this scenario - it is easy to build and deploy,
and development is lightning fast.
Dart code is remarkably similar to both Java and C# so it's easy to port. And using Flutter/Dart, 
I do not need a RESTful interface to communicate with a backend that needs to be built and deployed separately.

Plus, doesn't it look nice?

## Tests

There are some tests in the /test directory. The input via the front end is sanitised using a regex filter - 
the number_to_text.dart file has its own validations which are kept simple.
