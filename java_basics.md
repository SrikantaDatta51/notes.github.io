
### 1. Arrays
   **a. Sorting in Descending Order**
   ```java
   Integer[] arr = {5, 2, 8, 1};
   Arrays.sort(arr, Collections.reverseOrder());
   ```

### 2. ArrayList
   **a. Iterating over ArrayList**
   ```java
   ArrayList<Integer> list = new ArrayList<>(Arrays.asList(1, 2, 3));
   for (int num : list) {
       System.out.println(num);
   }
   ```

### 4. HashMap
   **a. Iterating over Key-Value Pairs**
   ```java
   HashMap<String, Integer> map = new HashMap<>();
   map.put("A", 1);
   map.put("B", 2);
   for (Map.Entry<String, Integer> entry : map.entrySet()) {
       System.out.println(entry.getKey() + ": " + entry.getValue());
   }
   ```


   **b. Filling an Array**
   ```java
   int[] arr = new int[5];
   Arrays.fill(arr, 10); // arr = {10, 10, 10, 10, 10}
   ```

   **c. Copying an Array**
   ```java
   int[] original = {1, 2, 3};
   int[] copy = Arrays.copyOf(original, original.length);
   ```

   **d. Comparing Two Arrays**
   ```java
   int[] arr1 = {1, 2, 3};
   int[] arr2 = {1, 2, 3};
   boolean equal = Arrays.equals(arr1, arr2); // equal = true
   ```

   **e. Converting Array to List**
   ```java
   Integer[] arr = {1, 2, 3};
   List<Integer> list = Arrays.asList(arr);
   ```

### 2. ArrayList
   **a. Iterating over ArrayList**
   ```java
   ArrayList<Integer> list = new ArrayList<>(Arrays.asList(1, 2, 3));
   for (int num : list) {
       System.out.println(num);
   }
   ```

   **b. Removing an Element**
   ```java
   ArrayList<Integer> list = new ArrayList<>(Arrays.asList(1, 2, 3));
   list.remove(1); // Removes element at index 1
   ```

   **c. Checking if List Contains an Element**
   ```java
   ArrayList<Integer> list = new ArrayList<>(Arrays.asList(1, 2, 3));
   boolean contains = list.contains(2); // contains = true
   ```

   **d. Finding Index of an Element**
   ```java
   ArrayList<Integer> list = new ArrayList<>(Arrays.asList(1, 2, 3));
   int index = list.indexOf(2); // index = 1
   ```

   **e. Replacing an Element**
   ```java
   ArrayList<Integer> list = new ArrayList<>(Arrays.asList(1, 2, 3));
   list.set(1, 5); // list = {1, 5, 3}
   ```

### 3. HashSet
   **a. Adding Multiple Elements**
   ```java
   HashSet<Integer> set = new HashSet<>();
   set.addAll(Arrays.asList(1, 2, 3));
   ```

   **b. Removing an Element**
   ```java
   HashSet<Integer> set = new HashSet<>(Arrays.asList(1, 2, 3));
   set.remove(2); // Removes value 2
   ```

   **c. Checking Set Size**
   ```java
   HashSet<Integer> set = new HashSet<>(Arrays.asList(1, 2, 3));
   int size = set.size(); // size = 3
   ```

   **d. Clearing the Set**
   ```java
   HashSet<Integer> set = new HashSet<>(Arrays.asList(1, 2, 3));
   set.clear(); // set is now empty
   ```

   **e. Converting Set to Array**
   ```java
   HashSet<Integer> set = new HashSet<>(Arrays.asList(1, 2, 3));
   Integer[] arr = set.toArray(new Integer[set.size()]);
   ```

### 4. HashMap
   **a. Iterating over Key-Value Pairs**
   ```java
   HashMap<String, Integer> map = new HashMap<>();
   map.put("A", 1);
   map.put("B", 2);
   for (Map.Entry<String, Integer> entry : map.entrySet()) {
       System.out.println(entry.getKey() + ": " + entry.getValue());
   }
   ```

   **b. Removing a Key-Value Pair**
   ```java
   HashMap<String, Integer> map = new HashMap<>();
   map.put("A", 1);
   map.remove("A"); // Removes key "A"
   ```

   **c. Checking if Key Exists**
   ```java
   HashMap<String, Integer> map = new HashMap<>();
   map.put("A", 1);
   boolean exists = map.containsKey("A"); // exists = true
   ```

   **d. Getting Default Value if Key Not Found**
   ```java
   HashMap<String, Integer> map = new HashMap<>();
   int value = map.getOrDefault("A", 0); // value = 0
   ```

   **e. Replacing a Value**
   ```java
   HashMap<String, Integer> map = new HashMap<>();
   map.put("A", 1);
   map.replace("A", 5); // "A" now maps to 5
   ```

### 5. LinkedList
   **a. Adding Element at Specific Position**
   ```java
   LinkedList<Integer> list = new LinkedList<>();
   list.add(1);
   list.add(1, 2); // list = {1, 2}
   ```

   **b. Getting First and Last Elements**
   ```java
   LinkedList<Integer> list = new LinkedList<>(Arrays.asList(1, 2, 3));
   int first = list.getFirst(); // first = 1
   int last = list.getLast(); // last = 3
   ```

   **c. Removing First and Last Elements**
   ```java
   LinkedList<Integer> list = new LinkedList<>(Arrays.asList(1, 2, 3));
   list.removeFirst();
   list.removeLast(); // list = {2}
   ```

   **d. Converting to Array**
   ```java
   LinkedList<Integer> list = new LinkedList<>(Arrays.asList(1, 2, 3));
   Integer[] arr = list.toArray(new Integer[list.size()]);
   ```

   **e. Clearing the List**
   ```java
   LinkedList<Integer> list = new LinkedList<>(Arrays.asList(1, 2, 3));
   list.clear(); // list is now empty
   ```

### 6. PriorityQueue (Heap)
   **a. Creating a Max-Heap**
   ```java
   PriorityQueue<Integer> maxHeap = new PriorityQueue<>(Collections.reverseOrder());
   maxHeap.add(5);
   maxHeap.add(2);
   int max = maxHeap.poll(); // max = 5
   ```

   **b. Checking if Heap is Empty**
   ```java
   PriorityQueue<Integer> heap = new PriorityQueue<>();
   boolean isEmpty = heap.isEmpty(); // isEmpty = true
   ```

   **c. Getting Size of Heap**
   ```java
   PriorityQueue<Integer> heap = new PriorityQueue<>(Arrays.asList(1, 2, 3));
   int size = heap.size(); // size = 3
   ```

   **d. Removing Specific Element**
   ```java
   PriorityQueue<Integer> heap = new PriorityQueue<>(Arrays.asList(1, 2, 3));
   heap.remove(2); // Removes value 2
   ```

   **e. Clearing the Heap

**
   ```java
   PriorityQueue<Integer> heap = new PriorityQueue<>(Arrays.asList(1, 2, 3));
   heap.clear(); // heap is now empty
   ```

### 7. Stack
   **a. Checking if Stack is Empty**
   ```java
   Stack<Integer> stack = new Stack<>();
   boolean isEmpty = stack.isEmpty(); // isEmpty = true
   ```

   **b. Peeking at Top Element without Removing**
   ```java
   Stack<Integer> stack = new Stack<>();
   stack.push(5);
   int top = stack.peek(); // top = 5
   ```

   **c. Getting Stack Size**
   ```java
   Stack<Integer> stack = new Stack<>();
   stack.push(5);
   int size = stack.size(); // size = 1
   ```

   **d. Searching for an Element in Stack**
   ```java
   Stack<Integer> stack = new Stack<>();
   stack.push(5);
   int position = stack.search(5); // position = 1
   ```

   **e. Converting Stack to Array**
   ```java
   Stack<Integer> stack = new Stack<>();
   stack.push(5);
   Object[] arr = stack.toArray();
   ```

### 8. String Manipulation
   **a. Converting to Upper and Lower Case**
   ```java
   String str = "Hello";
   String upper = str.toUpperCase(); // upper = "HELLO"
   String lower = str.toLowerCase(); // lower = "hello"
   ```

   **b. Replacing Characters**
   ```java
   String str = "Hello";
   String replaced = str.replace('e', 'a'); // replaced = "Hallo"
   ```

   **c. Splitting String by Delimiter**
   ```java
   String str = "1,2,3";
   String[] parts = str.split(","); // parts = {"1", "2", "3"}
   ```

   **d. Trimming Whitespace**
   ```java
   String str = " Hello ";
   String trimmed = str.trim(); // trimmed = "Hello"
   ```

   **e. Converting String to Char Array**
   ```java
   String str = "Hello";
   char[] chars = str.toCharArray(); // chars = {'H', 'e', 'l', 'l', 'o'}
   ```

### 9. Binary Search
   **a. Searching in a List**
   ```java
   List<Integer> list = Arrays.asList(1, 2, 3, 4, 5);
   int index = Collections.binarySearch(list, 3); // index = 2
   ```

   **b. Searching in a Custom Object Array**
   ```java
   class Person implements Comparable<Person> {
       int age;
       // Constructor and compareTo method
   }
   Person[] people = // ...
   int index = Arrays.binarySearch(people, new Person(25));
   ```

   **c. Searching in Descending Order Array**
   ```java
   Integer[] arr = {5, 4, 3, 2, 1};
   int index = Arrays.binarySearch(arr, 3, Collections.reverseOrder()); // index = 2
   ```

   **d. Searching for Insertion Point**
   ```java
   int[] arr = {1, 3, 5};
   int index = Arrays.binarySearch(arr, 4); // index = -3 (insertion point is 2)
   ```

   **e. Searching in a 2D Array**
   ```java
   // Implement custom binary search for 2D array
   ```

### 10. Recursion
   **a. Fibonacci Sequence**
   ```java
   public int fibonacci(int n) {
       if (n <= 1) return n;
       return fibonacci(n - 1) + fibonacci(n - 2);
   }
   ```

   **b. Sum of Array Elements**
   ```java
   public int sum(int[] arr, int n) {
       if (n <= 0) return 0;
       return sum(arr, n - 1) + arr[n - 1];
   }
   ```

   **c. Reversing a String**
   ```java
   public String reverse(String str) {
       if (str.isEmpty()) return str;
       return reverse(str.substring(1)) + str.charAt(0);
   }
   ```

   **d. Tower of Hanoi**
   ```java
   public void towerOfHanoi(int n, char from, char to, char aux) {
       if (n == 1) {
           System.out.println("Move disk 1 from " + from + " to " + to);
           return;
       }
       towerOfHanoi(n - 1, from, aux, to);
       System.out.println("Move disk " + n + " from " + from + " to " + to);
       towerOfHanoi(n - 1, aux, to, from);
   }
   ```

   **e. Generating Permutations**
   ```java
   public void permute(String str, int l, int r) {
       if (l == r) {
           System.out.println(str);
           return;
       }
       for (int i = l; i <= r; i++) {
           str = swap(str, l, i);
           permute(str, l + 1, r);
           str = swap(str, l, i); // Backtrack
       }
   }
   public String swap(String str, int i, int j) {
       char[] chars = str.toCharArray();
       char temp = chars[i];
       chars[i] = chars[j];
       chars[j] = temp;
       return String.valueOf(chars);
   }
   ```

These examples cover a wide range of common tasks and can be used as building blocks in solving more complex problems, especially in coding interviews and competitive programming.
