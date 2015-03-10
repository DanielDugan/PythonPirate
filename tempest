import urllib
def read_text():
  quotes = open(r"E:\tempest\tempest.txt")
  #Save a text file on your local machine and link the path
  contents_of_file = quotes.read()
  #print(contents_of_file)
  quotes.close()
  check_pirate(contents_of_file)

def check_pirate(text_to_check):
  connection = urllib.urlopen("http://isithackday.com/arrpi.php?text="+text_to_check)
  output = connection.read()
  print(output)
  connection.close()

read_text()

#sample Output:

#Hell be empty and all ye devils be here. 
#William Shakespeare, Thar Tempest

#What's past be prologue. 
#William Shakespeare, Ye Tempest

#We be such stuff as dreams be made on, and our little life be rounded with a sleep. 
#William Shakespeare, Thar Tempest
