# Lab3


def textfile (name, file_path)
  
  try: 
    with open(file_path, "w") as file:
      file.write(name)
     print('File is complete')


fullname = "Ryan Plumb"

path? = "C:\Users\Ryan\Documents\OPS445\Lab3"
textfile(fullname, path)
