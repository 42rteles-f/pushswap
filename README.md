![pushswapexecution](https://github.com/42rteles-f/pushswap/assets/89268663/015729d6-5458-4baa-bf98-15473b2e6042)

The pushswap is a program about, quite simply, pushing and swaping numbers from one list to another in order to put them well... in order.

Although I learned quite a few sort algorithms such as bubble sort and selection sort, which aren't efficient enough for this projects, or others that could have been adapted to it like the merge sort. I choose to use the radix sort, I found its simplicity and the use of bitwise intriguing.

![pushswapfunc](https://github.com/42rteles-f/pushswap/assets/89268663/9c975d95-48db-473c-9a02-99987de2b919)

In a very simple way, we will look at each numbers bit starting from the least relevant one to the most relevant. The radix will separate the numbers in 2 groups, one group will contain all the numbers with the current looked at bit set to 1, and the other with the bits set to 0. Then we push one group on top of each other, go to the next bit and repeat, by the last bit your numbers will be in complete order. 
What happens here is, when you put the "0 bit group"(smaller group) on top of the "1 bit group"(bigger group), you are almost putting the smaller ones on top of the bigger ones. But of course because you are looking at one bit at a time, there is going to be bigger numbers among the smaller group. But not to worry eventually you will check those bigger bits and the bigger numbers will be removed from the first group of 0 bit. So with each step you will filter the "fake small" ones from the truly small, and have them in true order.
In resume, just taking away the bigger bit number away and put it back on the stack, will sort the list.
