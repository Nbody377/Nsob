while not game:IsLoaded() and not game.Players.LocalPlayer do task.wait() end
getgenv().Stats = {-- Name, Rebcap, Statcap, Play Solo ONLY?
    {game.Players.LocalPlayer.Name, math.huge, math.huge, false}, 
    {game.Players.LocalPlayer.Name, math.huge, math.huge, false},
}
getgenv().WebHooks = {
    ["Stats"] = "webhook here", -- Do you want to log your stat gain progress?
    ["Rebs"] = "webhook here", -- Do you want to log your reb gain progress?
}
