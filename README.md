def christmas_tree(x):
    for i in range(1,x+1):
        print((x-i)*' ','*'*(2*i-1))

        


 def check_letters(word1,word2):
    for letter in word1:
        if letter not in word2:
            return False
    else:
        return True
       
