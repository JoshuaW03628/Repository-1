---
toc: false
layout: post
description: The post for Dict./Title
categories: [markdown]
title: Formatting for Titles/Dictionary
---
# Format Code to Run This:
## Define an empty List called InfoDb
InfoDb = []

## Append to List a Dictionary of key/values related to a person and cars
InfoDb.append({
    "FirstName": "Josh",
    "LastName": "Williams",
    "DOB": "January 6",
    "Residence": "San Diego",
    "Email": "joshuawilliams52006@gmail.com",
    "Owns_Cars": ["2011-Nissan Versa"],
     "Favorite Games": ["Apex-Legends"]
})

## Append to List a 2nd Dictionary of key/values
InfoDb.append({
    "FirstName": "Ryan",
    "LastName": "Mcweeny",
    "DOB": "March 27",
    "Residence": "San Diego",
    "Email": "N/A",
    "Owns_Cars": ["Lamborghini"],
    "Favorite_Show": ["CocoMelon"]
})

## Print the data structure
print(InfoDb)


# Lets Make This Look Nicer

## given and index this will print InfoDb content
def print_data(d_rec):
    print(d_rec["FirstName"], d_rec["LastName"])  # using comma puts space between values
    print("\t", "Residence:", d_rec["Residence"]) # \t is a tab indent
    print("\t", "Birth Day:", d_rec["DOB"])
    print("\t", "Cars: ", end="")  # end="" make sure no return occurs
    print(", ".join(d_rec["Owns_Cars"]))  # join allows printing a string list with separator
    print()


## for loop iterates on length of InfoDb
def for_loop():
    print("For loop output\n")
    for record in InfoDb:
        print_data(record)

for_loop()
