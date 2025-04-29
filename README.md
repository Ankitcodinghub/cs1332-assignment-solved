# cs1332-assignment-solved
**TO GET THIS SOLUTION VISIT:** [CS1332 Assignment Solved](https://www.ankitcodinghub.com/product/cs1332-important-solved-9/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109725&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS1332 Assignment  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
1. All submitted code must compile under JDK 8. This includes unused code, so don’t submit extra files that don’t compile. Any compile errors will result in a 0.

2. Do not include any package declarations in your classes.

3. Do not change any existing class headers, constructors, instance/global variables, or method signatures. For example, do not add throws to the method headers since they are not necessary.

4. Do not add additional public methods.

5. Do not use anything that would trivialize the assignment. (e.g. don’t import/use java.util.ArrayList for an ArrayList assignment. Ask if you are unsure.)

6. Always be very conscious of efficiency. Even if your method is to be O(n), traversing the structure multiple times is considered inefficient unless that is absolutely required (and that case is extremely rare).

7. You must submit your source code, the .java files, not the compiled .class files.

8. Only the last submission will be graded. Make sure your last submission has all required files. Resubmitting will void all previous submissions.

9. After you submit your files, redownload them and run them to make sure they are what you intended to submit. You are responsible if you submit the wrong files.

HashMap

You are to code a LinearProbingHashMap, a key-value hash map with a linear probing collision resolution strategy. A HashMap maps unique keys to values and allows O(1) average case lookup of a value when the key is known.

The table should not contain duplicate keys, but can contain duplicate values. In the event of trying to add a duplicate key, replace the value in the existing (key, value) pair with the new value and return the old value.

You should implement two constructors for this HashMap. As per the javadocs, you should use constructor chaining to implement the no-arg constructor.

If adding to the table would cause the load factor (LF) to exceed (greater than, not greater than or equal to) the max load factor constant provided in the java file, the table should be resized to have a capacity of 2n + 1, where n is the current capacity before adding the parameterized element. See the javadocs for specific instructions on when to resize.

Do not use magic numbers in your code. That is, use the provided INITIAL CAPACITY in your code rather than hardcoding its values.

Hash and Compression Functions

You should not write your own hash functions for this assignment. Instead, use the hashCode() method that every Object has. For the compression function, mod by table length first, then take the absolute value (it must be done in this order to prevent overflow in certain cases). As a reminder, you should be using the hashCode() method on only the keys (and not the LinearProbingMapEntry object itself) since that’s what is used to look up the values. After converting a key to an integer with a hash function, it must be compressed to fit in the array backing the HashMap.

Linear Probing

Your hash map must implement a linear probing collision policy. If the index corresponding to the hash value of the key is occupied, probe in linear increments. For example, if the hash value of your key is 7 with a backing array of capacity 9, and index 7 mod 9 in the array is occupied, check index 7 + 1 mod 9, then 7+2 mod 9, then 7+3 mod 9, etc. until you hit a null spot in the array or after you have attempted table.length probes.

Adding Items

When adding a key/value pair to a HashMap, add the pair to the array in the correct position. Also remember that keys are unique in a hash map, so you must ensure that duplicate keys are not added. When searching for a spot to add, after ensuring no duplicates, you should add at the first encountered removed spot (if there are any). If no removed spots were encountered, add at the null spot that terminated your search.

Removing Items

Grading

Here is the grading breakdown for the assignment. There are various deductions not listed that are incurred when breaking the rules listed in this PDF and in other various circumstances.

Methods:

constructor 3pts

put 17pts

remove 20pts

get 10pts

contains 10pts

keySet 5pts

values 5pts

resizeBackingTable 5pts

Other:

Checkstyle 10pts

Efficiency 15pts

Total: 100pts

JUnits

If you need help on running JUnits, there is a guide, available on Canvas under Files, to help you run JUnits on the command line or in IntelliJ.

Style and Formatting

Javadocs

Vulgar/Obscene Language

Any submission that contains profanity, vulgar, or obscene language will receive an automatic zero on the assignment. This policy applies not only to comments/javadocs, but also things like variable names. Exceptions

When throwing exceptions, you must include a message by passing in a String as a parameter. The message must be useful and tell the user what went wrong. “Error”, “BAD THING HAPPENED”, and “fail” are not good messages. The name of the exception itself is not a good message. For example:

Bad: throw new IndexOutOfBoundsException(‘‘Index is out of bounds.’’);

Good: throw new IllegalArgumentException(‘‘Cannot insert null data into data structure.’’);

Generics

If available, use the generic type of the class; do not use the raw type of the class. For example, use new LinkedList&lt;Integer&gt;() instead of new LinkedList(). Using the raw type of the class will result in a penalty.

Forbidden Statements

• package

• System.arraycopy()

• clone()

• assert()

• Arrays class

• Array class

• Thread class

• Collections class

• Collection.toArray()

• Reflection APIs

• Inner or nested classes

• Lambda Expressions

• Method References (using the :: operator to obtain a reference to a method)

If you’re not sure on whether you can use something, and it’s not mentioned here or anywhere else in the homework files, just ask.

Debug print statements are fine, but nothing should be printed when we run your code. We expect clean runs – printing to the console when we’re grading will result in a penalty. If you submit these, we will take off points.

Provided

The following file(s) have been provided to you. There are several, but we’ve noted the ones to edit.

1. LinearProbingHashMap.java

This is the class in which you will implement the LinearProbingHashMap. Feel free to add private helper methods but do not add any new public methods, inner/nested classes, instance variables, or static variables.

2. LinearProbingMapEntry.java

This class stores a key-value pair and a removed flag for your hash map. Do not alter this file.

3. LinearProbingHashMapStudentTest.java

This is the test class that contains a set of tests covering the basic operations on the LinearProbingHashMap class. It is not intended to be exhaustive and does not guarantee any type of grade. Write your own tests to ensure you cover all edge cases.

Deliverables

You must submit all of the following file(s). Make sure all file(s) listed below are in each submission, as only the last submission will be graded. Make sure the filename(s) matches the filename(s) below, and that only the following file(s) are present. The only exception is that Canvas will automatically append a -n depending on the submission number to the file name(s). This is expected and will be handled by the TAs when grading as long as the file name(s) before this add-on matches what is shown below. If you resubmit, be sure only one copy of each file is present in the submission. If there are multiple files, do not zip up the files before submitting; submit them all as separate files.

Once submitted, double check that it has uploaded properly on Canvas. To do this, download your uploaded file(s) to a new folder, copy over the support file(s), recompile, and run. It is your sole responsibility to re-test your submission and discover editing oddities, upload issues, etc.

1. LinearProbingHashMap.java
