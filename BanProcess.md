# BanProcess (JI)

I prefer to use JI for a banwave.

Therefore JI is recomended

JI as banwave

1. Player gets caught hacking
    1.5. Player is added by staff
2. Player is added to JI's JDay (Judgement day)
    2.5. Staff are notified
3. JI Waits for a certain time.
4. Judgement day occurs
    4.5. One by one it bans all of the players with the configured JDay command.
        4.5.5. Brodcasts {Player} has been banned.

Code:

```yaml
prefix: '&8&l[&4&lGWEN&8&l] '
ban-timer: '&c%player% &7will be banned in 5 seconds. &cReason &7[&c%check%&7]'
alerts: '&c%player% &7failed &7[&c%check%&7] [&bVL%vl%&7] %tags%'
punish-commands:
- 'ba ban %player% gwen &8&l[&4&lGWEN&8&l]: &c(JI) Unfair Advantage! &7(%check%)'
- 'broadcast &8&l[&4&lGWEN&8&l]&c: (JI) &a%player% &chas been banned for &7(%check%)'
jday-added: '&c%player% &7was added to the jday list. &cReason &7[&c%check%&7]'
jday-command: ban %player% (JDay) %check%
autoban-cancel: '&7You canceled &c%player% &7autoban queue.'
jday-broadcast: '&3%player% &7has been removed permanently from the network.'
```

> NOTE: CODE WILL BE EDITED SOON.

In the perspective of a player:

ji says the wave is in a certain ammount of time.

players warp to court, jail, prison, or other structure and wait for JDay to occure.

JDAY occurs

Players are banned 1 by 1

players notice that all of the players that will be banned have 4 guardians floating above the suspects head.

> Note: spreading the players so the chunk dosent get too laggy would be smart. use the /spreadnear command i think.

the plyer explodes and the guardian goes away.

After the explosion goes away the player is GONE!

the player has been banned.

> Note: Animation warning below, please read!!!
> WITH MOBSTACKER INSTALLED, THE 4 GUARDIANS DO SPAWN BUT THEY GET COMBINDED TO ONE MOB INSTANTLY.
> YOU ONLY SEE ONE GUARDIN INSTEAD OF 4
> ALSO THE GUARDIAN DOSENT GO AWAY CAUSE IT IS A NEW DIFFERENT ENTITY.
> TRY AND MAKE YOUR LAG CLEARER BYPASS GUARDIANS
> LIST OF THINGS THAT MESS WITH GWEN ANIMATION:
> MOBSTACKER
> REACT
> CLEARLAG
> MOB REMOVING PLUGINS
> PLUGINS THAT HALT SERVER ACTIVITY
