# Python-projects

import random


subjects= [
  "Scientists",
  "Researchers",
  "Experts",
  "Analysts",
  "Economists",
  "Politicians",
  "Doctors",
  "Engineers"
]


actions =[
  "discover",
  "develop",
  "analyze",
  "predict",
  "investigate",
  "debate",
  "treat",
  "design"
]


places=[
  "in the lab",
  "at the conferance",
  "in the field",
  "in the hospital",
  "in the office",
  "in the city",
  "in the university",
  "in the government"
]


while True:
  subject= random.choice(subjects)
  action= random.choice(actions)
  place= random.choice(places)
  
  headline= f"BREAKING NEWS: {subject} {action} {place}"
  print("\n" + headline)


  user_input= input("\nDO YOU WANT TO GENERATE ANOTHER HEADLINE?(yes/no)
").strip()
  if user_input == "no":
    break


print("\nThank you for using the headline generator. Have a great day!")

