# STRINGS:

Strings are widely used in C++ ,Sequence of characters:
WE HAVE 2 WAYS TO CREATE STRINGS AND USE THEM:
1.BY CREATING A CHARACTER ARRAYS ,TREAT THEM AS STRING.
2.BY CREATING A STRING OBJECT

char str[50]="ruparani thupakula"

User input : char str[50]
             cin>>str;
             
             but it is ineffecinet method cin is delimter means it doesnot consider space eg: rupa is good  output: rupa //after space it skips
             use  get
             cin.get(str,50); //50 is size 
"\0 " TERMINATES SIZE RUPA\0RANI GIVES OUTPUT:RUPA
2.String str="rupa rani";//DMA also if string s='a' // gives error cant compatable to typecasting to char
    ***no size considered n in string obj 
   user input:
   use *getline(cin,str);
   
   
   
   STRINGS OPERATIONS:
   1.ACCESSING
   2.CONCATATION:(+,.append(),strcat()
      1. STR1 = STR1+STR2
      2.STR1.APPEND(STR2)
      3.strcat(str1,str2)
   3.COMPARISON
     1.strcmp(str1,str2) //3 cases 
     ***if str2>str1 returns pos val  
     str2<str1 returns neg val;
     == return 0
     2.COMPARE 
     str1.compare(str2)
     3.RELATIONAL : ==, >=, <=
     ***str1==str2
   
   Find char which occurs max in a string
   
   
  
