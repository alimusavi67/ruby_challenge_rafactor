what code do:
1- this code read txt file from given path
2- sort them with date that came from file names with specific regular expression
3- choose the last date(most recent)
4- sort file with Clicks field of it
5- the goal is to read any files match our date condition and make one file from them based on rules code use for combine
data with same Unique ID and row numbers
as we can see in test file :
  .if when all enumerators have a sequence of elements with the same key([enumerator_for(1,2), enumerator_for(1,2)]) we have  [1,1],[2,2] in return
  .when all enumerators have a sequence of elements with the same key, but one is longer ([enumerator_for(1,2), enumerator_for(1,2,3)] ) we have [1,1],[2,2],[nil,3]
   and other rules we have in test files
i do not do much change in code, this code is alrady doing good, 
for better OO design maybe its good to seprate some part of modifre code in other classess
