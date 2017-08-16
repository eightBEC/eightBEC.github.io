### That's me

A lot of people ask me where my nickname - **eightBEC** or **8BEC** - is coming from.

When I was 13 years old, I started to get interested in reverse engineering. It fascinated me to solve those complex puzzles :mag: like CrackMes or KeygenMes. One of the first tasks when analyzing a program, is to look for the entry point - that position where your debugger enters the code of your program.
`8BEC` is the hexadecimal representation of a part of this entry sequence for a function in assembly. Actually there is a `55` before the `8BEC` instruction, but that was a little too unspecific for a nickname.

Both instructions ensure a proper setup of the stack frame for a function. This guarantees that function parameters and local variables can be accessed in a consistent way. More on this topic in this [book](https://books.google.de/books?id=TpEZq3TCeHsC).
```assembly
 55             push ebp      ; save EBP
 8BEC           mov ebp, esp  ; establish stack frame
```


*That's the story of how it all started - Fast Forward:*


Currently I'm a Cognitive Engineer at IBM Watson in Germany working together with clients on innovative use cases cross industries. I have a strong background in NLP and Machine Learning and experienced in Java, Python and C.  
*Studies*: Innovation and Management Master Programme at [SMI](https://www.steinbeis-smi.de/de/master/programme/management-innovation.html) and a Bachelor of Science from DHBW Stuttgart in Computer Science with a semster abroad in China.

Curious about everything related to technology, art, sustainability, politics and economics. I think all of this is somehow related and it's important that we focus on those relationships rather than having a tunnel view on a specific field on interest.

### Articles & Publications

For my latest publications take a look at my [Google Scholar](https://scholar.google.com/citations?hl=en&user=tOdSeTUAAAAJ) profile.

### Projects

Some of my electronics and 3D printing projects can be found on my old [blog](https://eightbec.github.io/blog/).  
For all open source software projects take a look at my [github](https://github.com/eightBEC) profile.
