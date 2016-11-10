Tali Israeli- 301807756		
	
Information Retrievle Project:	
	
Go to folder scr -> open file name: hw2 ir - final	
	
* Libraries Installation :	
 1. Part I required a file that include stop words list.	
	"You can find this file in ""lib"" folder."
	"Also, run line ""nltk.download()"" in initializations cell for the first time you run this code."
	
* Executaion of the code - run the next cells according to this order:	
	
1. Initializations Cell	
	dir variable - please change this var to docuemnts' folder path in your computer. 
	queriesDir variable  - please change this var to result queries' path in your computer.
	resultDir variable - please change this var to result folder path in your computer.
 	
2. Function's defenitions that relate to Part I : 	
	#NAME?
   	#NAME?
	
"3. Part I Cell- this part go throw the documents in input folder according to ""dir"" variable,"	
   	analyze the lines in the documents: stemming and remove stop words and then create the index.
   	"In the end, the inverted index arr ( inverted_index ) is ready to use. "
	
4. Query Function 	
  	The function analyze the query: stemming and remove stop words.
  	Then it calculated the Similarity between the query and each doc. 
	
5. Run Query:	
  	The function get 1 query and return the top 20 relevant documents ranked accorfing to Similarity measure
	
6. getTop20	
  	The function read a query file and write to a result file for each query the top 20 relevant documents ranked according to the Similarity measure.
  	
7. Main loop - Part II:	
	run getTop20 function. 
	
the results will print in the text file according to resultDir variable. 	
