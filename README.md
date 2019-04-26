# Text-summarization_NLP
Text Summarization is software for help us to understand the summary of the text like wikipedia ..

we will take a link like wikipedia then summarize the text then display the summary .

Impact :

        Summarization systems often have additional evidence they can utilize in order to specify the most important topics of document(s). For example, when summarizing blogs, there are discussions or comments coming after the blog post that are good sources of information to determine which parts of the blog are critical and interesting .
In scientific paper summarization, there is a considerable amount of information such as cited papers and conference information which can be leveraged to identify important sentences in the original paper.



How text summarization works :

Input document → Convert Paragraphs to Sentences → Text Preprocessing → Tokenizing the Sentences → Find Weighted Frequency of                 Occurrence     →  Replace Words by Weighted Frequency in Original Sentences → Sort Sentences in Descending Order of Sum


Text Summarization Steps :
1) we will take the Text as input
   Example :
   Fall down seven times, get up eight. Ease is a greater threat to progress than hardship. Ease is a greater threat to progress        than hardship


2) Convert Paragraphs to Sentences " then split the paragraoh into sentences "
   Example :
   Fall down seven times, get up eight
   Ease is a greater threat to progress than hardship 
   Ease is a greater threat to progress than hardship 
   
3) Text Preprocessing
   we need to remove all the special characters, stop words and numbers from all the sentences .
   Example :
   fall seven time get eight
   ease greater threat progress hardship
   ease greater threat progress hardship 
   
4) Tokenizing the Sentences
   We need to tokenize all the sentences to get all the words that exist in the sentences .
   Example :
   'ease', 'greater', 'threat', 'hardship', 'ease',
 
 
 5) Find Weighted Frequency of Occurrence
    we find the weighted frequency of occurrences of all the words
    
 6) Replace Words by Weighted Frequency in Original Sentences 
    he final step is to plug the weighted frequency in place of the corresponding words in original sentences and finding their sum
    Example :
    
    Sentence 	                     --->                         So, keep working
    Sum of Weighted Frequencies    --->                         1 + 0.20 = 1.20 
 	
    Sentence                       --->                          Keep striving 
    Sum of Weighted Freauencies    --->                          1 + 0.20 = 1.20 
 
  7) Sort Sentences in Descending Order of Sum
     The final step is to sort the sentences in inverse order of their sum. The sentences with highest frequencies summarize the   text. For instance, look at the sentence with the highest sum of weighted frequencies .
     
     
     
