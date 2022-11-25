# Pyspark_with_large_txt_file
How easy is it to read large text files with pyspark? In this repository I show you some source codes that you can use to practice python with spark and text files.

1) For this example, I'll use these text files found in the "1_input" folder:

![image](https://user-images.githubusercontent.com/31372472/204044929-10ac1d11-b0a9-4353-b06f-88616c16279f.png)

2) Both files are large, not because of the number of rows but because of the number of characters per row:

![image](https://user-images.githubusercontent.com/31372472/204045080-e1effbb4-cedc-4f2c-b1f2-84905a5fd443.png)

![image](https://user-images.githubusercontent.com/31372472/204045314-e52558cb-839a-4700-9198-d57679f252e6.png)

3) I want two data from these files, the supply number and the flag if this supply has digital delivery:

* The supply number is in position 2 and has 7 characters.

![image](https://user-images.githubusercontent.com/31372472/204047601-04e2b14d-94f6-41f9-a3a9-9341d2f0d6b2.png)

* The "digital delivery" flag is at position 13 337 and has 1 characters.

![image](https://user-images.githubusercontent.com/31372472/204048589-e746a5c1-f3a5-4aef-9db5-17c0d5844bc1.png)

4) To upload these files and merge both, I'll be using Python and Spark.

![image](https://user-images.githubusercontent.com/31372472/204048743-02e25e87-ce37-473c-a333-3a1725f274eb.png)
