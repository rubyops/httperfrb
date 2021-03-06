HTTPerf.rb
==========

### 0.3.11

* Fixing error handling in process handing for `HTTPerf#run`.

### 0.3.10

* Adding `tee` support.

### 0.3.6

* cleaning up Open3 vs. Open4 and making them autoload for a slight performance increase

### 0.3.5

* fixing bug with parsing verbose output
* fixing bug with generating percentiles when less then 100 tests

### 0.3.3

* adding limited grapher handling back

### 0.3.2

* removed all grapher and verbose handling, as it isn't working as expected

### 0.3.1

* fixing verbose bug

### 0.3.0

* added handling for [HTTPerf::Grapher](http://github.com/rubyops/httperfrb-grapher)

### 0.2.1

* added verbose handling
* refactored parser a bit

### 0.2.0

* added parser
* changed default output of run to parsed

### 0.1.2

* fixed an issue with run output

### 0.1.1

* updating gem dependancy list to include 'open4'

### 0.1.0

* refactored #run to run system commands in a cleaner fashion
* added #fork to run in a thread
* added #fork_out to return the output from the last #fork
* added #fork_err to return the error from the last #fork


### 0.0.2

* fix a few critical bugs with params - 0.0.1 is bad


### 0.0.1

* Initial release.

