# gsheets-strava-setup

1. Login to [Strava](https://www.strava.com/login).
2. Visit your Strava settings.  
![image](https://user-images.githubusercontent.com/3951143/187322535-d2c40801-2fba-44b5-bea6-e479e306d014.png)
3. Enable "Health-Related Data" ![image](https://user-images.githubusercontent.com/3951143/187322667-84f74e93-2c9a-4161-b492-f0487db8d23d.png)
4. Go to your log sheet and select the tab with your name. ![image](https://user-images.githubusercontent.com/3951143/187323091-a3d2922c-abc7-4ab9-ab06-fe4c6b7ea2ad.png)
5. Click "Sync Current Tab" in the Strava dropdown. ![image](https://user-images.githubusercontent.com/3951143/187323365-f1d1a3f1-b17e-4b60-88c9-0ce91e923ffc.png)
6. An authorization prompt will be displayed. Click "Continue" ![image](https://user-images.githubusercontent.com/3951143/187323761-050f57da-5ec6-439a-867c-3f59c226ca8d.png)
7. Select your Google account ![image](https://user-images.githubusercontent.com/3951143/187323826-cc1caaba-9160-458f-94b2-87fc710fd98d.png)
8. Click "Advanced" ![image](https://user-images.githubusercontent.com/3951143/187323920-02a6a37c-2439-4bb8-89a5-30eb10c9f23e.png)
9. Click "Go to Strava Sync (unsafe)". The script we wrote to pull Strava data into sheets has not been approved by Google which is why this step is necessary. (You will only need to do this once). ![image](https://user-images.githubusercontent.com/3951143/187324130-e10dd399-3f5e-491e-ae78-393605a65de8.png)
10. Click "Allow" ![image](https://user-images.githubusercontent.com/3951143/187324185-01af12ce-64c9-45d8-81b9-b1d3cfda407c.png)
11. Now click "Sync Current Tab" again.
12. Click "Continue to Strava" ![image](https://user-images.githubusercontent.com/3951143/187324248-74378f93-d1bf-403c-a87d-a8327865ce63.png)
13. Click "Authorize" ![image](https://user-images.githubusercontent.com/3951143/187324305-e65e46ea-aca7-4219-a6c1-95401b3e225d.png)
14. You should see the text "Success! You can close this tab." if everything worked correctly. You can now close the tab and refresh the google sheets page.
15. Finally, click Strava -> "Sync Current tab" this time your Strava data should be imported to your google sheet tab.
