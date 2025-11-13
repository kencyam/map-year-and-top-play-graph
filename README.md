This is an updated version of https://github.com/kcyam/osu_pp_and_year_comparer, which uses an outdated osu! apiv1. Since I have lost access to that github, I'm uploading the new version here.


You need Jupyter notebook to run this.


To use follow these steps:

1) Log into your osu! account
2) Under your profile on the top right, click on your avatar and go to your settings
3) Scroll until you reach the OAuth section. If you already have your own client click on Edit and remember the ClientID and Client Secret. If not, click "New OAuth Application" and type in a name inside "Application Name". Register application and then go to edit and get remember the ClientID and Client Secret. DO NOT SHARE THESE WITH ANYBODY.
4) Open the file in Jupyter Notebook
5) Locate the variables "USER" and "PASSWORD". Replace the placeholder values with your ClientID and Client Secret respectively
6) Locate the list object "user_ids". Inside the array, add user's userID.
7) Run every block in order
8) The last block shall graph the user's top scores at the end
