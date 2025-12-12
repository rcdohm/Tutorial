# Understanding Binary

<p>Now that you understand the concept of number bases in familiar base 10, we can introduce the concept of binary. Computers operate through sets of transistors, which you
can think of as like a switch with a position of on or off. This represents two different states, and is where the concept of binary comes from, which allows us
to represent any number with a combination of on and off states, represented in binary as a 1 or a 0. Because there are only two possible states, binary is a base 2
numbering system.</p>

<p>A base 2 number system starts with 2<sup>0</sup>, the ones place just like base 10. However because each place in binary can only represent on or off, a number larger than one requires us to go beyond the first place, like reaching 10 in base 10. The second place in binary is 2<sup>1</sup>, or the twos place. A one in this position represents a
grouping of 2. </p>

<p>Below is table that can help us figure out how to represent numbers in binary. Say for example we want to express the number ten in binary. To do this we have to 
figure out the largest grouping found in the base 2 table that is less than ten. In the table we can see that 2<sup>4</sup> is 16 and too large to represent our number,
so we move to 2<sup>3</sup> which is 8 and the 4th place in a binary number, so it is represented as 1000. Though to reach our number of 10, we require two, which we can do by adding a 1 in the place representing the twos place, giving us 1010. </p>

<p>By expanding on this table and finding which values of the different places would fit into a number, we can express any number with just a combination of 1s and 0s.</p>


## Base 2 table
| Place         | Value           | 
| :----------- | :--------------: | 
| 2<sup>0</sup>| 1 | 
| 2<sup>1</sup>| 2  | 
| 2<sup>2</sup>| 4 | 
| 2<sup>3</sup>| 8  | 
| 2<sup>4</sup>| 16 | 
| 2<sup>5</sup>| 32  | 
| 2<sup>6</sup>| 64 | 
| 2<sup>7</sup>| 128  | 
|2<sup>8</sup>| 256  |
