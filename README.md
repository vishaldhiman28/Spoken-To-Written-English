
# Spoken To Written

This is a Python module which can that can convert a paragraph of spoken english to written english.

 For example, "two dollars" should be converted to $2. Abbreviations spoken as "C M" or "Triple A" should be written as "CM" and "AAA" respectively.


## Installation:


  Please ensure that you have **updated pip3** to the latest version before installing spoken2written.
  
  You can install the module using Python Package Index using the below command.
   ```
   >>python3 setup.py install
   ```


## Usage:


**Correct one:**
   ```
    >>python3
	>>from spoken2written import sp2wr
	>>sp2wr.convert_sp_to_wr()
	>>
	[IN]:Enter Your paragraph of spoken english:
	
	Hi! My name is Bruce. I am a Programmer. I try to wake up before 6 A M. I always come home after 7 P M. I earn hundred 		dollars per day. My contact number contains double 5, quadruple 8, single 9 and triple 4. Recently, My weight got double 	 the weight of my friend whom I call C M. 
	
	[OUT]:The input Spoken English Paragraph: 
	
	" Hi! My name is Bruce. I am a Programmer. I try to wake up before 6 A M. I always come home after 7 P M. I earn hundred 	  dollars per day. My contact number contains double 5, quadruple 8, single 9 and triple 4. Recently, My weight got double    	       the weight of my friend whom I call C M. "
		
	 Converted Written English Paragraph: 
	 
	 " Hi! My name is Bruce. I am a Programmer. I try to wake up before 6 AM. I always come home after 7 PM. I earn $100 per 	    day. My contact number contains 55, 8888, 9 and 444. Recently, My weight got double the weight of my friend whom I      	       call CM. "
```
	
	
**Wrong One:**
    
    >>python3
	>> from spoken2written import sp2wr
	>> sp2wr.convert_sp_to_wr()

	[IN]:Enter Your paragraph of spoken english:
	Hi! My name is Bruce.I am a Programmer.I try to wake up before 6 A M.I always come home after 7 P M.I earn hundred 		dollars per day.My contact  number contains double 5,quadruple 8, single 9 and triple 4.Recently, My weight got double 		the weight of my friend whom I call C M.
	
	[OUT]:The input Spoken English Paragraph: 

	" Hi! My name is Bruce.I am a Programmer.I try to wake up before 6 A M.I always come home after 7 P M.I earn hundred 		dollars per day.My contact  numbe  number contains double 5,quadruple 8, single 9 and triple 4.Recently, My weight got 		double the weight of my friend whom I call C M."

	Converted Written English Paragraph: 

	" Hi! My name is Bruce.I am a Programmer.I try to wake up before 6 A M.I always come home after 7 P M.I earn $100 per 
	day.My contact numbe number contains 5,quadruple5,quadruple 8, 9 and 4.Recently4.Recently4.Recently, My weight got 		the weight of my friend whom I call CM."


## Note: 

   **For the Above input paragraph the incorrect output as a result of improper use of spaces after '.' and ','.  So currently 	  	you have to keep in mind while writing the paragraph to consider proper use of spaces. Because this is not an intelligence-	based program this is simple rule-based. I will keep being updating the rules so that it can cover maximum cases.**



## Bugs/Errors

   If you find any bugs/errors in the usage of above code, please raise an issue through  
   [Github](https://github.com/cyberdhiman/Spoken-To-Written-English)


## Here are some possible future functionalities that  can be covered in the future versions of the module:

1.   If the paragraph contains a money figure e.g. two million three thousand nine hundred and eighty-four then we may convert it to numbers as 2003984.

2. Handling of both American number system and Indian number system e.g. million, lakhs.

3.  Handling of Dates e.g. Today's Date is twenty-eight October two thousand twenty as Today's Date is 28-10-2020/2020-10-28.

4. Handling of Punctuation.

5. Handling of proper spaces after one sentance.


**Please, Feel free to connect if you have some ideas.**


## License


MIT License

Copyright (c) 2019 Vishal Dhiman  [Github](https://github.com/cyberdhiman/Spoken-To-Written-English)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
