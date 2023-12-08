Mini Max Sum Time complexity: The time complexity for Mini Max Sum is O(n^2), this is because the code makes use of a nested
for loop (one for loop inside of a for loop). This means that for n elements we are checking we are also comparing it n additional
times. There are also no reucrssive elemtns so there is no additional checks aside from the nestd for loop. Thus n * n = n^2 for O(n^2).

Mini Max Sum Space complexity: The Space complexity for Mini Max Sum is O(c), this is becuase no new information is needed from the input
and the input itself does not change or get recalled later. This makes our input a refference point to find the Sum of the
biggest and smallest element. Since nothing is changed, we have a spce complexity of constant time or O(c).

