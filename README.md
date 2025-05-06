# functional-programming-assignment-4-ransitioning-to-haskell-and-sml-solved
**TO GET THIS SOLUTION VISIT:** [Functional-Programming Assignment 4-ransitioning to Haskell and SML Solved](https://www.ankitcodinghub.com/product/functional-programming-assignment-4-ransitioning-to-haskell-and-sml-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97098&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Functional-Programming Assignment 4-ransitioning to Haskell and SML   Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

4.1 Submission instructions

<ol>
<li>Unzip the A4.zip folder. You should find 2 folders, each with one file inside: 􏰀 hs, containing Solutions.hs – for the Haskell exercises

􏰀 sml, containing solutions.sml – for the SML exercises</li>
<li>Edit the first line of each of the source files as described in the comments.</li>
<li>Edit the source files with your solutions.</li>
<li>When done, zip (not rar renamed as zip!) this A4 folder and name the zip archive with the following format:
A4 ⟨FirstName⟩ ⟨LastName⟩ ⟨Group⟩

Examples of valid names:

􏰀 A4 John Doe 30432.zip

􏰀 A4 Ion Popescu 30434.zip

􏰀 A4 Gigel-Dorel Petrescu 30431.zip

Examples of invalid names:

􏰀 Solutions.zip

􏰀 A4.zip

􏰀 Solutii A4 Ion Popescu.zip
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
117

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
4.2 Assignment exercises 4.2.1 Haskell

Exercise 4.2.1 2p Implement a function strWords that splits a string into a list of words. You can assume

</div>
</div>
<div class="layoutArea">
<div class="column">
that the string contains only letters and spaces.

<pre>   &gt; strWords "Whats up doc"
   ["Whats", "up", "doc"]
   &gt; strWords "Beware the Jabberwock my son"
   ["Beware", "the", "Jabberwock", "my", "son"]
</pre>
</div>
<div class="column">
Haskell REPL

</div>
</div>
<div class="layoutArea">
<div class="column">
Implementation restrictions:

Aside from the functions that you define, you may only use the following library functions in your implementation: take , drop , takeWhile , dropWhile , span , foldl , foldr .

Grading:

2 points for the correct implementation

Exercise 4.2.2 2p

Implement a function piglatinize that converts strings to pig latin. The first consonant of each word is moved to the end of the word and “ay” is added, so “first” becomes “irst-fay.” Words that start with a vowel (’a’, ’e’, ’i’, ’o’ or ’u’) have “hay” added to the end instead (“apple” becomes “apple-hay”). You can assume that the input string contains only letters and spaces.

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>   &gt; piglatinize "Whats up doc"
   "hats-Way up-hay oc-day"
   &gt; piglatinize "An apple a day keeps the doctor away"
   "An-hay apple-hay a-hay ay-day eeps-kay he-tay octor-day away-hay"
</pre>
Hint:

Use your strWords words function to split the string.

</div>
</div>
<div class="layoutArea">
<div class="column">
Implementation restrictions:

Aside from the functions that you define, you may only use the following library functions in your implementation: elem , notElem , intersperse , intercalate , filter , map

Grading:

􏰀 1 point for defining a function that transforms a given word to pig latin.

􏰀 1 point for defining a function that concatenates the transformed words (by placing

spaces between them) into a string.

</div>
</div>
<div class="layoutArea">
<div class="column">
Haskell REPL

</div>
</div>
<div class="layoutArea">
<div class="column">
118

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Exercise 4.2.3 2p

</div>
</div>
<div class="layoutArea">
<div class="column">
Write a function apprPi :: Double will be used to approximate −π (minus pi) using the the iter function.

1. Implement the nextPi :: Double -&gt; Double function that will be used by iter to generate the next approximation of pi, based on the following formula:

</div>
</div>
<div class="layoutArea">
<div class="column">
2 · cos(xn )

xn+1 = xn + 2 , x0 = 0

</div>
</div>
<div class="layoutArea">
<div class="column">
2 · sin(xn ) − 1 2

</div>
</div>
<div class="layoutArea">
<div class="column">
2. Implement the apprPi function that uses iter and nextPi to approximate −π until two successive elements are equal.

Implementation restrictions:

Aside from the functions that you define, you may only use the following library functions in your implementation: takeWhile , dropWhile , last , head , snd , fst

Grading:

􏰀 1 point for implementing the nextPi function

􏰀 1 point for returning the correct result

Exercise 4.2.4 7p

Define a function topWords n str , with the signature topWords :: Int -&gt; String -&gt; [(String, Int)] that returns the top n words from the string str , by the number of occurrences. If there are multiple words with the same number of occurrences, you should break the ties sorting the words in lexicographic

order. You can assume that the input string contains only letters and spaces.

Haskell REPL

<pre>   &gt; topWords 10 "I know that you know that I know"
   [("know", 3), ("I", 2), ("that", 2), ("you", 1)]
   &gt; topWords 3 "I know that you know that I know"
   [("know", 3), ("I", 2), ("that", 2)]
</pre>
<pre>   &gt; topWords 6 "An apple a day keeps the doctor away"
   [("An", 1), ("a", 1), ("apple", 1), ("away", 1), ("day", 1), ("doctor", 1)]
</pre>
Solution option 1:

One possible solution is to define a function update fn def k l with the signature

udpate::(Eqk)=&gt;(v-&gt;v)-&gt;v-&gt;k-&gt;[(k,v)]-&gt;[(k,v)] thatlooksupthekey

k in the association list l . If the key is found, then the update function fn is applied to the value associated to the key and the list with the update value is returned. If the key is not found, the key is inserted into the association list with the default value def .

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>&gt; update (+1) 1 "a" [("a", 2), ("b", 3), ("c", 1)]
[("a", 3), ("b", 3), ("c", 1)]
&gt; update (+1) 1 "d" [("a", 2), ("b", 3), ("c", 1)]
[("a", 3), ("b", 3), ("c", 1), ("d", 1)]
</pre>
<pre>&gt; update (+1) 1 "c" [("a", 2), ("b", 3), ("c", 1)]
[("a", 3), ("b", 3), ("c", 2)]
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
119

</div>
</div>
<div class="layoutArea">
<div class="column">
Haskell REPL

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Solution option 2:

1. Implement a function uniques :: (Eq a) =&gt; [a] -&gt; [a] that obtains the unique el-

</div>
</div>
<div class="layoutArea">
<div class="column">
ements from a list.a

&gt; uniques [1, 2, 1, 4, 3, 2]

[1, 2, 3, 4]

</div>
<div class="column">
Haskell REPL

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol start="2">
<li>Implement a function countOccurrences :: (Eq a) =&gt; a -&gt; [a] -&gt; Int that counts how many times a given element occurs in a list.
Haskell REPL

<pre>        &gt; countOccurrences 1 [1, 2, 1, 4, 3, 2]
        2
</pre>
</li>
<li>Implement a function countWords :: String -&gt; [(String, Int)] that uses uniques and countOccurencres obtain a list of (word, count) tuples. This list does not have to be sorted (yet)!</li>
</ol>
Implementation restrictions:

Aside from the functions that you define, you may only use the following library functions in your implementation: map , filter , head , tail , take , drop , takeWhile , dropWhile ,

foldl , foldr , span , sortOn , sortBy Grading:

􏰀 5 points for obtaining the unsorted list of (word, count) tuples. – If you choose option 1 (the update function):

<ul>
<li>* &nbsp;2 points for handling the case when the value is missing from the associ- ation list</li>
<li>* &nbsp;3 points for handling the case when the value is already present in the association list
– If you choose option 2 ( uniques , countOccurencres and countWords ): * 2 points for the uniques function

* 2 points for the countOccurrences function

* 1 point for the countWords function

􏰀 2 points for obtaining the top n words

– 1 point for sorting the list by word countb

– 1 point for sorting the ties lexicographically

aYou might want to take a look at the quicksort function. Specifically what happens if you change the comparison operators in the partition part from (&lt;=) to (&lt;) and (&gt;=) to (&gt;).

bi.e. you still get one point if the output is only sorted by the number of occurrences
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
120

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
4.2.2 SML

</div>
</div>
<div class="layoutArea">
<div class="column">
Exercise 4.2.5 2p

Implement in SML a function levenshtein: string -&gt; string -&gt; int to calculate the Lev- enshtein distance of 2 string, in terms of the following operations: insertions, deletions and substitutions.

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>- levenshtein "kitten" "sitting";
val it = 3 : int;
- levenshtein "haskell" "sml";
val it = 5 : int;
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
121

</div>
</div>
<div class="layoutArea">
<div class="column">
SML REPL

</div>
</div>
</div>
