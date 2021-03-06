# NumberConverter
library currently have one method ```NumberConverter.int2str()``` which takes integer (N) as an argument, return a string representation of that integer.

## Getting Started
##### Installation #####
1. Clone this Repository.
2. Run ```mvn install``` to install it into local Maven repository.

##### Usage #####
Add this dependency
```xml
<dependency>
    <groupId>com.srj</groupId>
    <artifactId>num-converter</artifactId>
    <version>1.0</version>
</dependency>
```

Example:
```java
import com.srj.converter.NumberConverter;
public class test {
    public static void main(String[] args) {
        System.out.println(NumberConverter.int2str(233434222));
    }
}
```
Output:
```text
Two Hundred Thirty-Three Million Four Hundred Thirty-Four Thousand Two Hundred Twenty-Two
```


<!---

Number to String
================

Using a JVM based language of choice, *produce a library* that has the following capability within it:

**given some integer (N) as an argument, return a string representation of that integer.**

For example, using the capability in a scala REPL (implemented as a function called _int2str_) may look like this:
```
scala> int2str(5)
res0: String = five

scala> int2str(55)
res1: String = fifty-five
```


As a part of the submission, treat the library as though it were an API (which may have new capabilities in the future) that will be used within an organization for production use.  Given that, it should include an appropriate level of professional cleanliness that you would stand behind for a published library.

For the purpose of this problem, the solution should actually solve the problem, rather than purely delegate to another library to do the heavy lifting (such as ```com.ibm.icu.icu4j```).  While dependencies are permitted, the implementation of the solution should be thoughtful in the dependencies it brings in.

As far as the workflow for submission:

1. Create a branch, using a branch name you feel is appropriate.
2. Once you're satisfied with your solution, create a pull request against _master_

--->
