QAE / SDET Take Home Assignment Answer

1. Convert the given binary number into decimal.
Examples below
Input 111
Output 7

String s1 = new String("111");
for ( int i = 0; s1.lengh; i++)
{
i = i + s1 * 2;
}
System.out.println("Result Output is: " + i);  //  Result Output Number

---------------------------------------------------------------------------

How would you prioritize the following work? Answer

1. Build a new web app interface
2. Fix CSS display issue in front-end code
3. Fix JavaScript bug in front-end code
4. Upgrade the database
5. Fix bug with concurrency in server code

----------------------------------------------------------------

Automation Engineer Take Home Assignment Answer

Given: A dictionary's word list and two words beginWord and endWord. Task: Find the length of the shortest transformation sequence from beginWord to endWord. Also: 1) Only one letter can be changed at a time, and 2) Each transformed word must exist in the word list.
Input: Dictionary = {POON, PLEE, SAME, POIE, PLEA, PLIE, POIN}, start = TOON, target = PLEA 
Output: 7 
Explanation: TOON – POON – POIN – POIE – PLIE – PLEE – PLEA 
Input: Dictionary = {ABCD, EBAD, EBCD, XYZA}, start = ABCV, target = EBAD 
Output: 4 
Explanation: ABCV – ABCD – EBCD – EBAD

	Scanner inputDictioanary = new Scanner(System.in); // Create a Scanner object for Dictionary
	Scanner inputStart = new Scanner(System.in);       // Create a Scanner object for Start
    String start = inputStart.nextLine(); // Read user input start word
	Scanner inputTarget = new Scanner(System.in);      // Create a Scanner object for Target
	String target = inputTarget.nextLine(); // Read user input input target word
	int output = inputDictioanary.nextInt();  // Read user input for how many words
			    
	    for(int i=-1;i<output;i++)
	    {
	        String dictionary = inputDictioanary.nextLine();
	        str[i]=dictionary;
			if equal(str[i] = 
	    }
	    
		String str[] = new String[output];
		int targetlength = inputTarget.lengh(); // Lenght of Target word 
		String[] explanation = new String[output];
		int ResultOutput;
		
		for(string j : target) // Target String Search
		{
			string search = j;
			
			for(int k = 0; k < targetlength-1; k++)
			{
				
			if (str[i].equalIgnoreCase(search) ;
			{
				ResultOutput = ResultOutput + 1;
			}
		}

	    for(int i=0;i<output;i++)  // Filling output Explanation Array
		{
		System.out.println("Explanation is: " +  str[i]);  // Output Explanation Array
		
		}
		System.out.println("ResultOutputExplanation is: " + start + str[i] + target);  // Output Explanation Array
	    System.out.println("ResultOutput is: " + resultOutput);  //  Result Output Number
		
----------------------------------------------
		
