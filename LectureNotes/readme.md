
# Lecture notes
## May 2019 
### Week 1
#### May 20 2019 Monday, by Yiding Jin
What we have talked about in the class. 

1.learn how to use Github, create your own github repository.   https://guides.github.com/activities/hello-world/ 

2.learn how to making tables and adding hyperlink on markdown.

![table](file:///Users/jinyiding/Desktop/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202019-05-20%20%E4%B8%8B%E5%8D%887.19.08.png)

![link](file:///Users/jinyiding/Desktop/屏幕快照%202019-05-20%20下午7.25.34.png)

3.Created a account on edX and joined the course of MIT to learn python. 

### Week 2
#### May 23 2019 Thursday, by Julian Ye
1.	What are data structures?
		ex. List
		how to organise the data
2.	Fundamental Function:
		performs calculations and remembers results
		calculate speed: a billion calculations per second
		easy calculations are not enough
3.	Turing halting problem: impossible
		Computer cannot solve every single problem
4.	declarative: telling fact
		imperative: recipe or “how to”
5.	how to write ”close enough”  判断close enough 不是相等
		1.	difference reach a particular value, instead of “equal”(infinity)
		2.	BS .1=.5 ; BS .01= .025
		3.	float = int + decimal digit
6.	flow of control: not in normal sequence
7.	fixed programme and stored programme computer
		only one function and combined-function computer
8.	CU + ALU = CPU, Memory, Input, Output 
英语：words
语言：number string simple operator
9.	primitive: smallest unit that cannot be separated again
		add, and, or, not, logic sequence…
10.	syntax: grammar, common and easily caught
		static semantics: find this kind of error before running the programme
		semantics: do not meet my demand to do sth. but syntax and static semantics are correct
    --> Program crashes 
        Run forever
        Give answer but different than expected
11.	definitions: define something ex. a=1
		commands: ex. print something
12.	Nonetype
		list1=[2,3,1]
		list2=list1.append(1)
		print(list2)
		>>>None
		
### Week 3
#### May 30 2019 Thursday, by Lishan Xu
1.ISBN-11 最后一位为校验位:

	Weight权重
	
	10 9 8 7 6 5 4 3 2
	 6 9 8 7 5 1 2 3 4 （）

2.Declaration(comment): # x y z of type integer/ string/ …

3.Logic mistake:

	先判断/执行
	while <condition>:
		code
	while True:
		code
		if <condition>:
			Break
Helping tool: Trace table
	
4.Bisection二分法: 最多次数log2N+1

5.Vocabulary: indentation缩进 concatenate合并 slicing切片 enumeration枚举

6.Factorial example: [eg.](https://github.com/ZeroxAlone/homework190523/blob/master/%E7%AC%94%E8%AE%B0.py)


## May 2019 
### Week 6
#### June 16 2019 Monday, by Weixiao Guo
1. The Sequential Search
   a. What is the sequential search?
      It is a searching technique. 
  
   b. How it works?
      We need to search the item each by each, starting with the first element. If we run out of  items, we have discovered that the item we were searching for was not present.
      It can be efficitient to find a not prensent element in an oredered list. If the item we are looking for is present in the list, the chance of it being in any one of the n positions is still the same as before. In an ordered list, we still looking for it untill we find the item beyond it, then we can stop, and say that the item is not present.
   
   c. The number of trials
      If the item is present, we need to try n/2 times in average to find it, or it is not present, we need to take n trials.
   
   d. Understand and practice.

 2. The Binary Search
    a. What is the binary search?
       It is also a searching technique which is using a clever comparisons.
    
    b. How it works?
       Instead of searching the list in sequence, a binary search will start by examining the middle item. If that item is the one we are searching for, we are done. If it is not the correct item, we can use the ordered nature of the list to eliminate half of the remaining items. If the item we are searching for is greater than the middle item, we know that the entire lower half of the list as well as the middle item can be eliminated from further consideration. The item, if it is in the list, must be in the upper half.

     c. The number of trials
        By finding i in n/(2**i)=1
	n is the number of items
	i is the number of comparison
      
     d. Understand and practice
        method:loop&recursion
	the point of recursion: 明确终止条件 and 自己套用自己


### contributor
Daniel, Julian, Lisa, Shirley, Wilbur, Vivien, Nico, Tim, James, Andy, Cathy, Brian, Harry, Jack 

## June 2019 



## July 2019
