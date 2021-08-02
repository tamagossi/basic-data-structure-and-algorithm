# BIG O

---

### What is Big O?

Big O Notation is a relative representation of an algorithm's complexity. It describes how an algorithm performs and scales by denoting an upper bound of its growth rate. 

**So, what is Big O Notation? In simple terms:**
* It is the relative representation of the complexity of an algorithm.
* It describes how an algorithm performs and scales.
* It describes the upper bound of the growth rate of a function and could be thought of the worst case scenario.

**How to read a big O notation:**
Now for a quick look at the syntax: O(n<sup>2</sup>).
<em>n</em> is the number of elements that the function receiving as <em>inputs</em> . So, this example is saying that for n inputs, its complexity is equal to n<sup>2</sup>





<p align="center">
  <img src="https://miro.medium.com/max/1200/1*j8fUQjaUlmrQEN_udU0_TQ.jpeg" alt="Sublime's custom image" width="1000"/>
  <small><strong>HINT:</strong> Way to determine Big O is <strong>how much operation need to takes per ampunt of inputs/elements</strong></small>
</p>

### Types of Big O

-   [**O(n)**](#o-n-detailed)
-   [**O(1)**](#o-1-detailed)
-   **O(n<sup>2</sup>)**
-   **O(2<sup>n</sup>)**
-   **O(log n)**
-   **O(n!)**

---

<h4 id='o-n-detailed'>O (n)</h4>

<em>O(n)</em> represents the complexity of a function that increases linearly and in direct proportion to the number of inputs. example of with O(n) complexity:

```
  bool containsName(List<String> names, String nameToFind) {
    names.forEach((String name) {
      if (name == nameToFind) return true;
    });

    return false;
  }
```
___

<h4 id='o-1-detailed'>O (1)</h4>

<em>O(1)</em> represents a function that always takes the same take regardless of input size.

```
  bool isTheFirstNumberEqualToOne(List<int> numbers) {
    return numbers[0] == 1
  }
```
___

[**Source**](https://dzone.com/articles/learning-big-o-notation-with-on-complexity)
