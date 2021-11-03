# Word-Cloud-Zipfs-law-Map-Reduce
Pick a classic from Project Gutenberg.  Download the same as a text file. Find basic statistics related to the word occurence in the file.

1. First we will start dfs and yarn as shown below . 
> start-dfs,
>  start-yarn

![image](https://user-images.githubusercontent.com/37560890/140054918-a3fbc64f-b723-4b32-9001-82826ac0e144.png)

2. We are listing file directories in hdfs. In input folder we are having Gutenberg_data.csv (4gb).

![image](https://user-images.githubusercontent.com/37560890/140054986-f83f0c17-721b-44db-ba0b-eeef6317c59f.png)


3.  In 3rd step we will be running jar file and mapper program and reducer program.

![image](https://user-images.githubusercontent.com/37560890/140055194-0ece6e9d-d086-4634-98a7-8cb10ec543db.png)


4.  The whole process is done on gutenberg.cvs data (4gb).

![image](https://user-images.githubusercontent.com/37560890/140055476-b27bb319-b994-4188-8fcb-3a452444a293.png)


5.  As you can see below we got a word count file i.e. part-r-0000 file which consist of word and their frequency.

![image](https://user-images.githubusercontent.com/37560890/140055663-b14eb4ad-ded2-4786-9955-9b7211d2be7a.png)
