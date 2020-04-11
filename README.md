# PostYourAds
A business owner will post ads using an android app, those posts will be structured in a back-end server 
using a database like SQLite (check 'Note 1' below), then the client using his own Android app (which should be available in the Google Play Store) 
will see the posts by getting the structured info from the backend server.
We are making this app to sell it to business owners.

I will be posting some videos in this playlist : https://www.youtube.com/playlist?list=PLy0zBDiH3sw7SwZuAb5_Vm6H57fP1ig0b

If you want to add some videos to the playlist go ahead using this link : https://www.youtube.com/playlist?list=PLy0zBDiH3sw7SwZuAb5_Vm6H57fP1ig0b&jct=SZce7nulLhHpc0u_1P9e1V2SekNlYg

Note 1 : I think a set of files in the backend server instead of a database can be a good idea, especially that we don't know in advance the content of "item_detail". Each file will represents an "item" (in terms of "Android") and inside each file there can be a structure.

Helping conditions :
There won't be many files, so we can do a simple search in the folder containing the files.

Anyway, I will keep it with the SQLite database, because the structure of each table (referencing an 'item') is only made of a series of posts. I will be using "auto-increment" in case the administrator deleted an item, so we keep the chronological order.
