# Roblox-Replacer
Add replacer to your roblox game, make your life easier!

* **To add Replacer to your game there is a few things you need to do:**

1. buy & install the plugin link: [CLICK HERE!](https://www.roblox.com/library/14085310376/Replacer)
2. add the module to your game by clicking on: PLUGINS/REPLACER
3. now you have the Replacer module in your game!

* **Now when you have the module on your game you can start to learn how to use it:**

1. *Basic*:

first (basic) you need to create localscript, you must localscript in startgui you can't do it with a script.
now you need to get the module script from replicatedstorange by making the code:

```lua
local rep = require(game.ReplicatedStorage.Replacer)
```

now you can use the functions.

2. *Functions*:

the first function is Add with this function you can add
new replacements that you can use them:

```lua
rep:Add("name", "hi!!")
```

the name of this is what you need to get the replacement and
the hi!!! is the output, what you will get from the name.

now when you created a replacement you can use it from the get function:

```lua
print(rep:Get("name"))
```

this function will return the output of it, and im using it with print.

now when you add replacement and then get it and print what it get now if you want to change the output of the replacement you can set it with this function:

```lua
rep:Set("name", "new output")
```

in here i changed the name replacement output to "new output" and now everytime i try to get it it will get this new output.

the last function for now is txt, what this function do is doing the same get do but very more easy, because its inside text:

```lua
print(rep:Txt("the replacement: %name%"))
```

in here i was using the txt function inside print for it print the result, and what it doing is get the replacement by %% and you can add another text to it.

Overall it looks like this:

```lua
local rep = require(game.ReplicatedStorage.Replacer)


rep:Add("name", "hi!!")

print(rep:Get("name"))

rep:Set("name", "new output")

print(rep:Txt("the replacement: %name%"))
```


Except that you can create new replacements there is pre builded replacements.

3. *Replacements*:
here is all the replacements that pre builded.


**plr**:

%plr% - the player name

%plr_name% - the player name

%plr_id% - the player roblox id

%plr_fps% - the player current fps

%plrs% - the number of players in the server



**server**:

%server_plrs% - the number of players in the server

%server_max_plrs% - the max players the can be in the server



**game**:

%game% - the game name

%game_name% - the game name

%game_id% - the game id

more will added soon!


**So this is all you need to know about Replacer, more updates will added soon!**
