import random
def display(board):
     print(f'''
           {board[7]}|{board[8]}|{board[9]}                7 | 8 | 9
           ---+---+---                  ---+---+---
           {board[4]}|{board[5]}|{board[6]}    Positions-> 4 | 5 | 6
           ---+---+---                  ---+---+--- 
           {board[1]}|{board[2]}|{board[3]}                1 | 2 | 3
     ''')
def valid_input(): 
    while True:
        pos = input("Enter position:")
        if pos != '':
           if int(pos) in range(1,10):
              pos=int(pos)
              break
              print('not valid position\n')
        else:
         print('Thank u for playnig tic toc  toe!')
         exit()
    return int(pos)    
    


def valid_pos(turn,board): 
    print(f'{turn} chance')
    pos = valid_input()
    while True:
        if board[pos] =='   ':
            board[pos]=turn
            break
        else:
          print('cannot Overwrite,plz select new loc') 
          pos = valid_input()
     
def check(board):
    check = 0
    #row
    if  board[1] ==board[2] == board[3] !='   'or\
        board[4] ==board[5] == board[6] !='   'or\
        board[7] ==board[8] == board[9] !='   ':
        check=1
    #col
    elif board[1] ==board[4] == board[7] !='   'or\
         board[2] ==board[5] == board[8] !='   'or\
         board[3] ==board[6] == board[9] !='   ':
         check=1   
    #diag
    elif board[1] ==board[5] == board[9] !='   'or\
         board[3] ==board[5] == board[7] !='   ':
            check=1                           

def userInput(board,symbol):
    sym1, sym2 = symbol[random.randint(0,1)]
    print(f'({sym1} is goint first\n\n')
    display(board)
    for i in range(9):
        if i%2==0:
            turn=' '+sym1+' '
            valid_pos(turn,board)
        else:
            turn=' '+sym2+' '
            valid_pos(turn,board)
        display(board)
        if i>=4:
                if check(board):
                   display(board)
                   print(f"'{turn}'won'")
                   break
        if i == 8:
             print("none won,Its a Tie")    





def game():
    board =["just to adjust loc :)",'  ','  ','  ','  ','  ','  ','  ','  ','  ']
    symbol =[('x','0'),('0','x')]
    while True:
     marker  = input('\nEnter your Marker')
     if marker =='x' or marker == '0':
        userInput(board,symbol)
        break
    else:
        print('wrong marker(x,0) please enter again.\n')

def main():
    again ="Y"
    while again =="Y":
        print('press[space]for input whenever you want to stop the game')
        game()
        again = input("press 'Y/y' to play again?:").upper()
main()


