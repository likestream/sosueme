sosueme (pronounced "So sue me!") is a collection of Clojure utilities for things like io.

## Setup

The jar is available at http://clojars.org/factual/sosueme

Include it in your project.clj :dependencies like this:
````clojure
[factual/sosueme "0.0.1"]
````

## Usage

### io

The io package provides utility functions for io.

#### slurp-cp

Slurps content from the classpath. For exaple:

````clojure
(slurp-cp "somefile.txt"
````

## License

The use and distribution terms for this software are covered by the
Eclipse Public License 1.0 (http://opensource.org/licenses/eclipse-1.0.php)
which can be found in the file LICENSE.html at the root of this distribution.
By using this software in any fashion, you are agreeing to be bound by
the terms of this license.
You must not remove this notice, or any other, from this software.
