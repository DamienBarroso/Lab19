# Lab19
Ignore me I'm just a placeholder to study code for codereview

#Name: Damien Barroso
#Email: damien.barroso79@myhunter.cuny.edu
#Date: 10/8/2021
#This program determines how large of an influencer you are

peps = int(input("Enter your number of followers: "))

if peps < 0:
    print("Your influencer level is: Error")

if peps > 1000000:
    print("Your influener level is: Celebrity influencer")
elif peps <= 1000000 and peps > 500000:
    print("Your influener level is: Macro Influencer")
elif peps <= 500000 and peps > 100000:
    print("Your influener level is: Mid-Tier Influencer")
elif peps <= 100000 and peps > 10000:
    print("Your influener level is: Micro Influencer")
elif peps <= 10000 and peps > 1000:
    print("Your influener level is: Nano Influencer")
elif peps <= 1000 and peps >= 0:
    print("Your influener level is: Hyper Influencer")
