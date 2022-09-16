---
layout: essay
type: essay
title: Smart Questions Analysis
# All dates must be YYYY-MM-DD format!
date: 2022-09-08
published: true
labels:
- Software Engineering
- Learning
- Stack Overflow
- Smart Questions
---

<img width="400px" class="rounded float-start pe-4" src="../img/smart-questions/questionmark.jpeg">

### Think Before You Ask
In every class from high school to college, the most repeated phrase during a lecture has to be “Are there any questions?” In all my years of schooling I have asked only a handful of questions.  Coming up with a good question on the fly while learning new material can be tough. However, in the scope of software engineering, questions tend to arise during code implementation, where errors are often thrown during execution or lack of experience leads to not knowing how to implement a solution. Asking a smart question leads to efficient and effective use of your time. 

According to Eric Steven Raymond in [How To Ask Questions The Smart Way](http://www.catb.org/esr/faqs/smart-questions.html), asking a question involves searching for the answer first. Trying to understand the problem at hand leads you down a path where you can learn something on the way. Showing proof that you searched first before asking is important to those who may answer the question. Oftentimes a good question can provide answers with examples of proper code or a source that leads to the answer.

### Formulating a Question

The following are guidelines given by Raymond to think of before asking a question: 
1. Try to find an answer by searching the archives of the forum or mailing list you plan to post to.
2. Try to find an answer by searching the Web.
3. Try to find an answer by reading the manual.
4. Try to find an answer by reading a FAQ.
5. Try to find an answer by inspection or experimentation.
6. Try to find an answer by asking a skilled friend.
7. If you're a programmer, try to find an answer by reading the source code.

Once you've gone through searching for answers yourself, it's time to formulate your question. The question should include as much detail for the problem being faced, as well as documentation of sources or different ideas that have been tried. A properly formatted question will lead to a greater response from the community on the forum. 

### Smart Questions Yield Effective Answers
The following question was asked on StackOverflow regarding methods to copy the contents of an array into another array. The question clearly states a problem and detail in regard to the answer they are looking for. Along with the question, the author includes their knowledge of an existing method in the Python programming language and a JS method that results in the same outcome, but is achieved with different behaviour. The provided code block specifies the type of behavior the method will have on an array. The question received 1321 upvotes and garnered answers that provided different methods for supporting browsers.  
________________________________________________________________________________________________________

Asked by DzinX on [StackOverflow Page](https://stackoverflow.com/questions/1374126/how-to-extend-an-existing-javascript-array-with-another-array-without-creating).
####  *"How to extend an existing JavaScript array with another array, without creating a new array?"*

There doesn't seem to be a way to extend an existing JavaScript array with another array, i.e. to emulate Python's extend method.

I want to achieve the following:
```
>>> a = [1, 2]
[1, 2]
>> b = [3, 4, 5]
[3, 4, 5]
>>> SOMETHING HERE
>>> a
[1, 2, 3, 4, 5]`
```
I know there's a a.concat(b) method, but it creates a new array instead of simply extending the first one. I'd like an algorithm that works efficiently when a is significantly larger than b (i.e. one that does not copy a).

________________________________________________________________________________________________________


### A Bad Question Wastes Time 
Submitting a question to a forum such as StackOverflow takes time. When the question is not clear or detail is not provided, it wastes the time of the author and people attempting to help. The following post is headed with a statement instead of a question. The body provides no detail with how the author tried to implement their solution. The post gained 5 downvotes. Because there is lack of detail in the body, a reader can speculate that the author did not take time to search the web for an algorithm to implement reversing a linked list. 

________________________________________________________________________________________________________

Asked by Vivek M. on [StackOverflow Page](https://stackoverflow.com/questions/38718013/reverse-a-linked-list-in-c).
####  *"Reverse a linked list in C"*

```
void reverse(node *pointer) {
    node *head, *curr;
    head = pointer;
    curr = head;
    while (head != NULL) {
        while (curr -> next != NULL) {
            curr = curr -> next;
        }
        printf("%d", curr -> data);
        free(curr);
        curr = head;
    }
}
```
I don't know what's wrong with the code it prints only the last node of the linked list while trying to reverse it.

________________________________________________________________________________________________________
