# ASCII_VALUES
ascii_dict = {} #EMPTY DICTIONARY
for i in range(ord('a'), ord('z')+1): #USING FOR LOOP AND TAKING RANGE OF ASCII VALUES UPTO a-z
     ascii_dict[chr(i)] = i #updating into ascii_dict 
print(ascii_dict) # printing the values
