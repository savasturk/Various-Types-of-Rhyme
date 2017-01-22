# Various-Types-of-Rhyme
Write a program that finds the type of rhyme of the poem (string array).

Various Types of Rhyme 
- Radif
- Rhyme
- Head Rhyme  


Radif    (Kelime Halindeki Redifler)

All lines must end with the same word(s).

Example 
string[] poem = {"Koyun verdi kuzu verdi süt verDi", 
                 "Yemek verdi ekmek verdi et veRdi", 
		    "Kazma ile dövmeyince zor vErdi"}
Output: Repetition:  verdi,

        Type:  Radif

Example 
string[] poem = {"Doğru söylerim halk razı değil",
                 "Eğri söylerim sen razı değil",
                 "Program yazmaya ben razı değil",
                 "Bahane uydurmaya kim razı değil",
                 "Daha fazla yazmaya herkes razı değil"}
Output: Repetition:  razı değil
        Type:  Radif

Example 
string[] poem = {"Zannetme ki şöyle böyle bir söz", 
                 "Gel sen dahi söyle böyle bir söz", 
		    "Güzel yüzden ne şöyle böyle bir söz", 
		    "Ne böyle kuru, sert böyle bir söz"}
Output: Repetition:  böyle bir söz
        Type:  Radif


Rhyme  (Kafiye)
A rhyme is a repetition of the same letter(s) in one, two or more words in the final syllables of all lines in poems and songs.

Example:
string[] poem = {"The evening hymn that sorrow", 
                 "We promised love tomorrow", 
                 "I am an orrow",
		    "Now pride and love will borrow", 
		    "It will be good morrow"}
Output: Repetition:  orrow
        Type:  Rhyme

Example:
string[] poem = {"One morning you will look in vain",
                 "My smile of delicate disdain", 
    		    "one touch. . . and then again",  
    "Like ink the color red, I stain", 
    "the hearts of those whose love I drain", 
    "and then she leaves when I remain", 
    "Perhaps she sometimes ignites the drifting tallgrass plain",
    "rainbows blazing an arc over sparkling rain", 
    "Perhaps she burns across diamond ice in glacial mountain",
    "heartbroken she wondered how long the pain", 
    "Her face was smooth as porcelain"}
Output:  Repetition: ain
         Type:  Rhyme      


Head Radif  (Baş Redif) 

Radif at the beginning of all lines.

Example:
string[] poem = {"Elmas için bilenmeden keskin derler",
                 "elmas daha keskin benim bilgilim, asilim, ışığım"}
Output:  Repetition: elmas
         Type:  Head Radif



Head Ryhme  (Baş Kafiye) 

Ryhme at the beginning of all lines.

Example:

string[] poem = {"kök kalık teg yuklunmaksız azsız suksuz",
                 "körgülüg neñ uşik ekşer tapgulugsuz",
                 "körser sizni yig yörügçe körmeksizin",
                 "körür olar kirtü arıg burkanlarıg"}
Output:  Repetition: kö
         Type:  Head Rhyme



More than One Types 

Example:
string[] poem = {"Közlerine kanar kanar giderim",
    "Gözlerine yanar yanar giderim", 
    "Sözlerini anar anar giderim", 
    "Anar giderim"}
Output:  Repetition: giderim
         Type:  Radif

         Repetition:  anar 
         Type:  Rhyme 

Example:
string[] poem = {"Zannetme ki şöyle böyle bir söz", 
                 "Gel sen dahi söyle böyle bir söz", 
		    "Güzel yüzden ne şöyle böyle bir söz", 
		    "Ne böyle kuru, neyle böyle bir söz"}
Output: Repetition:  böyle bir söz
        Type:  Radif
        Repetition:  yle
        Type:  Rhyme

Example: 
string[] poem = {"I do not like three eggs and ham",
                 "I do not like them Sam I am",
                 "I do not like them in a boat",
                 "I do not like them in a goat",
                 "I do not like them in a house",
                 "I do not like those mouses"}
Output:  Repetition:   I do not like
         Type:  Head Radif 
                  Repetition:   th
         Type:  Head Rhyme 


Example: 
string[] poem = {"I do not like three eggs tand boat",
                 "I do not like them in sand boat"}
Output:  Repetition:  I do not like
         Type:  Head Radif       
         Repetition:  th
         Type:  Head Rhyme
         Repetition:  boat
         Type:  Radif       
         Repetition:  and
         Type:  Rhyme

