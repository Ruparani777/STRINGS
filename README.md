# STRINGS:

Strings are widely used in C++ ,Sequence of characters:
WE HAVE 2 WAYS TO CREATE STRINGS AND USE THEM:
1.BY CREATING A CHARACTER ARRAYS ,TREAT THEM AS STRING.
2.BY CREATING A STRING OBJECT

char str[50]="ruparani thupakula"

User input : char str[50]
             cin>>str;
             
             but it is ineffeiceinet method cin is delimter means it doesnot consider space eg: rupa is good  output: rupa //after space it skips
             use  get
             cin.get(str,50); //50 is size 
"\0 " TERMINATES SIZE RUPA\0RANI GIVES OUTPUT:RUPA
2.String str="rupa rani";//DMA
    ***no size considered n in string obj 
   user input:
   use *getline(cin,str);
   
   
  
