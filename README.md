# icewarp_unlimited_file_upload

first step:
login to your account and then change your profile picture.

second step:
capture request with burp suit.
https://github.com/networksecure/icewarp_unlimited_file_upload/blob/master/unlimi2.PNG

third step:
send request to intruder, and add posiotion like below.
https://github.com/networksecure/icewarp_unlimited_file_upload/blob/master/unlimit1.PNG

forth step:
start attack.

result:
Look at the responses, as you can see all of files has been uploaded and you can access the file.
the file upload location pattern is "upload_date-folder(random number)/file(random number)"
Look at below image.
https://github.com/networksecure/icewarp_unlimited_file_upload/blob/master/unlimited%20upload%20file-1%20-%20Copy.PNG
