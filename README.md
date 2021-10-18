local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("SHELL X HUBV1 beta", "LightTheme")

local Tab = Window:NewTab("Main")
local Section = Tab:NewSection("AutoFarmbeta")

Section:NewButton("on", "have a bug", function()
    _G.farm = true

Ms = "Bandit [Lv. 5]"
CFRAMEQUEST = CFrame.new(1063.775390625, 16.516618728638, 1535.3385009766)
while _G.farm do wait()
    pcall(function()
if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false then
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFRAMEQUEST
    wait(2)
local args = {
    [1] = "StartQuest",
    [2] = "BanditQuest1",
    [3] = 1
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
elseif game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true then
  for i,x in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
        for n,y in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
            if x.Name == Ms then
                if y.Name == Ms then
                     game:GetService'VirtualUser':CaptureController()
                    game:GetService'VirtualUser':Button1Down(Vector2.new(851, 158))
                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = x.HumanoidRootPart.CFrame * CFrame.new(0,5,10)
                     x.HumanoidRootPart.CFrame = y.HumanoidRootPart.CFrame
                    x.HumanoidRootPart.CanCollide = false
                    y.HumanoidRootPart.CanCollide = false
                    x.HumanoidRootPart.Size = Vector3.new(30,30,30)
                    y.HumanoidRootPart.Size = Vector3.new(30,30,30)
                    x.Humanoid:ChangeState(11)
                    y.Humanoid:ChangeState(11)
                    if sethiddenproperty then
                        sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
                    end
        end
    end
end
end
end
end)
end
spawn(function()
    pcall(function()
        while wait() do
            for i = 1,3 do
                if _G.farm == true then
                    game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
                end
            end
        end
    end)
end)
end)

local Section = Tab:NewSection("AutoFarmoff")

Section:NewButton("off", "ButtonInfo", function()
    _G.farm = false

Ms = "Bandit [Lv. 5]"
CFRAMEQUEST = CFrame.new(1063.775390625, 16.516618728638, 1535.3385009766)
while _G.farm do wait()
    pcall(function()
if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false then
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFRAMEQUEST
    wait(2)
local args = {
    [1] = "StartQuest",
    [2] = "BanditQuest1",
    [3] = 1
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
elseif game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true then
  for i,x in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
        for n,y in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
            if x.Name == Ms then
                if y.Name == Ms then
                     game:GetService'VirtualUser':CaptureController()
                    game:GetService'VirtualUser':Button1Down(Vector2.new(851, 158))
                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = x.HumanoidRootPart.CFrame * CFrame.new(0,5,10)
                     x.HumanoidRootPart.CFrame = y.HumanoidRootPart.CFrame
                    x.HumanoidRootPart.CanCollide = false
                    y.HumanoidRootPart.CanCollide = false
                    x.HumanoidRootPart.Size = Vector3.new(30,30,30)
                    y.HumanoidRootPart.Size = Vector3.new(30,30,30)
                    x.Humanoid:ChangeState(11)
                    y.Humanoid:ChangeState(11)
                    if sethiddenproperty then
                        sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
                    end
        end
    end
end
end
end
end)
end
spawn(function()
    pcall(function()
        while wait() do
            for i = 1,3 do
                if _G.farm == true then
                    game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
                end
            end
        end
    end)
end)
end)

local Tab = Window:NewTab("Teleport")
local Section = Tab:NewSection("Teleport to Starterisland")

Section:NewButton("Teleport", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(946.396484, 16.5166149, 1428.54102, -0.0332927071, -4.42573764e-08, 0.999445617, -4.84113132e-11, 1, 4.42803092e-08, -0.999445617, 1.42582701e-09, -0.0332927071)
end)

local Section = Tab:NewSection("Teleport to MiddleTown")

Section:NewButton("Teleport", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-698.071655, 7.85224533, 1559.16711, 0.971976697, 3.74573865e-08, 0.235077143, -4.1371532e-08, 1, 1.17186092e-08, -0.235077143, -2.11157172e-08, 0.971976697)
end)

local Section = Tab:NewSection("Teleport to Jungle")

Section:NewButton("Teleport", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1324.81079, 11.8530645, 492.504089, -0.950561523, 0, -0.310536355, 0, 1, 0, 0.310536355, 0, -0.950561523)
end)

local Section = Tab:NewSection("Teleport to Buggyisland")

Section:NewButton("Teleport", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1170.74316, 44.7520409, 3842.05664, 0.970839202, 5.36658966e-08, -0.23973158, -6.63443274e-08, 1, -4.4815863e-08, 0.23973158, 5.94138285e-08, 0.970839202)
end)

local Section = Tab:NewSection("Teleport to Desert")

Section:NewButton("Teleport", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(909.186157, 6.5132513, 4380.58252, -0.979714632, -1.68406054e-08, 0.2003977, -9.15892709e-11, 1, 8.35881551e-08, -0.2003977, 8.18741839e-08, -0.979714632)
end)

local Section = Tab:NewSection("Teleport to Snowisland")

Section:NewButton("Teleport", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1390.01794, 87.272789, -1347.60876, -0.199600711, -3.93440693e-08, -0.979877293, 1.92018632e-08, 1, -4.40634516e-08, 0.979877293, -2.76105663e-08, -0.199600711)
end)

local Section = Tab:NewSection("Teleport to Marineford")

Section:NewButton("Teleport", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4818.64404, 20.6519604, 4371.78076, 0.853140891, 0, -0.521680713, 0, 1, 0, 0.521680713, 0, 0.853140891)
end)

local Section = Tab:NewSection("Teleport to Skypiea1")

Section:NewButton("Teleport", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4695.72168, 845.277161, -1849.30481, 0.942552745, 0, 0.33405903, 0, 1, 0, -0.33405903, 0, 0.942552745)
end)

local Section = Tab:NewSection("Teleport to Skypiea2")

Section:NewButton("Teleport", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-7887.83545, 5545.49316, -380.958527, -0.000477724156, -6.86372985e-08, -0.999999881, 5.76642201e-08, 1, -6.86648534e-08, 0.999999881, -5.76970152e-08, -0.000477724156)
end)

local Section = Tab:NewSection("Teleport to Prison")

Section:NewButton("Teleport", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(5009.61572, 3.65196347, 739.075989, -0.00479308004, 9.31296569e-08, 0.999988496, 5.43943734e-08, 1, -9.28700103e-08, -0.999988496, 5.39486145e-08, -0.00479308004)
end)

local Section = Tab:NewSection("Teleport to Colosseum")

Section:NewButton("Teleport", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1477.56165, 7.38933945, -2937.54102, 0.748681664, -4.16919406e-08, 0.662929654, -1.05962474e-08, 1, 7.4857347e-08, -0.662929654, -6.30688533e-08, 0.748681664)
end)

local Section = Tab:NewSection("Teleport to Magma Village")

Section:NewButton("Teleport", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5254.56592, 8.59067631, 8451.16797, -0.356155008, 7.88511798e-08, 0.934427261, 7.19219528e-08, 1, -5.69715759e-08, -0.934427261, 4.69150905e-08, -0.356155008)
end)

local Section = Tab:NewSection("Teleport to Fishman island")

Section:NewButton("Teleport", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(61352.3828, 18.8707905, 1502.90942, -0.999073625, 2.99610892e-09, -0.043031659, 3.08991832e-09, 1, -2.11348894e-09, 0.043031659, -2.24449526e-09, -0.999073625)
end)

local Section = Tab:NewSection("Teleport to Fountain city")

Section:NewButton("Teleport", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(5072.36914, 4.50129032, 4158.08545, 0.574859381, 0, 0.818252444, 0, 1, 0, -0.818252623, 0, 0.57485944)
end)

local Tab = Window:NewTab("Players")
local Section = Tab:NewSection("Teleport")
 
--------------------
 
players = {}
 
for i,v in pairs(game:GetService("Players"):GetChildren()) do
   table.insert(players,v.Name)
end
 
Section:NewDropdown("Select Player", " ", players, function(abc)
    Select = abc
end)
 
 
Section:NewButton("Refresh", " ", function()
    table.clear(players)
for i,v in pairs(game:GetService("Players"):GetChildren()) do
   table.insert(players,v.Name)
end
end)
 
Section:NewButton("Teleport", " ", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[Select].Character.HumanoidRootPart.CFrame
end)

local Tab = Window:NewTab("Game")
local Section = Tab:NewSection("TeleportChestAll")

Section:NewButton("Teleport", "ButtonInfo", function()
    local ll__SHARK_X_HUB__ll = "SHARK X HUB | MOOD#999" local ll__lIllIllIl__ll = game.Players.LocalPlayer if #ll__SHARK_X_HUB__ll == 22 then local ll__lIIlIIlllIl__ll = "SHARK X HUB NO 1" _G.ll__lIllI__ll = true local p = true local ll__lIllIlllIllIl__ll = {[1] = "SetTeam", [2] = "Pirates"} game:GetService("ReplicatedStorage").Remotes.CommF:InvokeServer(unpack(ll__lIllIlllIllIl__ll)) _G.ll__lIllIll__ll = true while _G.ll__lIllIll__ll do pcall(function() if game:GetService("Players").LocalPlayer.Data.Beli.Value >= 25000 then _G.ll__lIllI__ll = false  local ll__lIIlIIlllIl__ll = "HIW KAO WA I SUD" game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Cousin", "Check") game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Cousin", "Buy") end end ) wait() local ll_lIIlIIllIll_ll = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame local ll_lIIlIll_ll = game.Workspace:GetChildren() for i = 1, #ll_lIIlIll_ll do if ll_lIIlIll_ll[i].Name:lower():match("chest") then ll__lIllIl__ll = false repeat wait() if ll_lIIlIll_ll[i].Parent ~= game.Workspace then ll__lIllIl__ll = true else pcall( function()  local ll__lIIlIIlllIl__ll = "YOUR MOTHER SUCK MY DICK!" if game:GetService("Players").LocalPlayer.Data.Beli.Value >= 25000 then _G.ll__lIllI__ll = false game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Cousin", "Check") game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Cousin", "Buy") local ll__IlIlIIIllllIIl__ll = 0.4 function ll__lIIlIlllIllIlllIllIL__ll(ll__IllIllIIIlIl__ll) if game.Players.LocalPlayer.Backpack:FindFirstChild(ll__IllIllIIIlIl__ll) then local ll__IIIlIIllIl__ll = game.Players.LocalPlayer.Backpack:FindFirstChild(ll__IllIllIIIlIl__ll) wait(ll__IlIlIIIllllIIl__ll) game.Players.LocalPlayer.Character.Humanoid:EquipTool(ll__IIIlIIllIl__ll) end end for ll__IlIIllIIlllIl__ll,ll__IlIlIlIlIll__ll in pairs (game.Players.LocalPlayer.Backpack:GetChildren()) do if string.find(ll__IlIlIlIlIll__ll.Name,"Fruit") then local ll__IlIIIIllllIl__ll = ll__IlIlIlIlIll__ll.Name ll__lIIlIlllIllIlllIllIL__ll(ll__IlIIIIllllIl__ll) end end end end ) if _G.ll__lIllI__ll then game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = ll_lIIlIll_ll[i].CFrame end end until ll__lIllIl__ll == true end end  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = ll_lIIlIIllIll_ll  end else  local ll__lIIlIIlllIl__ll = "YOUR MOTHER AND YOUR SISTER SUCK MY DICK!" ll__lIllIllIl__ll:kick(ll__lIIlIIlllIl__ll) end
end)


local Section = Tab:NewSection("Bringfruit")

Section:NewButton("can't use", "ButtonInfo", function()
    
end)

local Section = Tab:NewSection("BringPlayers")

Section:NewButton("Bring", "ButtonInfo", function()
    --[[
bad skid
--]]
 
local L_1_ = true;
local L_2_ = game.Players.LocalPlayer.Character.HumanoidRootPart;
local L_3_ = L_2_.Position - Vector3.new(5, 0, 0)
 
game.Players.LocalPlayer:GetMouse().KeyDown:Connect(function(L_4_arg1)
	if L_4_arg1 == 'f' then
		L_1_ = not L_1_
	end;
	if L_4_arg1 == 'r' then
		L_2_ = game.Players.LocalPlayer.Character.HumanoidRootPart;
		L_3_ = L_2_.Position - Vector3.new(5, 0, 0)
	end
end)
 
for L_5_forvar1, L_6_forvar2 in pairs(game.Players:GetPlayers()) do
	if L_6_forvar2 == game.Players.LocalPlayer then
	else
		local L_7_ = coroutine.create(function()
			game:GetService('RunService').RenderStepped:Connect(function()
				local L_8_, L_9_ = pcall(function()
					local L_10_ = L_6_forvar2.Character;
					if L_10_ then
						if L_10_:FindFirstChild("HumanoidRootPart") then
							if L_1_ then
								L_6_forvar2.Backpack:ClearAllChildren()
								for L_11_forvar1, L_12_forvar2 in pairs(L_10_:GetChildren()) do
									if L_12_forvar2:IsA("Tool") then
										L_12_forvar2:Destroy()
									end
								end;
								L_10_.HumanoidRootPart.CFrame = CFrame.new(L_3_)
							end
						end
					end
				end)
				if L_8_ then
				else
					warn("Unnormal error: "..L_9_)
				end
			end)
		end)
		coroutine.resume(L_7_)
	end
end;
 
game.Players.PlayerAdded:Connect(function(L_13_arg1)   
	if L_13_arg1 == game.Players.LocalPlayer then
	else
		local L_14_ = coroutine.create(function()
			game:GetService('RunService').RenderStepped:Connect(function()
				local L_15_, L_16_ = pcall(function()
					local L_17_ = L_13_arg1.Character;
					if L_17_ then
						if L_17_:FindFirstChild("HumanoidRootPart") then
							if L_1_ then
								L_13_arg1.Backpack:ClearAllChildren()
								for L_18_forvar1, L_19_forvar2 in pairs(L_17_:GetChildren()) do
									if L_19_forvar2:IsA("Tool") then
										L_19_forvar2:Destroy()
									end
								end;
								L_17_.HumanoidRootPart.CFrame = CFrame.new(L_3_)
							end
						end
					end
				end)
				if L_15_ then
				else
					warn("Unnormal error: "..L_16_)
				end
			end)
		end)
		coroutine.resume(L_14_)
	end           
end)
end)

local Section = Tab:NewSection("NpcTeleport")

Section:NewButton("NpcTeleport", "ButtonInfo", function()
    
end)


local Section = Tab:NewSection("Blackleg")

Section:NewButton("Teleport", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-987.23175, 13.7520361, 3989.80298, -0.272060424, -7.10997128e-09, -0.962280095, -8.50117921e-10, 1, -7.14832105e-09, 0.962280095, -1.12672338e-09, -0.272060424)
end)

local Section = Tab:NewSection("Electro")

Section:NewButton("Teleport", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5387.12012, 13.5180063, -2147.54541, 0.166960597, 1.33693021e-08, -0.985963345, 2.98132008e-08, 1, 1.86081266e-08, 0.985963345, -3.25015534e-08, 0.166960597)
end)

local Section = Tab:NewSection("FishMan")

Section:NewButton("Teleport", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(61583.3281, 18.8707886, 986.646545, -0.00245730928, -5.70202374e-08, -0.999997139, -1.9176398e-10, 1, -5.70199425e-08, 0.999997139, 5.16460208e-11, -0.00245730928)
end)

local Tab = Window:NewTab("Credit")
local Section = Tab:NewSection("Madeby:1E A")
local Section = Tab:NewSection("FaceBook:SuwanShell")
local Section = Tab:NewSection("Uiby:Kavoui")
