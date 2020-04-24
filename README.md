# home-assignment-dinatech

#######################################################################################
This findOddEvenPair function accepts an array and output int - index of valid pair. 
If in array is more than one valid answers function will ask You to provide an index number which valid pair index You need and will return it.

To use this function :
echo findOddEvenPair ([1,2,4,3,7]). 

How it works:
1. incoming array is splited in pairs with array_chunk.
2. for each pair function is checking if the first number is odd or even and the same for the second number 
if they are different then the pair is valid and stored in $result array.
3.In the and function returns intiger - index of valid pair. If in array is more than one valid answers 
function will ask You to provide an index number which valid pair index You need and will return it.

########################################################################################
Class of SummationService 
accepts array and provide method sum which acepts two parametrs for array slice $a = $offset , $b = $length and will sum sliced array.
more info about array slice - https://www.php.net/manual/en/function.array-slice.php
more info about array sum - https://www.php.net/manual/en/function.array-sum.php


To use this method :
echo (new SummationService(array $Yourarray))->sum($a,$b);

########################################################################################

function longestSubstr(string $text): string

accepts string and returns return its longest substring that does not include any
two-character sequence more than once.  In case there are several such substrings
with the same number of characters in them, function will return the
leftmost one.

echo longestSubstr('aaa');   \\ output : aa


