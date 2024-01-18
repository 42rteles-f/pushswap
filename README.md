![pushswapexecution](https://github.com/42rteles-f/pushswap/assets/89268663/015729d6-5458-4baa-bf98-15473b2e6042)

The pushswap is a program about, quite simply, pushing and swaping numbers from one list to another in order to put them well... in order.

Although I learned quite a few sort algorithms such as bubble sort and selection sort, which aren't efficient enough for this projects, or others that could have been adapted to it like the merge sort. I choose to use the radix sort, I found its simplicity and the use of bitwise intriguing.

![pushswapfunc](https://github.com/42rteles-f/pushswap/assets/89268663/9c975d95-48db-473c-9a02-99987de2b919)

In a very simple way, examining each number based on its bits, the radix will separate the numbers in 2 groups, one group will contain all the smaller numbers, but it will carry some bigger numbers as well. In the next loop, it will filter those big numbers out of the middle of the smaller ones, doing this during each loop until finally the numbers will be completely arranged.
