# csci203-csci803-assignment-1-in-java-solved
**TO GET THIS SOLUTION VISIT:** [CSCI203/CSCI803 ASSIGNMENT 1 in Java Solved](https://www.ankitcodinghub.com/product/csci203-csci803-assignment-1-solved-3/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;31332&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI203\/CSCI803 ASSIGNMENT 1 in Java Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
You are to write a word processing program in one file (only) named: ass1.cpp or ass1.java, etc.&nbsp; Your main() procedure should record the start time of your program and, at the end of processing, display the total run time of your program (in seconds).&nbsp; You should do this work in steps, as described below. You may use any data structures and algorithms that have been presented in class up to the end of week 4. If you use other data structures or algorithms, appropriate references must be provided.&nbsp; <strong>Note: You will only receive the 2 marks for step-1 if you complete and demo Step-1 in your lab class in week-4.</strong>

&nbsp;

<h1>Step-1 (Week-4 demo, 2 marks)</h1>
Write a program that reads the dictionary file (named: “dictionary.txt) and places the words in an appropriate array and then prints the number of words read on the screen. (You can assume that the dictionary contains no more than 400,000 words and no word is longer than 35 characters.)&nbsp; Then write a function <u>that uses a linear search</u> to find the first 5 emordnilap words in the dictionary array and displays them on the screen. Note: An emordnilap word is a word larger than 1 character that when spelled backward exists in the dictionary, e.g.: “peels – sleep” or “racecar – racecar”. (Yes palindromes are emordnilap words too. In fact “emordnilap” is “palindrome” spelled backwards.) Example output:

<strong>&nbsp;</strong>

<strong>Number of words in dictionary: 370103 </strong>

<strong>First 5 emordnilap words: </strong>

<strong>aa : aa aaa : aaa aas : saa ab : ba aba : aba </strong>

<strong>&nbsp;</strong>

<strong>Total run time (secs): 1 </strong>

&nbsp;

Note:&nbsp; Make sure your search stops when the first 5 emordnilap words are found. Step-1 is not about speed. We will speed it up in step-2. . .

&nbsp;

<h1>Step-2 (More Emordnilap words, 2 marks)</h1>
Before you commence Step-2, estimate how long it would take for your step-1 linear search to find all the emordnilap words in the dictionary? Now, replace the linear search with a binary search and determine the time to find ALL the emordnilap words in the dictionary. Write your estimate of the speedup factor in the report in Step-5. Print on the screen: the first 10 emordnilap words found (similar to step-1) and the longest emordnilap word found. (Note: if there is more than one emordnilap word with the longest length, print the first one only.) Implement other speed enhancements if you can think of any.

&nbsp;

<h1>Step-3 (Spell-check, 3 marks)</h1>
Read the input data file: “sample.txt”, pre-process it (as explained below) and search for each word (once only) in the dictionary. Then print on the screen the total number of valid words read, the number of unique words read, and the number of unique words read that were found in the dictionary. You should store all unique words that were found in the dictionary in a suitable array.

&nbsp;

<u>Note:</u> To pre-process the words read from “sample.txt”, all capitals should be converted to lower case. Punctuation marks in words should be removed and treated as a single word. Thus, <em>it’s </em>will become <em>its</em>, <em>you’ll </em>will become <em>youll </em>and <em>loop-hole </em>will become <em>loophole</em>. Any word that becomes zero characters as a result of the pre-processing should be rejected it as an invalid word.

<strong>&nbsp;</strong>

<h1>Step-4 (Anagrams, 3 marks)</h1>
Use the dictionary to find anagrams of the unique words stored in the array from step-3. Print the first 10 anagram words together with their anagrams in alphabetic order e.g.: <strong>&nbsp;admire: armied damier dimera merida&nbsp; after: afret frate trefa&nbsp; …. </strong>

Also, print the word with the most anagrams, the longest word with anagram(s), the total number of words with anagram(s) and the total number of anagrams found. Optimise your code so that it completes this task as quickly as possible.

<strong>&nbsp;</strong>

<h1>Step-5 (Specifications, 2 marks)</h1>
In a comment block at the bottom of your program, write the following details in no more than 20 lines of text. State the run time of your final program and what machine this was on. Quote the speedup achieved in step-2. List the data structures and algorithms used by your program to spellcheck, find emordnilap words and find anagrams. Also include any other enhancements you did to speed up your program (if any). For this step, marks will be awarded based on how accurately and clearly you describe your program.

<strong>&nbsp;</strong>

<strong>Marking Guide: </strong>

Programs must compile and run on banshee under gcc (C programs), g++ (C++ programs), javac (Java programs) or python (python programs). Programs which do not compile and run on banshee will receive no marks. Marks may be deducted for untidy or poorly designed code. Appropriate comments should be provided where needed. All coding and comments must be your own work. <u>Inbuilt standard libraries or data structures and algorithms, such as STL should not be used.</u> You may use <em>string</em> or <em>String </em>type for storing the words, if you wish.

&nbsp;

<strong>Submission: </strong>

Assignments should be typed into a single text file named “ass1.<em>ext” </em>where <em>“ext” </em>is the appropriate file extension for the chosen language. You should run your program and copy and paste the output into a text file named: “output.txt”

&nbsp;
