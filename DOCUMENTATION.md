## ```Class priorityqueue (Object)```

Available functions for ```priorityqueue```;
* priorityqueue.length()
  
Returns an integer of the length of the priorityqueue.
* priorityqueue.time()

Returns how long it will take to get into the main server.

## ```Class userstats (Object)```
Available functions for ``userstats`` (all require a *user* kwarg);

**NOTE:** All of the functions in the class userstats return an integer except userstats.uuid().

* userstats.kills()
  
Returns the amount of kills the user has dealt.
* userstats.deaths()
  
Returns the amount of deaths the user has had.
* userstats.joins()
  
Returns the amount of joins the user has had.
* userstats.leaves()
  
Returns the amount of leaves the user has had.
* userstats.id()
  
Returns the ID of the user in the api.2b2t.dev database.
* userstats.adminlevel()
  
Returns the adminlevel of the user (with 0 being normal user and 1 being administrator.)
* userstats.uuid()

Returns the UUID of the user.

## ```Class lastdeath & lastkill (Object)```

Available functions for ``lastdeath & lastkill`` (all require a *user* kwarg);

**NOTE:** Lastdeath and Lastkill functions are the same.
* lastdeath.id() or lastkill.id()
  
Returns the user's ID in the api.2b2t.dev database.
* lastdeath.datetime() or lastkill.datetime()
  
Returns the day and hour of the user's last death or their last kill.
* lastdeath.message() or lastkill.message()

Returns the user's last death message or their last kill message.

## ```Class normalqueue (Object)```
Available functions for ```normalqueue```:
* normalqueue.length()

Provides the current length of the non-priority queue. Returns an integer.

## ```Class serverstats (Object)```
Available functions for ```serverstats```;
* serverstats.uptime()

Provides the current uptime of 2b2t. Returns a string.
* serverstats.tps()
  
Provides the current TPS of 2b2t. Returns a integer.
* serverstats.totalqueue()
Provides the length of the total queue of 2b2t (priorityqueue and normalqueue combined for convenience.) Returns an integer.

## ```async def lastseen```
Provides the time a 2b2t user was lastseen. Returns a string.