# Figshare_wget_download
I see a lot of posts on forums asking about how to directly download figshare data without downloading and uploading. Just a helpful article to help you wget from figshare incase the file is large and you need it directly on cloud or cluster.

1. Once you are inside the figshare project page, you will see the download tab as attached below.

![{D2EB2CD4-C8A8-426E-B1C1-42FD8375231E}](https://github.com/user-attachments/assets/2cb1e779-93ee-4b40-a285-c35253304a27)

2. You would "Right Click" on the download button, and select "copy link address" (as attached below).

![{CC049322-C307-44FC-8DD6-EFFAA5F2FA73}](https://github.com/user-attachments/assets/a35062e8-75c5-4a64-a537-76010d75a188)

3. Then You would use this command on your Linux terminal:

"wget --content-disposition https://ndownloader.figshare.com/articles/xxxxxxxx/versions/x (your link)"
for example: "wget --content-disposition https://ndownloader.figshare.com/articles/29190726/versions/1"

It would be recommended to do this in a persistent terminal incase the download gets cancelled. 
