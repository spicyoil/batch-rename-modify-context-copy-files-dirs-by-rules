# batch rename/modify context/copy files/dirs by rules
#  

#change_contents_script.py  #used only for files
#usage: .py target_keyword  replace  newword oldword  
#usage: .py target_keyword  delete   newword   
  
  
#change_name_script.py	    #used for files and dirs
#usage: .py target_keyword  replace  newword oldword   
#usage: .py target_keyword  delete   oldword   
#usage: .py target_keyword  add      newword   
  
#copy_file_script.py    #used only for dirs
#usage: .py target_keyword  replace  newword oldword   
#usage: .py target_keyword  delete   oldword  
#usage: .py target_keyword  add      newword   
  
#Be careful I only test them in Python2  
#All scripts only works on current directory  
#target_keyword :is used to search the files/dirs which match  
#add: can only to add string in the end
#  
