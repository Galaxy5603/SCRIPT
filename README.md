-------------------------{|DiscordServer|}--------------------
------------------{|https://discord.gg/2yDHqwwvUy|}--------------------
-------------------------{|DiscordServer|}--------------------



--[[
  
  -------------------------[Moveset for each damage]-------------------------------
Or this one:
  
Move1 = "Deadly Dance" 
Move2 = "Anger Rush"
Move3 = "Meteor Crash"

And for ki moves i suggest use:

Move1 = "Blaster Meteor"
Move2 = "Chain Destructo Disk"

And for big melee moveset i suggest this one:

]]--

--[[









░██████╗░░█████╗░██╗░░░░░░█████╗░██╗░░██╗██╗░░░██╗
██╔════╝░██╔══██╗██║░░░░░██╔══██╗╚██╗██╔╝╚██╗░██╔╝
██║░░██╗░███████║██║░░░░░███████║░╚███╔╝░░╚████╔╝░
██║░░╚██╗██╔══██║██║░░░░░██╔══██║░██╔██╗░░░╚██╔╝░░
╚██████╔╝██║░░██║███████╗██║░░██║██╔╝╚██╗░░░██║░░░
░╚═════╝░╚═╝░░╚═╝╚══════╝╚═╝░░╚═╝╚═╝░░╚═╝░░░╚═╝░░░










]]--



Move1 = "Blaster Meteor"
Move7 = "Chain Destructo Disk"


Settings = {
    Earth = false; -- True to auto on earth, false to auto on queue (Recommended if you bug in queue)
    AntiLeach = false; -- If it exceeds the limit of people, rejoins you
    PeopleAllowed = 1; -- Number of people allowed in broly
    AutoPunch = true;  -- Auto Punches (Left Click) if you ran out of ki
    DoubleFreeze = false;  -- Freezes double exp
    TeamDamage = false;  -- Makes you be able to kill other people in broly
    LateTransform = true;  -- For androids, transforms when ki is at 70%
    LateTransform2 = false; -- For other races, transforms when ki is at 85% (Only h type form)
    Promote = true;  -- Promotes my discord
    forms = true;  -- turn this on for forms, turn off for androids
    RejoinTime = 350;  -- rejoins in broly if this time is exceeded
    GrabChecker = 300;  -- time it takes for broly to be last form, rejoins you if hes not by then
    AnimateFreeze = true;  -- Breaks your animator (if you have forms on you can't use this)
    invis = false;  -- Makes you invisible or not (Queue, Earth)
    waittime = 0;  -- The time waited before the script loads
    ChargeTime = 0,5; -- The time it takes to charge (Recommended = 3.5 seconds)
}


loadstring(game:HttpGet("https://raw.githubusercontent.com/Galaxy5603/Auto-Broly/main/Auto%20Broly%20Galaxy%20V16.lua"))()
