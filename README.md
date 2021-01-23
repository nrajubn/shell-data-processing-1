# Shell-data-processing 

## Basic commands 
 
- ``` mkdir ``` creates a new directory
- ``` rmdir ``` deletes the specified empty directory
- ``` rm  ``` deletes a specified directory containing files
- ``` pwd ``` shows the current working directory
- ``` cat ``` displays the contents of file

## Command used to fetch data from url:

```  curl "https://towardsdatascience.com/introduction-to-apache-spark-207a479c3001" -o "data.txt" ```

## Command used to count unique words in a squential order:

``` tr ' ' '\12' < returnedfile | sort | uniq -c | sort -nr > result.txt ```  
- ``` tr ``` tranforms or deletes characters from strings  
- ``` sort ``` sorts  the contents of a file in a particular order  
- ``` uniq -c ```  returns the number of times a word is repeated  
- ``` sort -nr ``` option -n sorts numnerically and option -r sorts in reverse order  
