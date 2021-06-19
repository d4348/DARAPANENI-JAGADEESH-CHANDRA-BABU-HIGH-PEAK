# DARAPANENI-JAGADEESH-CHANDRA-BABU-HIGH-PEAK
d={'fitbit Plus':7980,'IPods':22349,'MI Band':999,'Cult Pass':2799,'Macbook Pro':229900,'Digital Camera':11101,'Alexa':9999,'Sandwich Toaster':2195,'Microwave Oven':9800,'Scale':4999}
values=list(d.values())
values.sort()

https://user-images.githubusercontent.com/51988851/122642732-86c73a80-d129-11eb-854b-80b5e21e6329.mp4



https://user-images.githubusercontent.com/51988851/122642768-acecda80-d129-11eb-892f-59de1168bc7e.mp4


n=int(input())
SUM=values[-1]
for i in range(len(values)-n+1):
    Sub_list=[]
    Sub_list=values[i:i+n]
    if((Sub_list[-1]-Sub_list[0])<SUM):
        SUM=Sub_list[-1]-Sub_list[0]
        Final=Sub_list
print("Number of the employees: {}".format(n))
for result in Final:
    for key,value in d.items():
        if(result==value):
            print("{}: {}".format(key,value))
print("And the difference the chosen goodie with highest price and lowest price is {}".format(SUM))

