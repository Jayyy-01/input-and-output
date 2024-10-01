# input-and-output
***MS Dhoni aged X years, is a Cancerian, born with very strong Mars in his birth chart. Notably, Mars is the ruling planet for sports. Write a program to get the age of Dhoni as an integer and display the same.***
a=int(input())
print("Age of Dhoni is",a)

***After Dhoni made it to the pinnacle of Success as Indian Captain, Mr. Banerjee was once invited by the Media to recall his association with Dhoni. Mr. Banerjee quoted one important moment that complemented the traits of Dhoni. It was when he approached Dhoni and asked him if he would play cricket for the school team saying "Will you be a wicketkeeper?" and was taken aback by Dhoni's confident reply "I will if I get a chance". Write a program to display the answers of Dhoni that impressed his master.***
p=input("Banerjee's Question:\n")
r=input("Dhoni's Reply:\n")
print("For Banerjee's Question \"{}\" Dhoni's Confident reply was \"{}\"".format(p,r))

***It was in the 1997-98 season that Ranchi saw the rise of the Captain Cool in the interschool trophy between DAV Jawahar Vidhya Mandir and Kendriya School. It was in that match Dhoni convinced Banerjee to be the opener and justified it with a double century.***

def display_match_details():
    # Input details for Team 1
    print("Team 1:")
    team1_name = input("Team Name:\n")
    team1_score = input("Score:\n")
    team1_overs = input("Overs played:\n")
    # Input details for Team 2
    print("Team 2:")
    team2_name = input("Team name:\n")
    team2_score = input("Score:\n")
    team2_overs = input("Overs played:\n")  
    # Displaying match details
    print("Match Details:")   
    # Details for Team 1
    print("Team 1:")
    print(f"Name: {team1_name}")
    print(f"Score: {team1_score}")
    print(f"Overs played: {team1_overs}") 
    # Details for Team 2
    print("Team 2:")
    print(f"Name: {team2_name}")
    print(f"Score: {team2_score}")
    print(f"Overs played: {team2_overs}")
display_match_details()


