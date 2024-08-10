# steam-showcase-game-collector
add any game to steam game collector 

to add any game to the steam showcase, change only the appid. If you want to add a purchase shop showcase, you need to change the purchaseid as well



Slot: 
`0 = first game
1 = second game
2 = third game
3 = fourth game`



```javascript
$J.post(g_rgProfileData.url + "ajaxsetshowcaseconfig", {
    appid: 359850,
    customization_type: 2,
    purchaseid: 0,
    slot: 0,
    sessionid: g_sessionID
});

