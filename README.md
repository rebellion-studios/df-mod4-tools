# df-mod4-tools

## Exercise 1

I downloaded the NSRL hash database from the provided link. Then I went to ```Tools``` and then ```Options``` and then ```Hash Sets``` and then imported the database.

[IMAGE_GOES_HERE]




## Exercise 2

This allows you to view file types by exensions and then tag them. You can then generate a report in excel based on those files. The hashes can then be copied into Autopsy to create a database of selected files.

excel.png

autopsy-1.png

autopsy-2.png

autopsy-3.png




## Exercise 3

This had to have some adjusting. The book said to go to offset 1FF, but the close offset available was 1F0, which didn't seem to make that big of a difference.

The books said to go to ```Tools``` and then ```Compute Hash```, but it was actually under ```Generate Checksum```. The MD5 results, which is actually my one of my favorite encryption methods, is inside the ```quotes-md5.txt``` file.

[ADD_IMAGES_HERE]


## Exercise 4

I wasn't able to figure out how to load the file and shift the bits with Autopsy. I found a program called Hex Workshop. I shifted the bits to the right 2 times. But shifting thing 2 times to the left did nothing right, so I started again. This time I shifted everything to the left 2 times and then back to the right 2 times. But again things did not appear how they should be.

Then I shifted things over (See what I did there?) to the updated exercise. Things went a lot smoother. It's a shame that Hex Workshop and WinHex didn't work for these. Old and new files have been kept.

[ADD IMAGES HERE]



## Bonus

At first I tried to download a program that could do the work. But I couldn't find any good ones. Then I searched for an online generator and I found https://crackstation.net/. I then pasted the hashes, not expecting much. Seconds later I recieved the passwords and I saw the values of 783425, 783436, 783457. I then decided to try it myself. I couldn't get the website to work when I encrypted ```Barbie 2023```, it only worked with `2023`. This website was able to crack the hash of ```d398b29d3dbbb9bf201d4c7e1c19ff9d43c15fd45a0cec46fbe9885ec3f6e97f```, but not ```d1881d34a9bb289b7ab57204061813660a6b44886578c60cdac8d7563478229b```.

|                               Hash                               | Password |
|------------------------------------------------------------------|----------|
| 9e89895d350e5fdac013006b2acb067f8516149cdf7e952b021ff0326718ab70 |   783425 |
| af95a5393589cace29a63eead5328f1647a8bc62b5ef18b023c574484a877ced |   783436 |
| 30fc150e7c8b42dd86b1bb6e67ee256be8230969bb37cc111749e87af383ae82 |   783457 |

[ADD_IMAGES_HERE]

