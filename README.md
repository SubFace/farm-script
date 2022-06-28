-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local DropWeights = Instance.new("TextButton")
local EquipWeights = Instance.new("TextButton")
local DisablePopups = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local AntiAFK = Instance.new("TextButton")
local FarmWeights = Instance.new("TextButton")
local Admin = Instance.new("TextButton")
local clicktp = Instance.new("TextButton")
local LoopKill = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
ScreenGui.ResetOnSpawn = false

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.712328792, 0, 0.198773012, 0)
Frame.Size = UDim2.new(0, 223, 0, 611)

DropWeights.Name = "DropWeights"
DropWeights.Parent = Frame
DropWeights.BackgroundColor3 = Color3.fromRGB(20, 23, 89)
DropWeights.BorderSizePixel = 0
DropWeights.Position = UDim2.new(0.107623316, 0, 0.407833666, 0)
DropWeights.Size = UDim2.new(0, 174, 0, 50)
DropWeights.Font = Enum.Font.SciFi
DropWeights.Text = "Drop Weights"
DropWeights.TextColor3 = Color3.fromRGB(0, 0, 0)
DropWeights.TextScaled = true
DropWeights.TextSize = 14.000
DropWeights.TextWrapped = true

EquipWeights.Name = "EquipWeights"
EquipWeights.Parent = Frame
EquipWeights.BackgroundColor3 = Color3.fromRGB(20, 23, 89)
EquipWeights.BorderSizePixel = 0
EquipWeights.Position = UDim2.new(0.107623316, 0, 0.0797691271, 0)
EquipWeights.Size = UDim2.new(0, 174, 0, 49)
EquipWeights.Font = Enum.Font.SciFi
EquipWeights.Text = "Equip Weights"
EquipWeights.TextColor3 = Color3.fromRGB(0, 0, 0)
EquipWeights.TextScaled = true
EquipWeights.TextSize = 14.000
EquipWeights.TextWrapped = true

DisablePopups.Name = "DisablePopups"
DisablePopups.Parent = Frame
DisablePopups.BackgroundColor3 = Color3.fromRGB(20, 23, 89)
DisablePopups.BorderSizePixel = 0
DisablePopups.Position = UDim2.new(0.107623316, 0, 0.620942771, 0)
DisablePopups.Size = UDim2.new(0, 174, 0, 50)
DisablePopups.Font = Enum.Font.SciFi
DisablePopups.Text = "Disable Pop-ups"
DisablePopups.TextColor3 = Color3.fromRGB(0, 0, 0)
DisablePopups.TextScaled = true
DisablePopups.TextSize = 14.000
DisablePopups.TextWrapped = true

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(20, 23, 89)
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Size = UDim2.new(0, 223, 0, 25)
TextLabel.Font = Enum.Font.Oswald
TextLabel.Text = "SubFa3e's Farm GUI"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

AntiAFK.Name = "AntiAFK"
AntiAFK.Parent = Frame
AntiAFK.BackgroundColor3 = Color3.fromRGB(20, 23, 89)
AntiAFK.BorderSizePixel = 0
AntiAFK.Position = UDim2.new(0.107623316, 0, 0.513497531, 0)
AntiAFK.Size = UDim2.new(0, 174, 0, 50)
AntiAFK.Font = Enum.Font.SciFi
AntiAFK.Text = "Anti-AFK"
AntiAFK.TextColor3 = Color3.fromRGB(0, 0, 0)
AntiAFK.TextScaled = true
AntiAFK.TextSize = 14.000
AntiAFK.TextWrapped = true

FarmWeights.Name = "FarmWeights"
FarmWeights.Parent = Frame
FarmWeights.BackgroundColor3 = Color3.fromRGB(20, 23, 89)
FarmWeights.Position = UDim2.new(0.107623316, 0, 0.187022626, 0)
FarmWeights.Size = UDim2.new(0, 174, 0, 50)
FarmWeights.Font = Enum.Font.SciFi
FarmWeights.Text = "Farm Weights"
FarmWeights.TextColor3 = Color3.fromRGB(0, 0, 0)
FarmWeights.TextScaled = true
FarmWeights.TextSize = 14.000
FarmWeights.TextWrapped = true

Admin.Name = "Admin"
Admin.Parent = Frame
Admin.BackgroundColor3 = Color3.fromRGB(20, 23, 89)
Admin.BorderSizePixel = 0
Admin.Position = UDim2.new(0.107623316, 0, 0.295857131, 0)
Admin.Size = UDim2.new(0, 174, 0, 50)
Admin.Font = Enum.Font.SciFi
Admin.Text = "Admin"
Admin.TextColor3 = Color3.fromRGB(0, 0, 0)
Admin.TextScaled = true
Admin.TextSize = 14.000
Admin.TextWrapped = true

clicktp.Name = "clicktp"
clicktp.Parent = Frame
clicktp.BackgroundColor3 = Color3.fromRGB(20, 23, 89)
clicktp.BorderSizePixel = 0
clicktp.Position = UDim2.new(0.107623316, 0, 0.728105545, 0)
clicktp.Size = UDim2.new(0, 174, 0, 50)
clicktp.Font = Enum.Font.SciFi
clicktp.Text = "Click TP (press e)"
clicktp.TextColor3 = Color3.fromRGB(0, 0, 0)
clicktp.TextScaled = true
clicktp.TextSize = 14.000
clicktp.TextWrapped = true

LoopKill.Name = "LoopKill"
LoopKill.Parent = Frame
LoopKill.BackgroundColor3 = Color3.fromRGB(20, 23, 89)
LoopKill.BorderSizePixel = 0
LoopKill.Position = UDim2.new(0.107623316, 0, 0.836333871, 0)
LoopKill.Size = UDim2.new(0, 174, 0, 50)
LoopKill.Font = Enum.Font.SciFi
LoopKill.Text = "Loop Kill"
LoopKill.TextColor3 = Color3.fromRGB(0, 0, 0)
LoopKill.TextScaled = true
LoopKill.TextSize = 14.000
LoopKill.TextWrapped = true

-- Scripts:

local function PDENT_fake_script() -- Frame.SmoothDrag 
	local script = Instance.new('LocalScript', Frame)

	local Drag = script.Parent.Parent.Frame
	gsCoreGui = game:GetService("CoreGui")
	gsTween = game:GetService("TweenService")
	local UserInputService = game:GetService("UserInputService")
		local dragging
		local dragInput
		local dragStart
		local startPos
		local function update(input)
			local delta = input.Position - dragStart
			local dragTime = 0.04
			local SmoothDrag = {}
			SmoothDrag.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
			local dragSmoothFunction = gsTween:Create(Drag, TweenInfo.new(dragTime, Enum.EasingStyle.Sine, Enum.EasingDirection.InOut), SmoothDrag)
			dragSmoothFunction:Play()
		end
		Drag.InputBegan:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
				dragging = true
				dragStart = input.Position
				startPos = Drag.Position
				input.Changed:Connect(function()
					if input.UserInputState == Enum.UserInputState.End then
						dragging = false
					end
				end)
			end
		end)
		Drag.InputChanged:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
				dragInput = input
			end
		end)
		UserInputService.InputChanged:Connect(function(input)
			if input == dragInput and dragging and Drag.Size then
				update(input)
			end
		end)
	
end
coroutine.wrap(PDENT_fake_script)()

local plr = game.Players.LocalPlayer

FarmWeights.MouseButton1Click:connect(function()
	_G.Auto4 = true
	while _G.Auto4 do
		wait(0.6)
		for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
			if v.Name == "Double Weight" then v:Activate() end


		end
	end
end)

EquipWeights.MouseButton1Click:connect(function()
	_G.Equip = true
	while _G.Equip do
		wait()
		for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
			if v.Name == "Double Weight" then v:Activate()
				v.Parent = game.Players.LocalPlayer.Character
			end
		end
	end
end)

DropWeights.MouseButton1Click:connect(function() do

		local GodMode_IIIiil=select;local GodMode_iiiIllIllIilii=string.byte;local GodMode_illiIIIilIliilii=string.sub;local GodMode_IIIIIliiillIIiiI=string.char;local GodMode_lIIliIiliIIii=type;local GodMode_ilIiIlliiiIiiIiiliI=table.concat;local unpack=unpack;local setmetatable=setmetatable;local pcall=pcall;local GodMode_IlIll,GodMode_lIIIIiIl,GodMode_iIlliililiIIIll,GodMode_IlIlIiiili;if bit and bit.bxor then GodMode_IlIll=bit.bxor;GodMode_lIIIIiIl=function(GodMode_liiIiiIIiIllI,GodMode_lillIIiliIiI)local GodMode_IIiIlIllIiilIIIlll=GodMode_IlIll(GodMode_liiIiiIIiIllI,GodMode_lillIIiliIiI)if GodMode_IIiIlIllIiilIIIlll<0 then GodMode_IIiIlIllIiilIIIlll=4294967296+GodMode_IIiIlIllIiilIIIlll end;return GodMode_IIiIlIllIiilIIIlll end else GodMode_IlIll=function(GodMode_liiIiiIIiIllI,GodMode_lillIIiliIiI)local GodMode_iIIiIIIllillIll=function(GodMode_IiliIIiIIIIlilllliI,GodMode_illillIlillIllIl)return GodMode_IiliIIiIIIIlilllliI%(GodMode_illillIlillIllIl*2)>=GodMode_illillIlillIllIl end;local GodMode_iiliiI=0;for GodMode_lIlIIiiilIili=0,31 do GodMode_iiliiI=GodMode_iiliiI+(GodMode_iIIiIIIllillIll(GodMode_liiIiiIIiIllI,2^GodMode_lIlIIiiilIili)~=GodMode_iIIiIIIllillIll(GodMode_lillIIiliIiI,2^GodMode_lIlIIiiilIili)and 2^GodMode_lIlIIiiilIili or 0)end;return GodMode_iiliiI end;GodMode_lIIIIiIl=GodMode_IlIll end;GodMode_iIlliililiIIIll=function(GodMode_IllIIlIliIIl,GodMode_IiiliiIIIiliIIl,GodMode_lIiIIiIliil)return(GodMode_IllIIlIliIIl+GodMode_IiiliiIIIiliIIl)%GodMode_lIiIIiIliil end;GodMode_IlIlIiiili=function(GodMode_IllIIlIliIIl,GodMode_IiiliiIIIiliIIl,GodMode_lIiIIiIliil)return(GodMode_IllIIlIliIIl-GodMode_IiiliiIIIiliIIl)%GodMode_lIiIIiIliil end;local function GodMode_IIliIlIliiliiliIIi(GodMode_IIiIlIllIiilIIIlll)if GodMode_IIiIlIllIiilIIIlll<0 then GodMode_IIiIlIllIiilIIIlll=4294967296+GodMode_IIiIlIllIiilIIIlll end;return GodMode_IIiIlIllIiilIIIlll end;local getfenv=getfenv;if not getfenv then getfenv=function()return _ENV end end;local GodMode_IIIIlliiIlIliIlil={}local GodMode_IlliliilIIIl={}local GodMode_liIilI;local GodMode_lIilIiIlill;local GodMode_lIllIliiiilllIlllI={}local GodMode_IIiiliIII={}for GodMode_lIlIIiiilIili=0,255 do local GodMode_IIiiIIliiiilllIllIil,GodMode_IlIlIili=GodMode_IIIIIliiillIIiiI(GodMode_lIlIIiiilIili),GodMode_IIIIIliiillIIiiI(GodMode_lIlIIiiilIili,0)GodMode_lIllIliiiilllIlllI[GodMode_IIiiIIliiiilllIllIil]=GodMode_IlIlIili;GodMode_IIiiliIII[GodMode_IlIlIili]=GodMode_IIiiIIliiiilllIllIil end;local function GodMode_lIIlllli(GodMode_IIIIIIlI,GodMode_IllIiIiIillIIi,GodMode_iIIlilliii,GodMode_ilIIiiiiIIiIIIIllIII)if GodMode_iIIlilliii>=256 then GodMode_iIIlilliii,GodMode_ilIIiiiiIIiIIIIllIII=0,GodMode_ilIIiiiiIIiIIIIllIII+1;if GodMode_ilIIiiiiIIiIIIIllIII>=256 then GodMode_IllIiIiIillIIi={}GodMode_ilIIiiiiIIiIIIIllIII=1 end end;GodMode_IllIiIiIillIIi[GodMode_IIIIIliiillIIiiI(GodMode_iIIlilliii,GodMode_ilIIiiiiIIiIIIIllIII)]=GodMode_IIIIIIlI;GodMode_iIIlilliii=GodMode_iIIlilliii+1;return GodMode_IllIiIiIillIIi,GodMode_iIIlilliii,GodMode_ilIIiiiiIIiIIIIllIII end;local function GodMode_iiiilliillI(GodMode_llllIIIil)local function GodMode_iIiIIIlli(GodMode_ililiIiIililIliIiI)local GodMode_ilIIiiiiIIiIIIIllIII='ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/'GodMode_ililiIiIililIliIiI=string.gsub(GodMode_ililiIiIililIliIiI,'[^'..GodMode_ilIIiiiiIIiIIIIllIII..'=]','')return GodMode_ililiIiIililIliIiI:gsub('.',function(GodMode_IllIIlIliIIl)if GodMode_IllIIlIliIIl=='='then return''end;local GodMode_lilIlIi,GodMode_iIillIIiiiiIIllIlI='',GodMode_ilIIiiiiIIiIIIIllIII:find(GodMode_IllIIlIliIIl)-1;for GodMode_lIlIIiiilIili=6,1,-1 do GodMode_lilIlIi=GodMode_lilIlIi..(GodMode_iIillIIiiiiIIllIlI%2^GodMode_lIlIIiiilIili-GodMode_iIillIIiiiiIIllIlI%2^(GodMode_lIlIIiiilIili-1)>0 and'1'or'0')end;return GodMode_lilIlIi end):gsub('%d%d%d?%d?%d?%d?%d?%d?',function(GodMode_IllIIlIliIIl)if#GodMode_IllIIlIliIIl~=8 then return''end;local GodMode_lIiIIiiIIlIlIi=0;for GodMode_lIlIIiiilIili=1,8 do GodMode_lIiIIiiIIlIlIi=GodMode_lIiIIiiIIlIlIi+(GodMode_IllIIlIliIIl:sub(GodMode_lIlIIiiilIili,GodMode_lIlIIiiilIili)=='1'and 2^(8-GodMode_lIlIIiiilIili)or 0)end;return string.char(GodMode_lIiIIiiIIlIlIi)end)end;GodMode_llllIIIil=GodMode_iIiIIIlli(GodMode_llllIIIil)local GodMode_iIIIililIIII=GodMode_illiIIIilIliilii(GodMode_llllIIIil,1,1)if GodMode_iIIIililIIII=="u"then return GodMode_illiIIIilIliilii(GodMode_llllIIIil,2)elseif GodMode_iIIIililIIII~="c"then error("Synapse Xen - Failed to verify bytecode. Please make sure your Lua implementation supports non-null terminated strings.")end;GodMode_llllIIIil=GodMode_illiIIIilIliilii(GodMode_llllIIIil,2)local GodMode_illlIIIllIiIillIIIl=#GodMode_llllIIIil;local GodMode_IllIiIiIillIIi={}local GodMode_iIIlilliii,GodMode_ilIIiiiiIIiIIIIllIII=0,1;local GodMode_lliiliIliIl={}local GodMode_IIiIlIllIiilIIIlll=1;local GodMode_lliiIiliiIillI=GodMode_illiIIIilIliilii(GodMode_llllIIIil,1,2)GodMode_lliiliIliIl[GodMode_IIiIlIllIiilIIIlll]=GodMode_IIiiliIII[GodMode_lliiIiliiIillI]or GodMode_IllIiIiIillIIi[GodMode_lliiIiliiIillI]GodMode_IIiIlIllIiilIIIlll=GodMode_IIiIlIllIiilIIIlll+1;for GodMode_lIlIIiiilIili=3,GodMode_illlIIIllIiIillIIIl,2 do local GodMode_lIIillllliIIiII=GodMode_illiIIIilIliilii(GodMode_llllIIIil,GodMode_lIlIIiiilIili,GodMode_lIlIIiiilIili+1)local GodMode_IlliiiIlIilIlilIl=GodMode_IIiiliIII[GodMode_lliiIiliiIillI]or GodMode_IllIiIiIillIIi[GodMode_lliiIiliiIillI]if not GodMode_IlliiiIlIilIlilIl then error("Synapse Xen - Failed to verify bytecode. Please make sure your Lua implementation supports non-null terminated strings.")end;local GodMode_llIiIlI=GodMode_IIiiliIII[GodMode_lIIillllliIIiII]or GodMode_IllIiIiIillIIi[GodMode_lIIillllliIIiII]if GodMode_llIiIlI then GodMode_lliiliIliIl[GodMode_IIiIlIllIiilIIIlll]=GodMode_llIiIlI;GodMode_IIiIlIllIiilIIIlll=GodMode_IIiIlIllIiilIIIlll+1;GodMode_IllIiIiIillIIi,GodMode_iIIlilliii,GodMode_ilIIiiiiIIiIIIIllIII=GodMode_lIIlllli(GodMode_IlliiiIlIilIlilIl..GodMode_illiIIIilIliilii(GodMode_llIiIlI,1,1),GodMode_IllIiIiIillIIi,GodMode_iIIlilliii,GodMode_ilIIiiiiIIiIIIIllIII)else local GodMode_llillillIIlIiiIl=GodMode_IlliiiIlIilIlilIl..GodMode_illiIIIilIliilii(GodMode_IlliiiIlIilIlilIl,1,1)GodMode_lliiliIliIl[GodMode_IIiIlIllIiilIIIlll]=GodMode_llillillIIlIiiIl;GodMode_IIiIlIllIiilIIIlll=GodMode_IIiIlIllIiilIIIlll+1;GodMode_IllIiIiIillIIi,GodMode_iIIlilliii,GodMode_ilIIiiiiIIiIIIIllIII=GodMode_lIIlllli(GodMode_llillillIIlIiiIl,GodMode_IllIiIiIillIIi,GodMode_iIIlilliii,GodMode_ilIIiiiiIIiIIIIllIII)end;GodMode_lliiIiliiIillI=GodMode_lIIillllliIIiII end;return GodMode_ilIiIlliiiIiiIiiliI(GodMode_lliiliIliIl)end;local function GodMode_lilIilill(GodMode_IlIIliIlIIiilIil,GodMode_lIIIIilillii,GodMode_lIIii)if GodMode_lIIii then local GodMode_IiiilIliIliIillillIi=GodMode_IlIIliIlIIiilIil/2^(GodMode_lIIIIilillii-1)%2^(GodMode_lIIii-1-(GodMode_lIIIIilillii-1)+1)return GodMode_IiiilIliIliIillillIi-GodMode_IiiilIliIliIillillIi%1 else local GodMode_illllIIili=2^(GodMode_lIIIIilillii-1)if GodMode_IlIIliIlIIiilIil%(GodMode_illllIIili+GodMode_illllIIili)>=GodMode_illllIIili then return 1 else return 0 end end end;local function GodMode_iIiIIIlliIIIliIIi()local GodMode_IliIiIllIlIllIIi=GodMode_IlIll(1715054665,GodMode_lIilIiIlill)while true do if GodMode_IliIiIllIlIllIIi==GodMode_IlIll(1733912599,GodMode_lIilIiIlill)then return elseif GodMode_IliIiIllIlIllIIi==GodMode_IlIll(2557887040,GodMode_IlliliilIIIl[4])then GodMode_liIilI=function(GodMode_iIiiIlIIiiIIIII,GodMode_llilliIi)return GodMode_IlIll(GodMode_iIiiIlIIiiIIIII-1271,GodMode_llilliIi+15367)+GodMode_IlIll(1988247328,GodMode_IlliliilIIIl[7])end;GodMode_IliIiIllIlIllIIi=GodMode_IliIiIllIlIllIIi-GodMode_IlIll(4016577223,GodMode_lIilIiIlill)elseif GodMode_IliIiIllIlIllIIi==GodMode_IlIll(1733857895,GodMode_lIilIiIlill)then GodMode_liIilI=function(GodMode_iIiiIlIIiiIIIII,GodMode_llilliIi)return GodMode_IlIll(GodMode_iIiiIlIIiiIIIII-1999,GodMode_llilliIi+28059)+GodMode_IlIll(1153814062,GodMode_IlliliilIIIl[10])end;GodMode_IliIiIllIlIllIIi=GodMode_IliIiIllIlIllIIi+GodMode_IlIll(3316016714,GodMode_IlliliilIIIl[6])elseif GodMode_IliIiIllIlIllIIi==GodMode_IlIll(3782529581,GodMode_IlliliilIIIl[9])then GodMode_liIilI=function(GodMode_iIiiIlIIiiIIIII,GodMode_llilliIi)return GodMode_IlIll(GodMode_iIiiIlIIiiIIIII+38296,GodMode_llilliIi+48354)-GodMode_IlIll(4016626602,GodMode_lIilIiIlill)end;GodMode_IliIiIllIlIllIIi=GodMode_IliIiIllIlIllIIi-GodMode_IlIll(3316015162,GodMode_IlliliilIIIl[6])elseif GodMode_IliIiIllIlIllIIi==GodMode_IlIll(1733903014,GodMode_lIilIiIlill)then GodMode_liIilI=function(GodMode_iIiiIlIIiiIIIII,GodMode_llilliIi)return GodMode_IlIll(GodMode_iIiiIlIIiiIIIII-15795,GodMode_llilliIi-37473)+GodMode_IlIll(287806163,GodMode_IlliliilIIIl[4])end;GodMode_IliIiIllIlIllIIi=GodMode_IliIiIllIlIllIIi+GodMode_IlIll(4016600275,GodMode_lIilIiIlill)elseif GodMode_IliIiIllIlIllIIi==GodMode_IlIll(1131485599,GodMode_IlliliilIIIl[7])then GodMode_liIilI=function(GodMode_iIiiIlIIiiIIIII,GodMode_llilliIi)return GodMode_IlIll(GodMode_iIiiIlIIiiIIIII-8041,GodMode_llilliIi-43616)-GodMode_IlIll(4016635226,GodMode_lIilIiIlill)end;GodMode_IliIiIllIlIllIIi=GodMode_IlIll(GodMode_IliIiIllIlIllIIi,GodMode_IlIll(4177942198,GodMode_IlliliilIIIl[10]))elseif GodMode_IliIiIllIlIllIIi==GodMode_IlIll(4032121308,GodMode_IlliliilIIIl[6])then GodMode_liIilI=function(GodMode_iIiiIlIIiiIIIII,GodMode_llilliIi)return GodMode_IlIll(GodMode_iIiiIlIIiiIIIII+14501,GodMode_llilliIi-44971)+GodMode_IlIll(4016629490,GodMode_lIilIiIlill)end;GodMode_IliIiIllIlIllIIi=GodMode_IliIiIllIlIllIIi-GodMode_IlIll(915845780,GodMode_IlliliilIIIl[8])elseif GodMode_IliIiIllIlIllIIi==GodMode_IlIll(1715013589,GodMode_lIilIiIlill)then GodMode_liIilI=function(GodMode_iIiiIlIIiiIIIII,GodMode_llilliIi)return GodMode_IlIll(GodMode_iIiiIlIIiiIIIII+13088,GodMode_llilliIi+37149)+GodMode_IlIll(1988236534,GodMode_IlliliilIIIl[7])end;GodMode_IliIiIllIlIllIIi=GodMode_IlIll(GodMode_IliIiIllIlIllIIi,GodMode_IlIll(1240889695,GodMode_IlliliilIIIl[3]))elseif GodMode_IliIiIllIlIllIIi==GodMode_IlIll(2356649333,GodMode_lIilIiIlill)then GodMode_liIilI=function(GodMode_iIiiIlIIiiIIIII,GodMode_llilliIi)return GodMode_IlIll(GodMode_iIiiIlIIiiIIIII+45360,GodMode_llilliIi+11723)+GodMode_IlIll(2746774448,GodMode_IlliliilIIIl[3])end;GodMode_IliIiIllIlIllIIi=GodMode_IlIll(GodMode_IliIiIllIlIllIIi,GodMode_IlIll(2471134667,GodMode_IlliliilIIIl[6]))end end end;local function GodMode_IIiIiIIIiiiI(GodMode_IiiilIIiilIiiiII)local GodMode_lIiiIIIilllIII=1;local GodMode_IliiiliIIl;local GodMode_IlIiiiIii;local function GodMode_illIlIIIlii()local GodMode_IlIlIIiIII=GodMode_iiiIllIllIilii(GodMode_IiiilIIiilIiiiII,GodMode_lIiiIIIilllIII,GodMode_lIiiIIIilllIII)GodMode_lIiiIIIilllIII=GodMode_lIiiIIIilllIII+1;return GodMode_IlIlIIiIII end;local function GodMode_IlIiIIlI()local GodMode_lllIIlllIIiiilli,GodMode_iIiiIlIIiiIIIII,GodMode_llilliIi,GodMode_ilIliiilillIIiIi=GodMode_iiiIllIllIilii(GodMode_IiiilIIiilIiiiII,GodMode_lIiiIIIilllIII,GodMode_lIiiIIIilllIII+3)GodMode_lIiiIIIilllIII=GodMode_lIiiIIIilllIII+4;return GodMode_ilIliiilillIIiIi*16777216+GodMode_llilliIi*65536+GodMode_iIiiIlIIiiIIIII*256+GodMode_lllIIlllIIiiilli end;local function GodMode_iiIliliIlIliiillll()return GodMode_IlIiIIlI()*4294967296+GodMode_IlIiIIlI()end;local function GodMode_illIlIIIIllI()local GodMode_IiIIlilli=GodMode_lIIIIiIl(GodMode_IlIiIIlI(),GodMode_IIIIlliiIlIliIlil[1806877160]or(function()local GodMode_IllIIlIliIIl="this is so sad, alexa play ripull.mp4"GodMode_IIIIlliiIlIliIlil[1806877160]=GodMode_IlIll(GodMode_liIilI(1295327785,2732947224),GodMode_IlIll(695593121,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{2656102276,2254335195,1596161777,3133938856,626308835,3258210681,587053048}return GodMode_IIIIlliiIlIliIlil[1806877160]end)())local GodMode_lIIIlIlIiiiI=GodMode_lIIIIiIl(GodMode_IlIiIIlI(),GodMode_IIIIlliiIlIliIlil[3725322335]or(function(...)local GodMode_IllIIlIliIIl="luraph better then xen bros :pensive:"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(2927482402,1686355194)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(4184378372,110658844)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[3725322335]=GodMode_IlIll(GodMode_IlIll(745997999,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1709851691,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{2024893965,2476754594}return GodMode_IIIIlliiIlIliIlil[3725322335]end)("lIillIliiIlliIl",{},11219,"lliIIiiIlilllll","iIil"))local GodMode_iiilii=1;local GodMode_illillil=GodMode_lilIilill(GodMode_lIIIlIlIiiiI,1,20)*2^32+GodMode_IiIIlilli;local GodMode_IlIlIii=GodMode_lilIilill(GodMode_lIIIlIlIiiiI,21,31)local GodMode_illiiIllIlllliIIIiiI=(-1)^GodMode_lilIilill(GodMode_lIIIlIlIiiiI,32)if GodMode_IlIlIii==0 then if GodMode_illillil==0 then return GodMode_illiiIllIlllliIIIiiI*0 else GodMode_IlIlIii=1;GodMode_iiilii=0 end elseif GodMode_IlIlIii==2047 then if GodMode_illillil==0 then return GodMode_illiiIllIlllliIIIiiI*1/0 else return GodMode_illiiIllIlllliIIIiiI*0/0 end end;return math.ldexp(GodMode_illiiIllIlllliIIIiiI,GodMode_IlIlIii-1023)*(GodMode_iiilii+GodMode_illillil/2^52)end;local function GodMode_llIIIlIIililillil(GodMode_llIiIlliI)local GodMode_lllilI;if GodMode_llIiIlliI then GodMode_lllilI=GodMode_illiIIIilIliilii(GodMode_IiiilIIiilIiiiII,GodMode_lIiiIIIilllIII,GodMode_lIiiIIIilllIII+GodMode_llIiIlliI-1)GodMode_lIiiIIIilllIII=GodMode_lIiiIIIilllIII+GodMode_llIiIlliI else GodMode_llIiIlliI=GodMode_IliiiliIIl()if GodMode_llIiIlliI==0 then return""end;GodMode_lllilI=GodMode_illiIIIilIliilii(GodMode_IiiilIIiilIiiiII,GodMode_lIiiIIIilllIII,GodMode_lIiiIIIilllIII+GodMode_llIiIlliI-1)GodMode_lIiiIIIilllIII=GodMode_lIiiIIIilllIII+GodMode_llIiIlliI end;return GodMode_lllilI end;local function GodMode_iIIIlilIIIllllIliI(GodMode_lllilI)local GodMode_IiiilIliIliIillillIi={}for GodMode_lIlIIiiilIili=1,#GodMode_lllilI do local GodMode_IiIilIil=GodMode_lllilI:sub(GodMode_lIlIIiiilIili,GodMode_lIlIIiiilIili)GodMode_IiiilIliIliIillillIi[#GodMode_IiiilIliIliIillillIi+1]=string.char(GodMode_IlIll(string.byte(GodMode_IiIilIil),GodMode_IIIIlliiIlIliIlil[2394750056]or(function(...)local GodMode_IllIIlIliIIl="SYNAPSE XEN [FE BYPASS] [BETTER THEN LURAPH] [AMAZING] OMG OMG OMG !!!!!!"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3890676833,465504292)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(2574477292,1720548228)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[2394750056]=GodMode_IlIll(GodMode_IlIll(3938362641,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(4186941810,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{1411881380,2135913027,3989596047,2646325294,1332976428,110086689,4104002247,3120372044}return GodMode_IIIIlliiIlIliIlil[2394750056]end)({})))end;return table.concat(GodMode_IiiilIliIliIillillIi)end;local function GodMode_llilIiliiI()local GodMode_ilIlIliilililII={}local GodMode_lIiliilIiIlilIIlIlIl={}local GodMode_IlliiilllIIiIIliii={}local GodMode_iIIllIlIiIlIlIllliI={[GodMode_IIIIlliiIlIliIlil[1217082785]or(function(...)local GodMode_IllIIlIliIIl="hi xen doesn't work on sk8r please help"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(1054951662,465648657)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(847590584,3447441511)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[1217082785]=GodMode_IlIll(GodMode_IlIll(1664276513,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1615799414,GodMode_IlliliilIIIl[9]))-string.len(GodMode_IllIIlIliIIl)-#{1439609213,3823435444,98229503,2628841276,3968327751,1934225667}return GodMode_IIIIlliiIlIliIlil[1217082785]end)(11277,12707,"lllliiIi","liiil","IIliIiiIIli","iiliiIIIiliiIIlII")]=GodMode_ilIlIliilililII,[GodMode_IIIIlliiIlIliIlil[4145257874]or(function(...)local GodMode_IllIIlIliIIl="thats how mafia works"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(238756953,535586140)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(2307445886,1987562868)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[4145257874]=GodMode_IlIll(GodMode_IlIll(1162371325,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(4039289606,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{4219299912,1449384902,1574189967,912275712,832835489,2903004962,3812672267,3885116912,2729228879}return GodMode_IIIIlliiIlIliIlil[4145257874]end)(13619,{},6609,6260,5557,{},{},"lilliiliIliiIiI")]=GodMode_IlliiilllIIiIIliii,[GodMode_IIIIlliiIlIliIlil[600360600]or(function(...)local GodMode_IllIIlIliIIl="skisploit is the superior obfuscator, clearly."local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3634153482,833940261)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(2863203953,1431824889)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[600360600]=GodMode_IlIll(GodMode_IlIll(2588748501,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1252910397,GodMode_IlliliilIIIl[10]))-string.len(GodMode_IllIIlIliIIl)-#{847515241,2056169881,886048943}return GodMode_IIIIlliiIlIliIlil[600360600]end)("iiliIll")]=GodMode_lIiliilIiIlilIIlIlIl}GodMode_illIlIIIlii()for GodMode_lIlIi=1,GodMode_IlIll(GodMode_IlIiiiIii(),GodMode_IIIIlliiIlIliIlil[1946636726]or(function(...)local GodMode_IllIIlIliIIl="this is a christian obfuscator, no cursing allowed in our scripts"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(1114826123,4085239027)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(465825147,3829179628)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[1946636726]=GodMode_IlIll(GodMode_IlIll(3343951017,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1726074142,GodMode_IlliliilIIIl[8]))-string.len(GodMode_IllIIlIliIIl)-#{522863735,281157196,4054134440,3050657604,3317336256,327276953,2303441438,4070816962}return GodMode_IIIIlliiIlIliIlil[1946636726]end)({},{},9170,5180,{},9122,{}))do GodMode_IlIiIIlI()local GodMode_lIIliIiliIIii=GodMode_illIlIIIlii()local GodMode_lilIilIIiI;if GodMode_lIIliIiliIIii==(GodMode_IIIIlliiIlIliIlil[986473287]or(function(...)local GodMode_IllIIlIliIIl="level 1 crook = luraph, level 100 boss = xen"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(2625556241,1995451537)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(604262825,3690744222)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[986473287]=GodMode_IlIll(GodMode_IlIll(3476333769,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(3402561581,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{456255276,274603618,1915282062,4242369057,3624668951,2592011192,208489627,2919581602,3991119015}return GodMode_IIIIlliiIlIliIlil[986473287]end)({},"llllliiliIl",13757,3082,"iliiiiilIiIIl",13521))then GodMode_lilIilIIiI=GodMode_illIlIIIlii()~=0 elseif GodMode_lIIliIiliIIii==(GodMode_IIIIlliiIlIliIlil[1994131182]or(function(...)local GodMode_IllIIlIliIIl="hi devforum"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(2371334957,327047384)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(2333878258,1961167800)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[1994131182]=GodMode_IlIll(GodMode_IlIll(4129005889,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(3414716585,GodMode_IlliliilIIIl[3]))-string.len(GodMode_IllIIlIliIIl)-#{1481479825}return GodMode_IIIIlliiIlIliIlil[1994131182]end)({},{},"IIliIiliillliIllI"))then GodMode_lilIilIIiI=GodMode_illIlIIIIllI()elseif GodMode_lIIliIiliIIii==(GodMode_IIIIlliiIlIliIlil[3016463523]or(function(...)local GodMode_IllIIlIliIIl="hi my 2.5mb script doesn't work with xen please help"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(2848814550,3398514200)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(1219690887,3075314925)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[3016463523]=GodMode_IlIll(GodMode_IlIll(2944713254,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(2768020678,GodMode_IlliliilIIIl[9]))-string.len(GodMode_IllIIlIliIIl)-#{2784726028,1724718175,3598219768}return GodMode_IIIIlliiIlIliIlil[3016463523]end)({},{},{},9343))then GodMode_lilIilIIiI=GodMode_illiIIIilIliilii(GodMode_iIIIlilIIIllllIliI(GodMode_llIIIlIIililillil()),1,-2)end;GodMode_IlliiilllIIiIIliii[GodMode_lIlIi-1]=GodMode_lilIilIIiI end;GodMode_IlIiIIlI()GodMode_IlIiIIlI()for GodMode_lIlIi=1,GodMode_IlIll(GodMode_IlIiiiIii(),GodMode_IIIIlliiIlIliIlil[2428197976]or(function()local GodMode_IllIIlIliIIl="xen best rerubi paste"GodMode_IIIIlliiIlIliIlil[2428197976]=GodMode_IlIll(GodMode_liIilI(3028170786,3074217301),GodMode_IlIll(315381158,GodMode_IlliliilIIIl[7]))-string.len(GodMode_IllIIlIliIIl)-#{4202550017,152942774,3317276902,1668631386,533545885,760911212}return GodMode_IIIIlliiIlIliIlil[2428197976]end)())do GodMode_IlIiIIlI()local GodMode_liIiIlIII=GodMode_IlIll(GodMode_IlIiIIlI(),GodMode_IIIIlliiIlIliIlil[626493145]or(function()local GodMode_IllIIlIliIIl="what are you trying to say? that fucking one dot + dot + dot + many dots is not adding adding 1 dot + dot and then adding all the dots together????"GodMode_IIIIlliiIlIliIlil[626493145]=GodMode_IlIll(GodMode_liIilI(2167913297,3424146663),GodMode_IlIll(1839042727,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{3468643511,2670275461,3720726,795651858,475633298,3140456579,734439571}return GodMode_IIIIlliiIlIliIlil[626493145]end)())local GodMode_lIliIIllliIii=GodMode_illIlIIIlii()local GodMode_lIIliIiliIIii=GodMode_illIlIIIlii()local GodMode_IliIiIIiiIiIlIII={[269286993]=GodMode_liIiIlIII,[1380221887]=GodMode_lIliIIllliIii,[924786088]=GodMode_lilIilill(GodMode_liIiIlIII,1,6),[1728429953]=GodMode_lilIilill(GodMode_liIiIlIII,7,14)}if GodMode_lIIliIiliIIii==(GodMode_IIIIlliiIlIliIlil[3662006228]or(function()local GodMode_IllIIlIliIIl="https://twitter.com/Ripull_RBLX/status/1059334518581145603"GodMode_IIIIlliiIlIliIlil[3662006228]=GodMode_IlIll(GodMode_liIilI(1732524905,1974787115),GodMode_IlIll(4254103228,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{3151395145,3078123452,782566146,377504684,2179614263,1280522622,5672678}return GodMode_IIIIlliiIlIliIlil[3662006228]end)())then GodMode_IliIiIIiiIiIlIII[1748678928]=GodMode_lilIilill(GodMode_liIiIlIII,24,32)GodMode_IliIiIIiiIiIlIII[1783335623]=GodMode_lilIilill(GodMode_liIiIlIII,15,23)elseif GodMode_lIIliIiliIIii==(GodMode_IIIIlliiIlIliIlil[557067753]or(function(...)local GodMode_IllIIlIliIIl="pain is gonna use the backspace method on xen"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3110221547,4188627819)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(2111638752,2183398609)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[557067753]=GodMode_IlIll(GodMode_IlIll(298923806,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(3195014228,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{3715690435,86845612}return GodMode_IIIIlliiIlIliIlil[557067753]end)({}))then GodMode_IliIiIIiiIiIlIII[343510866]=GodMode_lilIilill(GodMode_liIiIlIII,15,32)elseif GodMode_lIIliIiliIIii==(GodMode_IIIIlliiIlIliIlil[2329192490]or(function()local GodMode_IllIIlIliIIl="sponsored by ironbrew, jk xen is better"GodMode_IIIIlliiIlIliIlil[2329192490]=GodMode_IlIll(GodMode_liIilI(867752981,3965663217),GodMode_IlIll(814677839,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{704076705}return GodMode_IIIIlliiIlIliIlil[2329192490]end)())then GodMode_IliIiIIiiIiIlIII[1677511591]=GodMode_lilIilill(GodMode_liIiIlIII,15,32)-131071 end;GodMode_lIiliilIiIlilIIlIlIl[GodMode_lIlIi]=GodMode_IliIiIIiiIiIlIII end;GodMode_IlIiIIlI()GodMode_illIlIIIlii()GodMode_iIIllIlIiIlIlIllliI[1225792899]=GodMode_IlIll(GodMode_illIlIIIlii(),GodMode_IIIIlliiIlIliIlil[1825264390]or(function(...)local GodMode_IllIIlIliIIl="i'm intercommunication about the most nonecclesiastical dll exploits for esp. they only characterization objects with a antepatriarchal in the geistesgeschichte for the esp."local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(1481333382,2925478251)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(3614951366,680048952)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[1825264390]=GodMode_IlIll(GodMode_IlIll(3691088678,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1859270837,GodMode_IlliliilIIIl[10]))-string.len(GodMode_IllIIlIliIIl)-#{1860588090,1842347714,1993579390,3024040976,1455184786}return GodMode_IIIIlliiIlIliIlil[1825264390]end)("iIIlI",{}))GodMode_illIlIIIlii()GodMode_IlIiIIlI()GodMode_iIIllIlIiIlIlIllliI[967784514]=GodMode_IlIll(GodMode_illIlIIIlii(),GodMode_IIIIlliiIlIliIlil[627344278]or(function(...)local GodMode_IllIIlIliIIl="wally bad bird"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3776748823,450690965)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(2754233932,1540776418)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[627344278]=GodMode_IlIll(GodMode_IlIll(707986537,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(3877267543,GodMode_IlliliilIIIl[8]))-string.len(GodMode_IllIIlIliIIl)-#{2472623989,3215950450,1356202406,36876073,4255736297,1896359648}return GodMode_IIIIlliiIlIliIlil[627344278]end)("lliIili",9001,13088,{},"Il",14481,6255))GodMode_IlIiIIlI()GodMode_illIlIIIlii()for GodMode_lIlIi=1,GodMode_IlIll(GodMode_IlIiiiIii(),GodMode_IIIIlliiIlIliIlil[2229986765]or(function(...)local GodMode_IllIIlIliIIl="so if you'we nyot awawe of expwoiting by this point, you've pwobabwy been wiving undew a wock that the pionyeews used to wide fow miwes. wobwox is often seen as an expwoit-infested gwound by most fwom the suwface, awthough this isn't the case."local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3551744326,3173474193)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(3243609378,1051431050)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[2229986765]=GodMode_IlIll(GodMode_IlIll(4013468947,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(4119821331,GodMode_IlliliilIIIl[7]))-string.len(GodMode_IllIIlIliIIl)-#{3080203910,2675429069,2222021131,3227675311,4132510484,2818149719,2427299538,1622917478}return GodMode_IIIIlliiIlIliIlil[2229986765]end)({},8299,{},12541,2297,{},9006,11845))do GodMode_ilIlIliilililII[GodMode_lIlIi-1]=GodMode_llilIiliiI()end;return GodMode_iIIllIlIiIlIlIllliI end;do assert(GodMode_llIIIlIIililillil(4)=="\27Xen","Synapse Xen - Failed to verify bytecode. Please make sure your Lua implementation supports non-null terminated strings.")GodMode_IlIiiiIii=GodMode_IlIiIIlI;GodMode_IliiiliIIl=GodMode_IlIiIIlI;local GodMode_iIllIliIIiilliIIIIl=GodMode_llIIIlIIililillil()GodMode_illIlIIIlii()GodMode_lIilIiIlill=GodMode_IIliIlIliiliiliIIi(GodMode_IlIiiiIii())GodMode_IlIiIIlI()GodMode_IlIiIIlI()local GodMode_IiiiIllI=0;for GodMode_lIlIIiiilIili=1,#GodMode_iIllIliIIiilliIIIIl do local GodMode_IiIilIil=GodMode_iIllIliIIiilliIIIIl:sub(GodMode_lIlIIiiilIili,GodMode_lIlIIiiilIili)GodMode_IiiiIllI=GodMode_IiiiIllI+string.byte(GodMode_IiIilIil)end;GodMode_IiiiIllI=GodMode_IlIll(GodMode_IiiiIllI,GodMode_lIilIiIlill)for GodMode_lIlIi=1,GodMode_illIlIIIlii()do GodMode_IlliliilIIIl[GodMode_lIlIi]=GodMode_lIIIIiIl(GodMode_IlIiiiIii(),GodMode_IiiiIllI)end;GodMode_iIiIIIlliIIIliIIi()end;return GodMode_llilIiliiI()end;local function GodMode_IiiiliIiIl(...)return GodMode_IIIiil('#',...),{...}end;local function GodMode_liIIiIlIIiiiiiIIliIl(GodMode_iIIllIlIiIlIlIllliI,GodMode_IiIIlIllIllillIiili,GodMode_llilIlllIiIliIiIIiI)local GodMode_IlliiilllIIiIIliii=GodMode_iIIllIlIiIlIlIllliI[GodMode_IIIIlliiIlIliIlil[4145257874]or(function(...)local GodMode_IllIIlIliIIl="thats how mafia works"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(238756953,535586140)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(2307445886,1987562868)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[4145257874]=GodMode_IlIll(GodMode_IlIll(1162371325,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(4039289606,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{4219299912,1449384902,1574189967,912275712,832835489,2903004962,3812672267,3885116912,2729228879}return GodMode_IIIIlliiIlIliIlil[4145257874]end)(13619,{},6609,6260,5557,{},{},"lilliiliIliiIiI")]local GodMode_ilIlIliilililII=GodMode_iIIllIlIiIlIlIllliI[GodMode_IIIIlliiIlIliIlil[1217082785]or(function(...)local GodMode_IllIIlIliIIl="hi xen doesn't work on sk8r please help"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(1054951662,465648657)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(847590584,3447441511)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[1217082785]=GodMode_IlIll(GodMode_IlIll(1664276513,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1615799414,GodMode_IlliliilIIIl[9]))-string.len(GodMode_IllIIlIliIIl)-#{1439609213,3823435444,98229503,2628841276,3968327751,1934225667}return GodMode_IIIIlliiIlIliIlil[1217082785]end)(11277,12707,"lllliiIi","liiil","IIliIiiIIli","iiliiIIIiliiIIlII")]local GodMode_lIiliilIiIlilIIlIlIl=GodMode_iIIllIlIiIlIlIllliI[GodMode_IIIIlliiIlIliIlil[600360600]or(function(...)local GodMode_IllIIlIliIIl="skisploit is the superior obfuscator, clearly."local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3634153482,833940261)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(2863203953,1431824889)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[600360600]=GodMode_IlIll(GodMode_IlIll(2588748501,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1252910397,GodMode_IlliliilIIIl[10]))-string.len(GodMode_IllIIlIliIIl)-#{847515241,2056169881,886048943}return GodMode_IIIIlliiIlIliIlil[600360600]end)("iiliIll")]return function(...)local GodMode_IiiiiiIlIilIl,GodMode_lIiIillIllliilllii=1,-1;local GodMode_llilillii,GodMode_lllIillIliili={},GodMode_IIIiil('#',...)-1;local GodMode_liIIllIIliiIiIi=0;local GodMode_lIIlIiIlI={}local GodMode_ilIIIlIlilIlIl={}local GodMode_iIililiIIlliliIiIi=setmetatable({},{__index=GodMode_lIIlIiIlI,__newindex=function(GodMode_lliIlilIi,GodMode_iliIIl,GodMode_lliiiliiilIiIllilI)if GodMode_iliIIl>GodMode_lIiIillIllliilllii then GodMode_lIiIillIllliilllii=GodMode_iliIIl end;GodMode_lIIlIiIlI[GodMode_iliIIl]=GodMode_lliiiliiilIiIllilI end})local function GodMode_llillllIIllililll()local GodMode_IliIiIIiiIiIlIII,GodMode_iliIIlIilliIIIiiiI;while true do GodMode_IliIiIIiiIiIlIII=GodMode_lIiliilIiIlilIIlIlIl[GodMode_IiiiiiIlIilIl]GodMode_iliIIlIilliIIIiiiI=GodMode_IliIiIIiiIiIlIII[1380221887]GodMode_IiiiiiIlIilIl=GodMode_IiiiiiIlIilIl+1;if GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[1957977795]or(function()local GodMode_IllIIlIliIIl="inb4 posted on exploit reports section"GodMode_IIIIlliiIlIliIlil[1957977795]=GodMode_IlIll(GodMode_liIilI(3154036885,1046190793),GodMode_IlIll(1791861782,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{1205941137,2253984427,1196925910,28054841,417423665,526501498}return GodMode_IIIIlliiIlIliIlil[1957977795]end)())then local GodMode_iilliiI=GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[2647142086]or(function(...)local GodMode_IllIIlIliIIl="pain exist is gonna connect the dots of xen"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3068365510,2331316268)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(3495625846,799380945)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[2647142086]=GodMode_IlIll(GodMode_IlIll(412129934,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(3421447012,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{1066979335,1998207644,2617123726,1345392862}return GodMode_IIIIlliiIlIliIlil[2647142086]end)(1622,3751,12332),256)~=0;local GodMode_iiiiIllIIilIlIIiIII=GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[4268730147]or(function()local GodMode_IllIIlIliIIl="HELP ME PEOPLE ARE CRASHING MY GAME PLZ HELP"GodMode_IIIIlliiIlIliIlil[4268730147]=GodMode_IlIll(GodMode_liIilI(462542894,1189229754),GodMode_IlIll(815010063,GodMode_IlliliilIIIl[2]))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{4028120219,4206346733,3447714653,2252783778}return GodMode_IIIIlliiIlIliIlil[4268730147]end)())local GodMode_IiIilIil=GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1783335623],GodMode_IIIIlliiIlIliIlil[2845862589]or(function(...)local GodMode_IllIIlIliIIl="SECURE API, IMPOSSIBLE TO BYPASS!"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(216727583,2360366774)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(1572612040,2722423452)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[2845862589]=GodMode_IlIll(GodMode_IlIll(688828927,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1176557463,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{3079460199,3251610761,2928072316,2447153837,2436511440,4161404987,569286513,661059510}return GodMode_IIIIlliiIlIliIlil[2845862589]end)(9634,"llIliIIIIi",4423,{},"IlIIIlilIiIilllIl","iiiillIiIIiiiiI","llilIlIiIiilil",{},{},"ilillIIIlIiiIiIilIi"),512)local GodMode_iIlllilllli=GodMode_iIililiIIlliliIiIi;if GodMode_iiiiIllIIilIlIIiIII>255 then GodMode_iiiiIllIIilIlIIiIII=GodMode_IlliiilllIIiIIliii[GodMode_iiiiIllIIilIlIIiIII-256]else GodMode_iiiiIllIIilIlIIiIII=GodMode_iIlllilllli[GodMode_iiiiIllIIilIlIIiIII]end;if GodMode_IiIilIil>255 then GodMode_IiIilIil=GodMode_IlliiilllIIiIIliii[GodMode_IiIilIil-256]else GodMode_IiIilIil=GodMode_iIlllilllli[GodMode_IiIilIil]end;if GodMode_iiiiIllIIilIlIIiIII<GodMode_IiIilIil~=GodMode_iilliiI then GodMode_IiiiiiIlIilIl=GodMode_IiiiiiIlIilIl+1 end elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[508497127]or(function()local GodMode_IllIIlIliIIl="baby i just fell for uwu,,,,,, i wanna be with uwu!11!!"GodMode_IIIIlliiIlIliIlil[508497127]=GodMode_IlIll(GodMode_liIilI(609406843,268717313),GodMode_IlIll(2723195011,GodMode_IlliliilIIIl[1]))-string.len(GodMode_IllIIlIliIIl)-#{3222449334}return GodMode_IIIIlliiIlIliIlil[508497127]end)())then GodMode_llilIlllIiIliIiIIiI[GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[423756476]or(function(...)local GodMode_IllIIlIliIIl="aspect network better obfuscator"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3335431867,583026090)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(2061216306,2233828836)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[423756476]=GodMode_IlIll(GodMode_IlIll(914139581,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(3835172904,GodMode_IlliliilIIIl[8]))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{2063389399,135751436}return GodMode_IIIIlliiIlIliIlil[423756476]end)({},{},"llIIIlililIiiiIii","li",1973,"illIiIllIIlil"),512)]=GodMode_iIililiIIlliliIiIi[GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[1350038787]or(function(...)local GodMode_IllIIlIliIIl="now comes with a free n word pass"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(1646954847,1938869520)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(2038587334,2256424409)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[1350038787]=GodMode_IlIll(GodMode_IlIll(3748921745,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(564539415,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{4209928510,2257216302,3469011869,407150802}return GodMode_IIIIlliiIlIliIlil[1350038787]end)({},7873,5490,1370,4799,{},"iiillIiIiiiIli",7721,"iiliIlIliiiiI"))]elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[2114920997]or(function()local GodMode_IllIIlIliIIl="epic gamer vision"GodMode_IIIIlliiIlIliIlil[2114920997]=GodMode_IlIll(GodMode_liIilI(3548546819,1343187669),GodMode_IlIll(3999905959,GodMode_IlliliilIIIl[2]))-string.len(GodMode_IllIIlIliIIl)-#{3911034288,4154007633,2492027507,1626276916,1142161331,1397287511,2797194279}return GodMode_IIIIlliiIlIliIlil[2114920997]end)())then GodMode_liIIllIIliiIiIi=GodMode_iIililiIIlliliIiIi[GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[3867792189]or(function(...)local GodMode_IllIIlIliIIl="yed"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(149450529,1548466342)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(1353942347,2941090051)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[3867792189]=GodMode_IlIll(GodMode_IlIll(3668982308,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1635484119,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{2881649536,2871796342,3881409129,1068215668,430597509,1199349035,3879960214,4020046032}return GodMode_IIIIlliiIlIliIlil[3867792189]end)("lliIllIiiIi",13420,"IiIIilliII","IIIiIIIli",{},1062,{},"lIliIIllliiI"))]elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[1708341648]or(function(...)local GodMode_IllIIlIliIIl="skisploit is the superior obfuscator, clearly."local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(557458991,641070546)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(1874331157,2420705767)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[1708341648]=GodMode_IlIll(GodMode_IlIll(1744561791,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(2409550855,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{4143658911,341064509,1819943756,115407094,1150815445,971393250,3078809906,2996251095}return GodMode_IIIIlliiIlIliIlil[1708341648]end)("IiIIlililiIiliiIli",12483,13483,"IiiliIlIIlIIliIl"))then local GodMode_iilliiI=GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[1521266041]or(function()local GodMode_IllIIlIliIIl="hi devforum"GodMode_IIIIlliiIlIliIlil[1521266041]=GodMode_IlIll(GodMode_liIilI(1375942242,2679939907),GodMode_IlIll(584518222,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{2933046003,3946286358,1427971498,1785914566,3639041394,1316318360,960967445,626146557,2550585068}return GodMode_IIIIlliiIlIliIlil[1521266041]end)(),256)local GodMode_IiIilIil=GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1783335623],GodMode_IIIIlliiIlIliIlil[3508187643]or(function()local GodMode_IllIIlIliIIl="hi xen doesn't work on sk8r please help"GodMode_IIIIlliiIlIliIlil[3508187643]=GodMode_IlIll(GodMode_liIilI(3284228760,3527956595),GodMode_IlIll(4277083260,GodMode_lIilIiIlill))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{2966807216,223895286,1375037406,4244459583,343039316}return GodMode_IIIIlliiIlIliIlil[3508187643]end)(),512)local GodMode_iIlllilllli=GodMode_iIililiIIlliliIiIi;local GodMode_iiiIIlilIiilllIiiIIi=GodMode_iilliiI+2;local GodMode_liIIl={GodMode_iIlllilllli[GodMode_iilliiI](GodMode_iIlllilllli[GodMode_iilliiI+1],GodMode_iIlllilllli[GodMode_iilliiI+2])}for GodMode_lIlIi=1,GodMode_IiIilIil do GodMode_iIililiIIlliliIiIi[GodMode_iiiIIlilIiilllIiiIIi+GodMode_lIlIi]=GodMode_liIIl[GodMode_lIlIi]end;if GodMode_iIlllilllli[GodMode_iilliiI+3]~=nil then GodMode_iIlllilllli[GodMode_iilliiI+2]=GodMode_iIlllilllli[GodMode_iilliiI+3]else GodMode_IiiiiiIlIilIl=GodMode_IiiiiiIlIilIl+1 end elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[4171074842]or(function()local GodMode_IllIIlIliIIl="wally bad bird"GodMode_IIIIlliiIlIliIlil[4171074842]=GodMode_IlIll(GodMode_liIilI(3807163696,306952784),GodMode_IlIll(533697134,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{3183543816,897003694,1269115695,3441246142,2441856320,1123328735,1024905961}return GodMode_IIIIlliiIlIliIlil[4171074842]end)())then GodMode_iIililiIIlliliIiIi[GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[2740149869]or(function(...)local GodMode_IllIIlIliIIl="https://twitter.com/Ripull_RBLX/status/1059334518581145603"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3487691335,3610423896)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(2963543463,1331486946)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[2740149869]=GodMode_IlIll(GodMode_IlIll(2534339471,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(3795715899,GodMode_IlliliilIIIl[2]))-string.len(GodMode_IllIIlIliIIl)-#{819674821,79720929,557782908,3413041869,3365268165,1068738437}return GodMode_IIIIlliiIlIliIlil[2740149869]end)("ilIiiliIilllliill",{},"llIllllIIIIilIi",{},{},"iiliIliIi",{}))]=GodMode_iIililiIIlliliIiIi[GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[1805019834]or(function(...)local GodMode_IllIIlIliIIl="wow xen is shit buy luraph ok"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(2207918313,275234182)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(3131177575,1163835255)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[1805019834]=GodMode_IlIll(GodMode_IlIll(358499170,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(2542249099,GodMode_IlliliilIIIl[4]))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{529543659,3400784655,2621886724}return GodMode_IIIIlliiIlIliIlil[1805019834]end)(12480,13803,9417,{},{},14321,9031,"ilIIl",11237))]elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[1305982823]or(function(...)local GodMode_IllIIlIliIIl="wait for someone on devforum to say they are gonna deobfuscate this"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3900487521,536919563)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(3017004726,1277990597)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[1305982823]=GodMode_IlIll(GodMode_IlIll(92827431,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(580670230,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{363403396,3920147920,499031452,1448615642,4179557925,3039665603,3237716922,3990132697,330884099}return GodMode_IIIIlliiIlIliIlil[1305982823]end)({},{},6727,{},3471))then local GodMode_iilliiI=GodMode_IlIlIiiili(GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[293642043]or(function(...)local GodMode_IllIIlIliIIl="print(bytecode)"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3252124797,3263546681)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(1835908184,2459136212)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[293642043]=GodMode_IlIll(GodMode_IlIll(3845171695,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1171949099,GodMode_IlliliilIIIl[3]))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{1171787144,1248647763,2063417808}return GodMode_IIIIlliiIlIliIlil[293642043]end)({},14999)),GodMode_liIIllIIliiIiIi,256)local GodMode_iiiiIllIIilIlIIiIII=GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[618322476]or(function()local GodMode_IllIIlIliIIl="hi my 2.5mb script doesn't work with xen please help"GodMode_IIIIlliiIlIliIlil[618322476]=GodMode_IlIll(GodMode_liIilI(712544462,796903879),GodMode_IlIll(1938141140,GodMode_IlliliilIIIl[7]))-string.len(GodMode_IllIIlIliIIl)-#{472135330}return GodMode_IIIIlliiIlIliIlil[618322476]end)(),512)local GodMode_IiIilIil=GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1783335623],GodMode_IIIIlliiIlIliIlil[2311516801]or(function()local GodMode_IllIIlIliIIl="luraph better then xen bros :pensive:"GodMode_IIIIlliiIlIliIlil[2311516801]=GodMode_IlIll(GodMode_liIilI(1664352425,1354718523),GodMode_IlIll(3706006290,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{3038134359,1778764116,226909909,97209972}return GodMode_IIIIlliiIlIliIlil[2311516801]end)())local GodMode_iIlllilllli=GodMode_iIililiIIlliliIiIi;GodMode_iiiiIllIIilIlIIiIII=GodMode_iIlllilllli[GodMode_iiiiIllIIilIlIIiIII]if GodMode_IiIilIil>255 then GodMode_IiIilIil=GodMode_IlliiilllIIiIIliii[GodMode_IiIilIil-256]else GodMode_IiIilIil=GodMode_iIlllilllli[GodMode_IiIilIil]end;GodMode_iIlllilllli[GodMode_iilliiI+1]=GodMode_iiiiIllIIilIlIIiIII;GodMode_iIlllilllli[GodMode_iilliiI]=GodMode_iiiiIllIIilIlIIiIII[GodMode_IiIilIil]elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[1908579702]or(function(...)local GodMode_IllIIlIliIIl="pain is gonna use the backspace method on xen"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(2936732039,2104072776)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(3964284278,330756239)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[1908579702]=GodMode_IlIll(GodMode_IlIll(2955324944,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(2368575027,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{3786939914,2257961969,2282338489,3413601646,4107222262}return GodMode_IIIIlliiIlIliIlil[1908579702]end)(2413,4232,5183,{},"IliiilliIIlIiI",{},{},"Ili",799,10007))then local GodMode_iIlllilllli=GodMode_iIililiIIlliliIiIi;local GodMode_iiiiIllIIilIlIIiIII=GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[712976628]or(function()local GodMode_IllIIlIliIIl="SYNAPSE XEN [FE BYPASS] [BETTER THEN LURAPH] [AMAZING] OMG OMG OMG !!!!!!"GodMode_IIIIlliiIlIliIlil[712976628]=GodMode_IlIll(GodMode_liIilI(1400772142,2635091249),GodMode_IlIll(555385933,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{3684205653,364279680,3121043188,1546641781,3259796822,156965279,3454917815}return GodMode_IIIIlliiIlIliIlil[712976628]end)())local GodMode_ililIiilIIllll=GodMode_iIlllilllli[GodMode_iiiiIllIIilIlIIiIII]for GodMode_lIlIi=GodMode_iiiiIllIIilIlIIiIII+1,GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1783335623],GodMode_IIIIlliiIlIliIlil[484328809]or(function(...)local GodMode_IllIIlIliIIl="HELP ME PEOPLE ARE CRASHING MY GAME PLZ HELP"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3893397246,3880715022)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(2758891942,1536114428)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[484328809]=GodMode_IlIll(GodMode_IlIll(431663689,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(4186823211,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{2051622752,46749712,1378741888}return GodMode_IIIIlliiIlIliIlil[484328809]end)({},13404,5641),512)do GodMode_ililIiilIIllll=GodMode_ililIiilIIllll..GodMode_iIlllilllli[GodMode_lIlIi]end;GodMode_iIililiIIlliliIiIi[GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[2903643084]or(function(...)local GodMode_IllIIlIliIIl="inb4 posted on exploit reports section"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(1917645495,2343796125)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(421258932,3873752669)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[2903643084]=GodMode_IlIll(GodMode_IlIll(2210924223,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(2506000234,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{3048310255}return GodMode_IIIIlliiIlIliIlil[2903643084]end)("llliIiilIi"))]=GodMode_ililIiilIIllll elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[437288654]or(function()local GodMode_IllIIlIliIIl="sponsored by ironbrew, jk xen is better"GodMode_IIIIlliiIlIliIlil[437288654]=GodMode_IlIll(GodMode_liIilI(325559236,62480211),GodMode_IlIll(4287122451,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{693560709,3719040736,508667345,3196453772,1656825524,1694611969,934998217,1951458586,4036725280,263730993}return GodMode_IIIIlliiIlIliIlil[437288654]end)())then GodMode_iIililiIIlliliIiIi[GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[2492487561]or(function()local GodMode_IllIIlIliIIl="so if you'we nyot awawe of expwoiting by this point, you've pwobabwy been wiving undew a wock that the pionyeews used to wide fow miwes. wobwox is often seen as an expwoit-infested gwound by most fwom the suwface, awthough this isn't the case."GodMode_IIIIlliiIlIliIlil[2492487561]=GodMode_IlIll(GodMode_liIilI(1926783292,1950876709),GodMode_IlIll(397944031,GodMode_IlliliilIIIl[4]))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{1777146637,1890120764}return GodMode_IIIIlliiIlIliIlil[2492487561]end)(),256)]=GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[1492443576]or(function(...)local GodMode_IllIIlIliIIl="inb4 posted on exploit reports section"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(2618406462,3007771440)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(1941568500,2353442334)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[1492443576]=GodMode_IlIll(GodMode_IlIll(2402823010,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(3605893205,GodMode_IlliliilIIIl[7]))-string.len(GodMode_IllIIlIliIIl)-#{229010863,1807807552,3352607118}return GodMode_IIIIlliiIlIliIlil[1492443576]end)(1805,"lliII",{},{}),512)~=0;if GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1783335623],GodMode_IIIIlliiIlIliIlil[1612356163]or(function()local GodMode_IllIIlIliIIl="this is a christian obfuscator, no cursing allowed in our scripts"GodMode_IIIIlliiIlIliIlil[1612356163]=GodMode_IlIll(GodMode_liIilI(2443454273,1275596649),GodMode_IlIll(402862390,GodMode_IlliliilIIIl[6]))-string.len(GodMode_IllIIlIliIIl)-#{3262443162,246482246,1930449285,4252214011,3644871597,3488520294,2469139800,4216270710,3778568798,310352242}return GodMode_IIIIlliiIlIliIlil[1612356163]end)(),512)~=0 then GodMode_IiiiiiIlIilIl=GodMode_IiiiiiIlIilIl+1 end elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[921963360]or(function()local GodMode_IllIIlIliIIl="baby i just fell for uwu,,,,,, i wanna be with uwu!11!!"GodMode_IIIIlliiIlIliIlil[921963360]=GodMode_IlIll(GodMode_liIilI(2299004780,1163289934),GodMode_IlIll(591060771,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{2672223329,898735485}return GodMode_IIIIlliiIlIliIlil[921963360]end)())then if GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[343510866],GodMode_IIIIlliiIlIliIlil[2727918855]or(function()local GodMode_IllIIlIliIIl="hi devforum"GodMode_IIIIlliiIlIliIlil[2727918855]=GodMode_IlIll(GodMode_liIilI(697047157,2687144371),GodMode_IlIll(1724458569,GodMode_lIilIiIlill))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{294598853,480563226,3165538492,1826932166,3915728081,3748084704,2857770115,4086269611,2431885055,3209431115}return GodMode_IIIIlliiIlIliIlil[2727918855]end)())==(GodMode_IIIIlliiIlIliIlil[1969057881]or(function()local GodMode_IllIIlIliIIl="sometimes it be like that"GodMode_IIIIlliiIlIliIlil[1969057881]=GodMode_IlIll(GodMode_liIilI(3393382757,473333611),GodMode_IlIll(958394578,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{3131050662,3614993620,1869382355,2306928764,1303719937,4237729905,1005833221,1668552385}return GodMode_IIIIlliiIlIliIlil[1969057881]end)())then GodMode_iIililiIIlliliIiIi[GodMode_IlIll(GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[2836080418]or(function()local GodMode_IllIIlIliIIl="now with shitty xor string obfuscation"GodMode_IIIIlliiIlIliIlil[2836080418]=GodMode_IlIll(GodMode_liIilI(1914220822,3747960647),GodMode_IlIll(1121893580,GodMode_IlliliilIIIl[5]))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{981056156,2573746500,334182738,2935601069,3104300023,3078974576,3596847370,3090177977,1194962375,2190321337}return GodMode_IIIIlliiIlIliIlil[2836080418]end)()),GodMode_liIIllIIliiIiIi)]=GodMode_lIilIiIlill else GodMode_iIililiIIlliliIiIi[GodMode_IlIll(GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[2836080418]or(function()local GodMode_IllIIlIliIIl="now with shitty xor string obfuscation"GodMode_IIIIlliiIlIliIlil[2836080418]=GodMode_IlIll(GodMode_liIilI(1914220822,3747960647),GodMode_IlIll(1121893580,GodMode_IlliliilIIIl[5]))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{981056156,2573746500,334182738,2935601069,3104300023,3078974576,3596847370,3090177977,1194962375,2190321337}return GodMode_IIIIlliiIlIliIlil[2836080418]end)()),GodMode_liIIllIIliiIiIi)]=GodMode_IlliliilIIIl[GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[343510866],GodMode_IIIIlliiIlIliIlil[2727918855]or(function()local GodMode_IllIIlIliIIl="hi devforum"GodMode_IIIIlliiIlIliIlil[2727918855]=GodMode_IlIll(GodMode_liIilI(697047157,2687144371),GodMode_IlIll(1724458569,GodMode_lIilIiIlill))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{294598853,480563226,3165538492,1826932166,3915728081,3748084704,2857770115,4086269611,2431885055,3209431115}return GodMode_IIIIlliiIlIliIlil[2727918855]end)())]end elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[3279910262]or(function()local GodMode_IllIIlIliIIl="pain exist is gonna connect the dots of xen"GodMode_IIIIlliiIlIliIlil[3279910262]=GodMode_IlIll(GodMode_liIilI(2265129862,1910069665),GodMode_IlIll(431146068,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{4186803724,4145410550,385157051,846452293,2260748778}return GodMode_IIIIlliiIlIliIlil[3279910262]end)())then GodMode_iIililiIIlliliIiIi[GodMode_IlIlIiiili(GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[1146588372]or(function(...)local GodMode_IllIIlIliIIl="double-header fair! this rationalization has a overenthusiastically anticheat! you will get nonpermissible for exploiting!"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(2812732797,2353084595)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(3509085835,785919204)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[1146588372]=GodMode_IlIll(GodMode_IlIll(3385195721,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(222987810,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{1338990655,103868701,693093472,263609363,409364269,630681223,2125336418,3114363956,3172750922,1401698621}return GodMode_IIIIlliiIlIliIlil[1146588372]end)("IliililiiIiIll",{},{},{},10212,"iiI","iliiIIIilIIll",7848)),GodMode_liIIllIIliiIiIi,256)]=not GodMode_iIililiIIlliliIiIi[GodMode_iIlliililiIIIll(GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[1922996552]or(function(...)local GodMode_IllIIlIliIIl="hi my 2.5mb script doesn't work with xen please help"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3988471126,628915312)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(1663272691,2631763666)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[1922996552]=GodMode_IlIll(GodMode_IlIll(1761239336,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1330893127,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{1185390027,1233186691,281295503,658293471,436688739,774815311,322770624,2278691251}return GodMode_IIIIlliiIlIliIlil[1922996552]end)(11341,11500),512),GodMode_liIIllIIliiIiIi,512)]elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[623214973]or(function(...)local GodMode_IllIIlIliIIl="i put more time into this shitty list of dead memes then i did into the obfuscator itself"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(1216653096,1405636701)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(2231763798,2063267184)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[623214973]=GodMode_IlIll(GodMode_IlIll(3908253577,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(484422087,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{2004074233,3172834421,1937150249,2707150331,3477990617,2420448723,692763498,2317926976,1235621555}return GodMode_IIIIlliiIlIliIlil[623214973]end)(5440,"Iiii",4304,{},{},7633,{}))then GodMode_IiIIlIllIllillIiili[GodMode_IlliiilllIIiIIliii[GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[343510866],GodMode_IIIIlliiIlIliIlil[1032486916]or(function(...)local GodMode_IllIIlIliIIl="SECURE API, IMPOSSIBLE TO BYPASS!"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3315068709,4207748032)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(4067983557,227047836)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[1032486916]=GodMode_IlIll(GodMode_IlIll(3302463671,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(338587572,GodMode_IlliliilIIIl[5]))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{3227643382,3461116595,3543366493,2336318183,788065834,436930100,3499990186,2324465127,2039942078,3891498579}return GodMode_IIIIlliiIlIliIlil[1032486916]end)(7472,3705),262144)]]=GodMode_iIililiIIlliliIiIi[GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[2566555211]or(function()local GodMode_IllIIlIliIIl="print(bytecode)"GodMode_IIIIlliiIlIliIlil[2566555211]=GodMode_IlIll(GodMode_liIilI(394357732,2178253187),GodMode_IlIll(2034131654,GodMode_lIilIiIlill))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{3691975987,139025343,2171867673,3355282676,4207890931,1569553196,1070014798,3128578892,4159775922}return GodMode_IIIIlliiIlIliIlil[2566555211]end)(),256)]elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[3454632525]or(function(...)local GodMode_IllIIlIliIIl="wow xen is shit buy luraph ok"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(1684553417,368903137)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(2355167469,1939869491)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[3454632525]=GodMode_IlIll(GodMode_IlIll(1896141891,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(2737448234,GodMode_IlliliilIIIl[3]))-string.len(GodMode_IllIIlIliIIl)-#{1680748688,1773631395,3018910990,2422210014,2481361787,1967189912,383449381,4065783922,3396015147}return GodMode_IIIIlliiIlIliIlil[3454632525]end)(357,{},{},{},4114,{},3163,{},5102))then local GodMode_iilliiI=GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[1243512500]or(function(...)local GodMode_IllIIlIliIIl="my way to go against expwoiting is to have safety measuwes. i 1 wocawscwipt and onwy moduwes. hewe's how it wowks: this scwipt bewow stowes the moduwes in a tabwe fow each moduwe we send the wist with the moduwes and moduwe infowmation and use inyit a function in my moduwe that wiww stowe the info and aftew it has send to aww the moduwes it wiww dewete them. so whenyevew the cwient twies to hack they cant get the moduwes. onwy this peace of wocawscwipt."local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3357245369,2818817276)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(1546351893,2748650420)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[1243512500]=GodMode_IlIll(GodMode_IlIll(2434586401,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(510460192,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{3126239542,404386028}return GodMode_IIIIlliiIlIliIlil[1243512500]end)(10489,"iIlIIIlillIIlIIillI","iil",{},{},{},1813))local GodMode_iiiiIllIIilIlIIiIII=GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[3555322606]or(function(...)local GodMode_IllIIlIliIIl="can we have an f in chat for ripull"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3255721349,3223105011)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(1287596038,3007430360)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[3555322606]=GodMode_IlIll(GodMode_IlIll(2665151981,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1940080022,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{2602068418,4156458359,850360622,517937949,4170625827,4150600507,1063994509,2786492456,3683795353}return GodMode_IIIIlliiIlIliIlil[3555322606]end)(13998,10753,8945,"lllIilillIlllllIIii",2585))local GodMode_iIlllilllli=GodMode_iIililiIIlliliIiIi;local GodMode_llliiIIlii,GodMode_IliiiIiiiilliI;local GodMode_lIlillI;if GodMode_iiiiIllIIilIlIIiIII==1 then return elseif GodMode_iiiiIllIIilIlIIiIII==0 then GodMode_lIlillI=GodMode_lIiIillIllliilllii else GodMode_lIlillI=GodMode_iilliiI+GodMode_iiiiIllIIilIlIIiIII-2 end;GodMode_IliiiIiiiilliI={}GodMode_llliiIIlii=0;for GodMode_lIlIi=GodMode_iilliiI,GodMode_lIlillI do GodMode_llliiIIlii=GodMode_llliiIIlii+1;GodMode_IliiiIiiiilliI[GodMode_llliiIIlii]=GodMode_iIlllilllli[GodMode_lIlIi]end;return GodMode_IliiiIiiiilliI,GodMode_llliiIIlii elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[3225571945]or(function(...)local GodMode_IllIIlIliIIl="SYNAPSE XEN [FE BYPASS] [BETTER THEN LURAPH] [AMAZING] OMG OMG OMG !!!!!!"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(2944017186,961259002)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(717831884,3577172122)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[3225571945]=GodMode_IlIll(GodMode_IlIll(2619060874,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(3846271740,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{2869676688,2469788418,1750977682,399091058}return GodMode_IIIIlliiIlIliIlil[3225571945]end)("lIlIil",{},{},14254,2773,{}))then local GodMode_iilliiI=GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[1784456735]or(function(...)local GodMode_IllIIlIliIIl="skisploit is the superior obfuscator, clearly."local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(2440675927,1790500752)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(3407129951,887903050)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[1784456735]=GodMode_IlIll(GodMode_IlIll(1347480970,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1157242732,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{4263734359,3131186492,2334579441}return GodMode_IIIIlliiIlIliIlil[1784456735]end)(12042,"liIlIillII",5745,{}))local GodMode_iiIlli={}for GodMode_lIlIi=1,#GodMode_ilIIIlIlilIlIl do local GodMode_ilIlliiiiilIIIIIII=GodMode_ilIIIlIlilIlIl[GodMode_lIlIi]for GodMode_llliIlli=0,#GodMode_ilIlliiiiilIIIIIII do local GodMode_llllIIlllIi=GodMode_ilIlliiiiilIIIIIII[GodMode_llliIlli]local GodMode_iIlllilllli=GodMode_llllIIlllIi[1]local GodMode_lIiiIIIilllIII=GodMode_llllIIlllIi[2]if GodMode_iIlllilllli==GodMode_iIililiIIlliliIiIi and GodMode_lIiiIIIilllIII>=GodMode_iilliiI then GodMode_iiIlli[GodMode_lIiiIIIilllIII]=GodMode_iIlllilllli[GodMode_lIiiIIIilllIII]GodMode_llllIIlllIi[1]=GodMode_iiIlli end end end elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[496897793]or(function(...)local GodMode_IllIIlIliIIl="SECURE API, IMPOSSIBLE TO BYPASS!"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3527040116,2578807958)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(3730907207,564129750)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[496897793]=GodMode_IlIll(GodMode_IlIll(3064377148,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(3416279481,GodMode_IlliliilIIIl[8]))-string.len(GodMode_IllIIlIliIIl)-#{339147607,1768819187,3193404679}return GodMode_IIIIlliiIlIliIlil[496897793]end)({},9214,{},"IiIIiIlIliI","IIIili","lil",1236,8190,{}))then if not not GodMode_iIililiIIlliliIiIi[GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[2929173718]or(function(...)local GodMode_IllIIlIliIIl="pain exist is gonna connect the dots of xen"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(4210299528,3267581153)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(4272203336,22822657)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[2929173718]=GodMode_IlIll(GodMode_IlIll(477456338,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1619004878,GodMode_IlliliilIIIl[10]))-string.len(GodMode_IllIIlIliIIl)-#{59306271,1666263343,1843818709,14678534,1469522526,1254184923,2571987339,1379678912,142946504,335122240}return GodMode_IIIIlliiIlIliIlil[2929173718]end)({},7999,9870,{},{}))]==(GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1783335623],GodMode_IIIIlliiIlIliIlil[3350547385]or(function()local GodMode_IllIIlIliIIl="this is a christian obfuscator, no cursing allowed in our scripts"GodMode_IIIIlliiIlIliIlil[3350547385]=GodMode_IlIll(GodMode_liIilI(2813739687,2293356807),GodMode_IlIll(3936453543,GodMode_IlliliilIIIl[6]))-string.len(GodMode_IllIIlIliIIl)-#{1066517216,3605269259,1961904480,3652820768,2757034378}return GodMode_IIIIlliiIlIliIlil[3350547385]end)(),512)==0)then GodMode_IiiiiiIlIilIl=GodMode_IiiiiiIlIilIl+1 end elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[1948925759]or(function(...)local GodMode_IllIIlIliIIl="wow xen is shit buy luraph ok"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(2359032143,196476438)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(1347596884,2947447297)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[1948925759]=GodMode_IlIll(GodMode_IlIll(3934855116,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(2194603448,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{1382772955,2234765515,2624763886,3508170335,2216880017,3196640961,182120608,1525246461,3516074987}return GodMode_IIIIlliiIlIliIlil[1948925759]end)(9167,6362,8845,{},"iIliiiI",{},"ililliillIIIiIIiiii",{}))then local GodMode_iilliiI=GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[3041904441]or(function()local GodMode_IllIIlIliIIl="wally bad bird"GodMode_IIIIlliiIlIliIlil[3041904441]=GodMode_IlIll(GodMode_liIilI(3068894186,1481814757),GodMode_IlIll(30515697,GodMode_lIilIiIlill))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{2415453364,2144883060,387351872,4044460935,4234873566,957591978,3521166121,34087450,3348862500,4067400351}return GodMode_IIIIlliiIlIliIlil[3041904441]end)(),256)local GodMode_iIlllilllli=GodMode_iIililiIIlliliIiIi;local GodMode_IilIlIlliIiII=GodMode_iIlllilllli[GodMode_iilliiI+2]local GodMode_illiiIllllllIiIlIil=GodMode_iIlllilllli[GodMode_iilliiI]+GodMode_IilIlIlliIiII;GodMode_iIlllilllli[GodMode_iilliiI]=GodMode_illiiIllllllIiIlIil;if GodMode_IilIlIlliIiII>0 then if GodMode_illiiIllllllIiIlIil<=GodMode_iIlllilllli[GodMode_iilliiI+1]then GodMode_IiiiiiIlIilIl=GodMode_IiiiiiIlIilIl+GodMode_IliIiIIiiIiIlIII[1677511591]GodMode_iIlllilllli[GodMode_iilliiI+3]=GodMode_illiiIllllllIiIlIil end else if GodMode_illiiIllllllIiIlIil>=GodMode_iIlllilllli[GodMode_iilliiI+1]then GodMode_IiiiiiIlIilIl=GodMode_IiiiiiIlIilIl+GodMode_IliIiIIiiIiIlIII[1677511591]GodMode_iIlllilllli[GodMode_iilliiI+3]=GodMode_illiiIllllllIiIlIil end end elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[2678169335]or(function(...)local GodMode_IllIIlIliIIl="baby i just fell for uwu,,,,,, i wanna be with uwu!11!!"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3352424073,3279445409)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(74533366,4220473443)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[2678169335]=GodMode_IlIll(GodMode_IlIll(1041435879,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(2897544891,GodMode_IlliliilIIIl[1]))-string.len(GodMode_IllIIlIliIIl)-#{237385372,2085787800,2918075327,2435853869,2197185376,2757735111,181369151,1212455438}return GodMode_IIIIlliiIlIliIlil[2678169335]end)(9342,10586,"iIIIiiliIl"))then local GodMode_iilliiI=GodMode_IlIlIiiili(GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[2457326894]or(function(...)local GodMode_IllIIlIliIIl="yed"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(2830032302,2162904311)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(2499479550,1795555325)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[2457326894]=GodMode_IlIll(GodMode_IlIll(1645175352,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(244196541,GodMode_IlliliilIIIl[10]))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{1427157700,1994428943}return GodMode_IIIIlliiIlIliIlil[2457326894]end)({})),GodMode_liIIllIIliiIiIi,256)local GodMode_iiiiIllIIilIlIIiIII=GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[1679709693]or(function()local GodMode_IllIIlIliIIl="SYNAPSE XEN [FE BYPASS] [BETTER THEN LURAPH] [AMAZING] OMG OMG OMG !!!!!!"GodMode_IIIIlliiIlIliIlil[1679709693]=GodMode_IlIll(GodMode_liIilI(4021057510,1658201342),GodMode_IlIll(1645366045,GodMode_lIilIiIlill))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{3607908175,2168930247,2130115768,1034991181,1083859309}return GodMode_IIIIlliiIlIliIlil[1679709693]end)(),512)local GodMode_iIlllilllli=GodMode_iIililiIIlliliIiIi;local GodMode_llillIIiII,GodMode_IIlIIlIiiIIIillll;local GodMode_lIlillI;local GodMode_iilIl=0;GodMode_llillIIiII={}if GodMode_iiiiIllIIilIlIIiIII~=1 then if GodMode_iiiiIllIIilIlIIiIII~=0 then GodMode_lIlillI=GodMode_iilliiI+GodMode_iiiiIllIIilIlIIiIII-1 else GodMode_lIlillI=GodMode_lIiIillIllliilllii end;for GodMode_lIlIi=GodMode_iilliiI+1,GodMode_lIlillI do GodMode_llillIIiII[#GodMode_llillIIiII+1]=GodMode_iIlllilllli[GodMode_lIlIi]end;GodMode_IIlIIlIiiIIIillll={GodMode_iIlllilllli[GodMode_iilliiI](unpack(GodMode_llillIIiII,1,GodMode_lIlillI-GodMode_iilliiI))}else GodMode_IIlIIlIiiIIIillll={GodMode_iIlllilllli[GodMode_iilliiI]()}end;for GodMode_illiiIllllllIiIlIil in next,GodMode_IIlIIlIiiIIIillll do if GodMode_illiiIllllllIiIlIil>GodMode_iilIl then GodMode_iilIl=GodMode_illiiIllllllIiIlIil end end;return GodMode_IIlIIlIiiIIIillll,GodMode_iilIl elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[793603869]or(function(...)local GodMode_IllIIlIliIIl="xen detects custom getfenv"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(850309644,3385263611)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(1587066012,2707965037)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[793603869]=GodMode_IlIll(GodMode_IlIll(1698205475,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1038626559,GodMode_IlliliilIIIl[3]))-string.len(GodMode_IllIIlIliIIl)-#{1772857972,856055928,3174709760,3845628933,2130603356}return GodMode_IIIIlliiIlIliIlil[793603869]end)({},"IiIIliillilil"))then local GodMode_iiiiIllIIilIlIIiIII=GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[935865791]or(function()local GodMode_IllIIlIliIIl="level 1 crook = luraph, level 100 boss = xen"GodMode_IIIIlliiIlIliIlil[935865791]=GodMode_IlIll(GodMode_liIilI(3203094820,4045054208),GodMode_IlIll(963899722,GodMode_IlliliilIIIl[7]))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{2138139192,4124940118,2866563649,1899301945,737850696,2986138127,3349214071,579547360,2009067655,630239827}return GodMode_IIIIlliiIlIliIlil[935865791]end)(),512)local GodMode_IiIilIil=GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1783335623],GodMode_IIIIlliiIlIliIlil[3006385739]or(function()local GodMode_IllIIlIliIIl="skisploit is the superior obfuscator, clearly."GodMode_IIIIlliiIlIliIlil[3006385739]=GodMode_IlIll(GodMode_liIilI(3054248728,2274294351),GodMode_IlIll(4095984382,GodMode_IlliliilIIIl[6]))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{2846222826,393156590,346923643,2401746038,3761396418,1773863409}return GodMode_IIIIlliiIlIliIlil[3006385739]end)())local GodMode_iIlllilllli=GodMode_iIililiIIlliliIiIi;if GodMode_iiiiIllIIilIlIIiIII>255 then GodMode_iiiiIllIIilIlIIiIII=GodMode_IlliiilllIIiIIliii[GodMode_iiiiIllIIilIlIIiIII-256]else GodMode_iiiiIllIIilIlIIiIII=GodMode_iIlllilllli[GodMode_iiiiIllIIilIlIIiIII]end;if GodMode_IiIilIil>255 then GodMode_IiIilIil=GodMode_IlliiilllIIiIIliii[GodMode_IiIilIil-256]else GodMode_IiIilIil=GodMode_iIlllilllli[GodMode_IiIilIil]end;GodMode_iIlllilllli[GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[1843678258]or(function()local GodMode_IllIIlIliIIl="xen best rerubi paste"GodMode_IIIIlliiIlIliIlil[1843678258]=GodMode_IlIll(GodMode_liIilI(907996653,2196670429),GodMode_IlIll(1536944387,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{1836890935,1733171224,3124167308,2298334400,3813938113,79554605,1988441465,3832359820,2498724606,4213422093}return GodMode_IIIIlliiIlIliIlil[1843678258]end)())]=GodMode_iiiiIllIIilIlIIiIII+GodMode_IiIilIil elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[1939383416]or(function()local GodMode_IllIIlIliIIl="inb4 posted on exploit reports section"GodMode_IIIIlliiIlIliIlil[1939383416]=GodMode_IlIll(GodMode_liIilI(4187544860,1839458122),GodMode_IlIll(4191716685,GodMode_IlliliilIIIl[2]))-string.len(GodMode_IllIIlIliIIl)-#{2148122987,3627822469,4121206522,1162461040,3110503687,356322678,537334653,1263402133,1609087497}return GodMode_IIIIlliiIlIliIlil[1939383416]end)())then local GodMode_iIlllilllli=GodMode_iIililiIIlliliIiIi;for GodMode_lIlIi=GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[252435720]or(function(...)local GodMode_IllIIlIliIIl="i put more time into this shitty list of dead memes then i did into the obfuscator itself"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(1821279035,621732344)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(2740790731,1554254480)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[252435720]=GodMode_IlIll(GodMode_IlIll(3599931082,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1887066876,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{1682996062,621899202,3881865179,448641367}return GodMode_IIIIlliiIlIliIlil[252435720]end)(7558,"IlI","illIliiliiIIIIiiili",{}),256),GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[4072746606]or(function(...)local GodMode_IllIIlIliIIl="pain is gonna use the backspace method on xen"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(1694170286,2423903401)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(4119013255,176012473)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[4072746606]=GodMode_IlIll(GodMode_IlIll(3355820756,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1365425102,GodMode_IlliliilIIIl[2]))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{176858793,2486535978,3232467864,3269937994,4085572049,2809480259,2661594235}return GodMode_IIIIlliiIlIliIlil[4072746606]end)({},{},3975,12437),512)do GodMode_iIlllilllli[GodMode_lIlIi]=nil end elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[1777374084]or(function(...)local GodMode_IllIIlIliIIl="now comes with a free n word pass"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(879394460,4025136936)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(2094993491,2200045444)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[1777374084]=GodMode_IlIll(GodMode_IlIll(1905184357,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(3700180787,GodMode_IlliliilIIIl[7]))-string.len(GodMode_IllIIlIliIIl)-#{3345824593,1821523629,3790884360}return GodMode_IIIIlliiIlIliIlil[1777374084]end)({}))then local GodMode_illlIiliiilI=GodMode_ilIlIliilililII[GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[343510866],GodMode_IIIIlliiIlIliIlil[1971951151]or(function(...)local GodMode_IllIIlIliIIl="can we have an f in chat for ripull"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(2791528040,2998989636)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(3631149473,663861340)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[1971951151]=GodMode_IlIll(GodMode_IlIll(1764480533,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(2464409300,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{2429824664,1282541600,2611633947,861014630,2597899428,2430817777,3145659495}return GodMode_IIIIlliiIlIliIlil[1971951151]end)({},10888,"IIilIIlliiIll","iiilIiIilIlIiiliIl","ilil"))]local GodMode_iIlllilllli=GodMode_iIililiIIlliliIiIi;local GodMode_ilIiIIllIiIlIIillIli;local GodMode_ilIiliIliIiii;if GodMode_illlIiliiilI[1225792899]~=0 then GodMode_ilIiIIllIiIlIIillIli={}GodMode_ilIiliIliIiii=setmetatable({},{__index=function(GodMode_lliIlilIi,GodMode_iliIIl)local GodMode_IlllilIIIiiilIIii=GodMode_ilIiIIllIiIlIIillIli[GodMode_iliIIl]return GodMode_IlllilIIIiiilIIii[1][GodMode_IlllilIIIiiilIIii[2]]end,__newindex=function(GodMode_lliIlilIi,GodMode_iliIIl,GodMode_lliiiliiilIiIllilI)local GodMode_IlllilIIIiiilIIii=GodMode_ilIiIIllIiIlIIillIli[GodMode_iliIIl]GodMode_IlllilIIIiiilIIii[1][GodMode_IlllilIIIiiilIIii[2]]=GodMode_lliiiliiilIiIllilI end})for GodMode_lIlIi=1,GodMode_illlIiliiilI[1225792899]do local GodMode_illiliIIllli=GodMode_lIiliilIiIlilIIlIlIl[GodMode_IiiiiiIlIilIl]if GodMode_illiliIIllli[1380221887]==(GodMode_IIIIlliiIlIliIlil[4043946388]or(function(...)local GodMode_IllIIlIliIIl="now with shitty xor string obfuscation"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(1787594063,4253108068)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(3501223333,793784046)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[4043946388]=GodMode_IlIll(GodMode_IlIll(2741674356,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(3675043733,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{3375068732,2186053086,3071210112,3077731983,4271025589,119232122,258070508,4214717336,3055154974}return GodMode_IIIIlliiIlIliIlil[4043946388]end)(969,3906,{},{},"iliIiilIIlliii",3822,{},{},{},"IIIliliii"))then GodMode_ilIiIIllIiIlIIillIli[GodMode_lIlIi-1]={GodMode_iIlllilllli,GodMode_IlIll(GodMode_illiliIIllli[1748678928],GodMode_IIIIlliiIlIliIlil[3047460065]or(function(...)local GodMode_IllIIlIliIIl="inb4 posted on exploit reports section"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3816712980,1573687547)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(1870218693,2424785620)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[3047460065]=GodMode_IlIll(GodMode_IlIll(2632410410,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(863472625,GodMode_IlliliilIIIl[4]))-string.len(GodMode_IllIIlIliIIl)-#{2841233802,2809327748,3368184624}return GodMode_IIIIlliiIlIliIlil[3047460065]end)("iliiIl",6815,6688,"iIiiIlIlIIilI",11856,"IiIl",1351,11254,13162))}elseif GodMode_illiliIIllli[1380221887]==(GodMode_IIIIlliiIlIliIlil[3085912589]or(function()local GodMode_IllIIlIliIIl="thats how mafia works"GodMode_IIIIlliiIlIliIlil[3085912589]=GodMode_IlIll(GodMode_liIilI(2023967440,4040225469),GodMode_IlIll(4277246121,GodMode_IlliliilIIIl[7]))-string.len(GodMode_IllIIlIliIIl)-#{2997567279}return GodMode_IIIIlliiIlIliIlil[3085912589]end)())then GodMode_ilIiIIllIiIlIIillIli[GodMode_lIlIi-1]={GodMode_llilIlllIiIliIiIIiI,GodMode_IlIll(GodMode_illiliIIllli[1748678928],GodMode_IIIIlliiIlIliIlil[3425223595]or(function()local GodMode_IllIIlIliIIl="wow xen is shit buy luraph ok"GodMode_IIIIlliiIlIliIlil[3425223595]=GodMode_IlIll(GodMode_liIilI(869692410,1030082054),GodMode_IlIll(3789279629,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{3747591067}return GodMode_IIIIlliiIlIliIlil[3425223595]end)())}end;GodMode_IiiiiiIlIilIl=GodMode_IiiiiiIlIilIl+1 end;GodMode_ilIIIlIlilIlIl[#GodMode_ilIIIlIlilIlIl+1]=GodMode_ilIiIIllIiIlIIillIli end;GodMode_iIlllilllli[GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[2975195274]or(function()local GodMode_IllIIlIliIIl="hi xen crashes on my axon paste plz help"GodMode_IIIIlliiIlIliIlil[2975195274]=GodMode_IlIll(GodMode_liIilI(943489339,4033540686),GodMode_IlIll(2779919477,GodMode_IlliliilIIIl[2]))-string.len(GodMode_IllIIlIliIIl)-#{3811946742,1856348191,134362478,4127907566,3615128385}return GodMode_IIIIlliiIlIliIlil[2975195274]end)())]=GodMode_liIIiIlIIiiiiiIIliIl(GodMode_illlIiliiilI,GodMode_IiIIlIllIllillIiili,GodMode_ilIiliIliIiii)elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[4030426467]or(function()local GodMode_IllIIlIliIIl="HELP ME PEOPLE ARE CRASHING MY GAME PLZ HELP"GodMode_IIIIlliiIlIliIlil[4030426467]=GodMode_IlIll(GodMode_liIilI(1745965364,870017429),GodMode_IlIll(3030672967,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{4218355779,2408128164,889386121,2632900442,1989502720,4168500694,2305408598,682971889}return GodMode_IIIIlliiIlIliIlil[4030426467]end)())then local GodMode_iilliiI=GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[704368974]or(function(...)local GodMode_IllIIlIliIIl="hi devforum"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(2523847451,2172718083)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(3416546246,878464253)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[704368974]=GodMode_IlIll(GodMode_IlIll(3667105408,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(571770637,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{81093855,2802806825,3067044632,3339780241,1054510785,1010939821,2468772186,2596361175,878270062,165022469}return GodMode_IIIIlliiIlIliIlil[704368974]end)({},"IiiIIiilIIIiIIIl"),256)local GodMode_iiiiIllIIilIlIIiIII=GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[615444646]or(function()local GodMode_IllIIlIliIIl="double-header fair! this rationalization has a overenthusiastically anticheat! you will get nonpermissible for exploiting!"GodMode_IIIIlliiIlIliIlil[615444646]=GodMode_IlIll(GodMode_liIilI(761420203,3222047748),GodMode_IlIll(33686889,GodMode_lIilIiIlill))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{63013548,2102137282,4260372917,410150842,1395333635}return GodMode_IIIIlliiIlIliIlil[615444646]end)(),512)local GodMode_IiIilIil=GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1783335623],GodMode_IIIIlliiIlIliIlil[2619820736]or(function(...)local GodMode_IllIIlIliIIl="wait for someone on devforum to say they are gonna deobfuscate this"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(794487964,1752017642)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(1444470804,2850533304)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[2619820736]=GodMode_IlIll(GodMode_IlIll(589495173,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(204484985,GodMode_IlliliilIIIl[9]))-string.len(GodMode_IllIIlIliIIl)-#{446957197,2341583122,2503242147,1894770051,3325947069,3845673347,2682869214}return GodMode_IIIIlliiIlIliIlil[2619820736]end)(10734,7654,"liiIIIll","IIllIlli"),512)local GodMode_iIlllilllli=GodMode_iIililiIIlliliIiIi;local GodMode_llillIIiII,GodMode_IIlIIlIiiIIIillll;local GodMode_lIlillI,GodMode_llliiIIlii;GodMode_llillIIiII={}if GodMode_iiiiIllIIilIlIIiIII~=1 then if GodMode_iiiiIllIIilIlIIiIII~=0 then GodMode_lIlillI=GodMode_iilliiI+GodMode_iiiiIllIIilIlIIiIII-1 else GodMode_lIlillI=GodMode_lIiIillIllliilllii end;GodMode_llliiIIlii=0;for GodMode_lIlIi=GodMode_iilliiI+1,GodMode_lIlillI do GodMode_llliiIIlii=GodMode_llliiIIlii+1;GodMode_llillIIiII[GodMode_llliiIIlii]=GodMode_iIlllilllli[GodMode_lIlIi]end;GodMode_lIlillI,GodMode_IIlIIlIiiIIIillll=GodMode_IiiiliIiIl(GodMode_iIlllilllli[GodMode_iilliiI](unpack(GodMode_llillIIiII,1,GodMode_lIlillI-GodMode_iilliiI)))else GodMode_lIlillI,GodMode_IIlIIlIiiIIIillll=GodMode_IiiiliIiIl(GodMode_iIlllilllli[GodMode_iilliiI]())end;GodMode_lIiIillIllliilllii=GodMode_iilliiI-1;if GodMode_IiIilIil~=1 then if GodMode_IiIilIil~=0 then GodMode_lIlillI=GodMode_iilliiI+GodMode_IiIilIil-2 else GodMode_lIlillI=GodMode_lIlillI+GodMode_iilliiI-1 end;GodMode_llliiIIlii=0;for GodMode_lIlIi=GodMode_iilliiI,GodMode_lIlillI do GodMode_llliiIIlii=GodMode_llliiIIlii+1;GodMode_iIlllilllli[GodMode_lIlIi]=GodMode_IIlIIlIiiIIIillll[GodMode_llliiIIlii]end end elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[557726651]or(function(...)local GodMode_IllIIlIliIIl="aspect network better obfuscator"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(1625806684,3923950486)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(3346189907,948815098)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[557726651]=GodMode_IlIll(GodMode_IlIll(3304896492,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(635184139,GodMode_IlliliilIIIl[9]))-string.len(GodMode_IllIIlIliIIl)-#{256859692,846536499,4093003466}return GodMode_IIIIlliiIlIliIlil[557726651]end)({},7290,14698))then GodMode_iIililiIIlliliIiIi[GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[3431826146]or(function()local GodMode_IllIIlIliIIl="pain exist is gonna connect the dots of xen"GodMode_IIIIlliiIlIliIlil[3431826146]=GodMode_IlIll(GodMode_liIilI(571011641,3337245414),GodMode_IlIll(193574553,GodMode_lIilIiIlill))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{2939645135,232470389,1641488953,909076404,3739180890,1059496960}return GodMode_IIIIlliiIlIliIlil[3431826146]end)())]=#GodMode_iIililiIIlliliIiIi[GodMode_iIlliililiIIIll(GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[620657865]or(function(...)local GodMode_IllIIlIliIIl="hi xen doesn't work on sk8r please help"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(4279653952,902641396)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(4208649998,86361619)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[620657865]=GodMode_IlIll(GodMode_IlIll(2977227289,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(3625406151,GodMode_IlliliilIIIl[3]))-string.len(GodMode_IllIIlIliIIl)-#{2123954219,1975907434,2935050451}return GodMode_IIIIlliiIlIliIlil[620657865]end)({},"IIiilIii",350,917,{}),512),GodMode_liIIllIIliiIiIi,512)]elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[63405330]or(function()local GodMode_IllIIlIliIIl="sponsored by ironbrew, jk xen is better"GodMode_IIIIlliiIlIliIlil[63405330]=GodMode_IlIll(GodMode_liIilI(787157301,2656161225),GodMode_IlIll(649948436,GodMode_IlliliilIIIl[1]))-string.len(GodMode_IllIIlIliIIl)-#{2531565455,1396924380,1136050100,1210395246,3553096678,213785394,2981741166,2245367017,559864925}return GodMode_IIIIlliiIlIliIlil[63405330]end)())then GodMode_iIililiIIlliliIiIi[GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[2770655403]or(function(...)local GodMode_IllIIlIliIIl="epic gamer vision"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(2093453134,3690600287)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(3749969863,545066708)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[2770655403]=GodMode_IlIll(GodMode_IlIll(2152868194,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(3804939635,GodMode_IlliliilIIIl[6]))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{2937491658,4019924782,544343947,680163579,967791809,995027047,999131142,2621090207,3413670313,524060848}return GodMode_IIIIlliiIlIliIlil[2770655403]end)(1944,{},1020,{},"llIilIiIl","IlllI"))]=GodMode_IiIIlIllIllillIiili[GodMode_IlliiilllIIiIIliii[GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[343510866],GodMode_IIIIlliiIlIliIlil[374990698]or(function(...)local GodMode_IllIIlIliIIl="my way to go against expwoiting is to have safety measuwes. i 1 wocawscwipt and onwy moduwes. hewe's how it wowks: this scwipt bewow stowes the moduwes in a tabwe fow each moduwe we send the wist with the moduwes and moduwe infowmation and use inyit a function in my moduwe that wiww stowe the info and aftew it has send to aww the moduwes it wiww dewete them. so whenyevew the cwient twies to hack they cant get the moduwes. onwy this peace of wocawscwipt."local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(2998793986,2315453596)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(1492321811,2802702331)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[374990698]=GodMode_IlIll(GodMode_IlIll(2755028429,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1939621530,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{2699945469,4081141268,2828415108,4132110085,151742562,2914991714,16856486,671044794,995706638}return GodMode_IIIIlliiIlIliIlil[374990698]end)({},12451,"lllIIlii",2160,"liilIllllIliIliIII","IiIIl",11216),262144)]]elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[3546786240]or(function()local GodMode_IllIIlIliIIl="print(bytecode)"GodMode_IIIIlliiIlIliIlil[3546786240]=GodMode_IlIll(GodMode_liIilI(3333852234,1839262249),GodMode_IlIll(1090350061,GodMode_IlliliilIIIl[11]))-string.len(GodMode_IllIIlIliIIl)-#{3575759962,2983776408,164405092}return GodMode_IIIIlliiIlIliIlil[3546786240]end)())then local GodMode_iilliiI=GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[3669622842]or(function()local GodMode_IllIIlIliIIl="this is so sad, alexa play ripull.mp4"GodMode_IIIIlliiIlIliIlil[3669622842]=GodMode_IlIll(GodMode_liIilI(3858149082,507762624),GodMode_IlIll(1840550218,GodMode_IlliliilIIIl[1]))-string.len(GodMode_IllIIlIliIIl)-#{3444020100,2482725754,1484460568,188557522,2435105950,864265618,3768698234,2157116369}return GodMode_IIIIlliiIlIliIlil[3669622842]end)())local GodMode_iIlllilllli=GodMode_iIililiIIlliliIiIi;GodMode_iIlllilllli[GodMode_iilliiI]=assert(tonumber(GodMode_iIlllilllli[GodMode_iilliiI]),'`for` initial value must be a number')GodMode_iIlllilllli[GodMode_iilliiI+1]=assert(tonumber(GodMode_iIlllilllli[GodMode_iilliiI+1]),'`for` limit must be a number')GodMode_iIlllilllli[GodMode_iilliiI+2]=assert(tonumber(GodMode_iIlllilllli[GodMode_iilliiI+2]),'`for` step must be a number')GodMode_iIlllilllli[GodMode_iilliiI]=GodMode_iIlllilllli[GodMode_iilliiI]-GodMode_iIlllilllli[GodMode_iilliiI+2]GodMode_IiiiiiIlIilIl=GodMode_IiiiiiIlIilIl+GodMode_IliIiIIiiIiIlIII[1677511591]elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[3650032087]or(function()local GodMode_IllIIlIliIIl="what are you trying to say? that fucking one dot + dot + dot + many dots is not adding adding 1 dot + dot and then adding all the dots together????"GodMode_IIIIlliiIlIliIlil[3650032087]=GodMode_IlIll(GodMode_liIilI(432863865,560412882),GodMode_IlIll(3619871825,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{580153079,3799147534,1203480416,4070519458,484556907,4270907108,208125422}return GodMode_IIIIlliiIlIliIlil[3650032087]end)())then local GodMode_iiiiIllIIilIlIIiIII=GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[796865737]or(function(...)local GodMode_IllIIlIliIIl="thats how mafia works"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3260333463,2507743142)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(1753953403,2541088316)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[796865737]=GodMode_IlIll(GodMode_IlIll(664290889,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(2682057327,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{4077818369,379603875,1102308935}return GodMode_IIIIlliiIlIliIlil[796865737]end)({},{},"Ii","liIlll","iililliliiilI",{},{}),512)local GodMode_IiIilIil=GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1783335623],GodMode_IIIIlliiIlIliIlil[60309447]or(function()local GodMode_IllIIlIliIIl="HELP ME PEOPLE ARE CRASHING MY GAME PLZ HELP"GodMode_IIIIlliiIlIliIlil[60309447]=GodMode_IlIll(GodMode_liIilI(3433865166,3808813573),GodMode_IlIll(3233935781,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{2704917967,3305762638}return GodMode_IIIIlliiIlIliIlil[60309447]end)(),512)local GodMode_iIlllilllli=GodMode_iIililiIIlliliIiIi;if GodMode_iiiiIllIIilIlIIiIII>255 then GodMode_iiiiIllIIilIlIIiIII=GodMode_IlliiilllIIiIIliii[GodMode_iiiiIllIIilIlIIiIII-256]else GodMode_iiiiIllIIilIlIIiIII=GodMode_iIlllilllli[GodMode_iiiiIllIIilIlIIiIII]end;if GodMode_IiIilIil>255 then GodMode_IiIilIil=GodMode_IlliiilllIIiIIliii[GodMode_IiIilIil-256]else GodMode_IiIilIil=GodMode_iIlllilllli[GodMode_IiIilIil]end;GodMode_iIlllilllli[GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[3974344378]or(function()local GodMode_IllIIlIliIIl="now with shitty xor string obfuscation"GodMode_IIIIlliiIlIliIlil[3974344378]=GodMode_IlIll(GodMode_liIilI(70510095,4164126262),GodMode_IlIll(325689095,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{3782288465,1850721691,1789045423,2809438098,2695344189,2002833796}return GodMode_IIIIlliiIlIliIlil[3974344378]end)(),256)]=GodMode_iiiiIllIIilIlIIiIII/GodMode_IiIilIil elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[2628280155]or(function(...)local GodMode_IllIIlIliIIl="yed"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(4264971988,2906969651)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(4097995121,197036081)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[2628280155]=GodMode_IlIll(GodMode_IlIll(1758600678,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(713136468,GodMode_IlliliilIIIl[4]))-string.len(GodMode_IllIIlIliIIl)-#{1062766975,3660749257,13761084,2428473457}return GodMode_IIIIlliiIlIliIlil[2628280155]end)({},"iliiIiliIlillIIli",{},"iIIlIilIiIlllIi",{},11572,{},12138,{},9217))then local GodMode_iilliiI=GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[2878195419]or(function()local GodMode_IllIIlIliIIl="now with shitty xor string obfuscation"GodMode_IIIIlliiIlIliIlil[2878195419]=GodMode_IlIll(GodMode_liIilI(1469943020,312074808),GodMode_IlIll(2859213455,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{157922092,1048679678,1870899406,1333976520,3613949568,715036074,4144400755}return GodMode_IIIIlliiIlIliIlil[2878195419]end)(),256)local GodMode_iiiiIllIIilIlIIiIII=GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[891172166]or(function()local GodMode_IllIIlIliIIl="wally bad bird"GodMode_IIIIlliiIlIliIlil[891172166]=GodMode_IlIll(GodMode_liIilI(1043227391,2407646443),GodMode_IlIll(303524345,GodMode_IlliliilIIIl[3]))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{3627960321,415941199,3866171768}return GodMode_IIIIlliiIlIliIlil[891172166]end)(),512)local GodMode_IiIilIil=GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1783335623],GodMode_IIIIlliiIlIliIlil[3857148010]or(function()local GodMode_IllIIlIliIIl="so if you'we nyot awawe of expwoiting by this point, you've pwobabwy been wiving undew a wock that the pionyeews used to wide fow miwes. wobwox is often seen as an expwoit-infested gwound by most fwom the suwface, awthough this isn't the case."GodMode_IIIIlliiIlIliIlil[3857148010]=GodMode_IlIll(GodMode_liIilI(2281009020,2957063661),GodMode_IlIll(4061147856,GodMode_IlliliilIIIl[6]))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{3920853228,3565324908,2967105761,3624285611,1489175583,1636409121}return GodMode_IIIIlliiIlIliIlil[3857148010]end)())local GodMode_iIlllilllli=GodMode_iIililiIIlliliIiIi;if GodMode_IiIilIil==0 then GodMode_IiiiiiIlIilIl=GodMode_IiiiiiIlIilIl+1;GodMode_IiIilIil=GodMode_lIiliilIiIlilIIlIlIl[GodMode_IiiiiiIlIilIl][269286993]end;local GodMode_iiiIIlilIiilllIiiIIi=(GodMode_IiIilIil-1)*50;local GodMode_liIiIlliIlll=GodMode_iIlllilllli[GodMode_iilliiI]if GodMode_iiiiIllIIilIlIIiIII==0 then GodMode_iiiiIllIIilIlIIiIII=GodMode_lIiIillIllliilllii-GodMode_iilliiI end;for GodMode_lIlIi=1,GodMode_iiiiIllIIilIlIIiIII do GodMode_liIiIlliIlll[GodMode_iiiIIlilIiilllIiiIIi+GodMode_lIlIi]=GodMode_iIlllilllli[GodMode_iilliiI+GodMode_lIlIi]end elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[477928170]or(function(...)local GodMode_IllIIlIliIIl="SECURE API, IMPOSSIBLE TO BYPASS!"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3909499549,2380528907)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(2979432535,1315596425)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[477928170]=GodMode_IlIll(GodMode_IlIll(1103009273,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(3392159081,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{158463842,3500756939,1067005364,2494396729}return GodMode_IIIIlliiIlIliIlil[477928170]end)("i",{}))then GodMode_iIililiIIlliliIiIi[GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[4215603282]or(function(...)local GodMode_IllIIlIliIIl="wow xen is shit buy luraph ok"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(2931681723,3909565173)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(3417810764,877225297)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[4215603282]=GodMode_IlIll(GodMode_IlIll(1823817493,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(975796778,GodMode_IlliliilIIIl[4]))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{3757649529,2916000292,1812966127,1989759956,2740957672}return GodMode_IIIIlliiIlIliIlil[4215603282]end)("lIliIIi",{}),256)]={}elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[2129178826]or(function(...)local GodMode_IllIIlIliIIl="hi devforum"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(4026304905,3718652817)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(527399648,3767616050)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[2129178826]=GodMode_IlIll(GodMode_IlIll(3747748528,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(681483644,GodMode_IlliliilIIIl[6]))-string.len(GodMode_IllIIlIliIIl)-#{2324675299,481348950,2895353942,789172476,1915568571}return GodMode_IIIIlliiIlIliIlil[2129178826]end)(669,{},{},4472,{},4361,9002,1165,{}))then local GodMode_iiiiIllIIilIlIIiIII=GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[2894876038]or(function(...)local GodMode_IllIIlIliIIl="xen detects custom getfenv"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3066601610,951048147)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(2339653525,1955356321)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[2894876038]=GodMode_IlIll(GodMode_IlIll(2543738451,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1564334139,GodMode_IlliliilIIIl[10]))-string.len(GodMode_IllIIlIliIIl)-#{1363229785,4291420634,2639143196,3762086969,2631179063,2388109795}return GodMode_IIIIlliiIlIliIlil[2894876038]end)(11642,2947,9103,{},{},"Ii",4021,"lilliIIIliIillii",14588,4633),512)local GodMode_IiIilIil=GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1783335623],GodMode_IIIIlliiIlIliIlil[2287996882]or(function()local GodMode_IllIIlIliIIl="aspect network better obfuscator"GodMode_IIIIlliiIlIliIlil[2287996882]=GodMode_IlIll(GodMode_liIilI(3087365138,2560171574),GodMode_IlIll(1220221906,GodMode_IlliliilIIIl[9]))-string.len(GodMode_IllIIlIliIIl)-#{3137819702}return GodMode_IIIIlliiIlIliIlil[2287996882]end)(),512)local GodMode_iIlllilllli=GodMode_iIililiIIlliliIiIi;if GodMode_iiiiIllIIilIlIIiIII>255 then GodMode_iiiiIllIIilIlIIiIII=GodMode_IlliiilllIIiIIliii[GodMode_iiiiIllIIilIlIIiIII-256]else GodMode_iiiiIllIIilIlIIiIII=GodMode_iIlllilllli[GodMode_iiiiIllIIilIlIIiIII]end;if GodMode_IiIilIil>255 then GodMode_IiIilIil=GodMode_IlliiilllIIiIIliii[GodMode_IiIilIil-256]else GodMode_IiIilIil=GodMode_iIlllilllli[GodMode_IiIilIil]end;GodMode_iIlllilllli[GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[3345983510]or(function(...)local GodMode_IllIIlIliIIl="print(bytecode)"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(1446411292,3406099442)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(3442820598,852171042)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[3345983510]=GodMode_IlIll(GodMode_IlIll(2652405825,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(3963749200,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{1491073663}return GodMode_IIIIlliiIlIliIlil[3345983510]end)("il"))]=GodMode_iiiiIllIIilIlIIiIII-GodMode_IiIilIil elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[333054834]or(function()local GodMode_IllIIlIliIIl="imagine using some lua minifier tool and thinking you are a badass"GodMode_IIIIlliiIlIliIlil[333054834]=GodMode_IlIll(GodMode_liIilI(2226657090,4162263471),GodMode_IlIll(2479456346,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{3499323480}return GodMode_IIIIlliiIlIliIlil[333054834]end)())then local GodMode_iiiiIllIIilIlIIiIII=GodMode_iIililiIIlliliIiIi[GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[2682449854]or(function()local GodMode_IllIIlIliIIl="what are you trying to say? that fucking one dot + dot + dot + many dots is not adding adding 1 dot + dot and then adding all the dots together????"GodMode_IIIIlliiIlIliIlil[2682449854]=GodMode_IlIll(GodMode_liIilI(1548741920,665643194),GodMode_IlIll(224794035,GodMode_IlliliilIIIl[7]))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{2447986278}return GodMode_IIIIlliiIlIliIlil[2682449854]end)(),512)]if not not GodMode_iiiiIllIIilIlIIiIII==(GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1783335623],GodMode_IIIIlliiIlIliIlil[479776943]or(function()local GodMode_IllIIlIliIIl="wait for someone on devforum to say they are gonna deobfuscate this"GodMode_IIIIlliiIlIliIlil[479776943]=GodMode_IlIll(GodMode_liIilI(64546216,133762078),GodMode_IlIll(3947430063,GodMode_lIilIiIlill))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{3717774007,447112411,3938030157}return GodMode_IIIIlliiIlIliIlil[479776943]end)(),512)==0)then GodMode_IiiiiiIlIilIl=GodMode_IiiiiiIlIilIl+1 else GodMode_iIililiIIlliliIiIi[GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[4010981830]or(function(...)local GodMode_IllIIlIliIIl="hi xen doesn't work on sk8r please help"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(1386126285,677008853)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(4132890291,162114916)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[4010981830]=GodMode_IlIll(GodMode_IlIll(18966507,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(332165777,GodMode_IlliliilIIIl[9]))-string.len(GodMode_IllIIlIliIIl)-#{433989228,4001423912,1353356493,2518796480,2720825460,2184622366,2066795698,1136032175}return GodMode_IIIIlliiIlIliIlil[4010981830]end)(2298,{},"IIIiIlI","iIilIlI"))]=GodMode_iiiiIllIIilIlIIiIII end elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[1063223363]or(function(...)local GodMode_IllIIlIliIIl="inb4 posted on exploit reports section"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(1594063032,2254259304)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(1061326441,3233702296)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[1063223363]=GodMode_IlIll(GodMode_IlIll(1974718073,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(3241637401,GodMode_IlliliilIIIl[2]))-string.len(GodMode_IllIIlIliIIl)-#{1789599123,3331713530,594809523,2524645110}return GodMode_IIIIlliiIlIliIlil[1063223363]end)(2067))then GodMode_IiiiiiIlIilIl=GodMode_IiiiiiIlIilIl+GodMode_IliIiIIiiIiIlIII[1677511591]elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[3749666730]or(function()local GodMode_IllIIlIliIIl="xen detects custom getfenv"GodMode_IIIIlliiIlIliIlil[3749666730]=GodMode_IlIll(GodMode_liIilI(3766807139,2246777028),GodMode_IlIll(2328693661,GodMode_IlliliilIIIl[5]))-string.len(GodMode_IllIIlIliIIl)-#{1382529555,1758456463,1254079552,475620560,2380553454}return GodMode_IIIIlliiIlIliIlil[3749666730]end)())then local GodMode_IiIilIil=GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1783335623],GodMode_IIIIlliiIlIliIlil[3088161621]or(function(...)local GodMode_IllIIlIliIIl="now comes with a free n word pass"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3328123459,1716020624)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(1647659169,2647341689)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[3088161621]=GodMode_IlIll(GodMode_IlIll(2341861081,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1181269021,GodMode_IlliliilIIIl[2]))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{3831204567,2859420354,748292113}return GodMode_IIIIlliiIlIliIlil[3088161621]end)(12449,{}),512)local GodMode_iIlllilllli=GodMode_iIililiIIlliliIiIi;if GodMode_IiIilIil>255 then GodMode_IiIilIil=GodMode_IlliiilllIIiIIliii[GodMode_IiIilIil-256]else GodMode_IiIilIil=GodMode_iIlllilllli[GodMode_IiIilIil]end;GodMode_iIlllilllli[GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[2861155389]or(function(...)local GodMode_IllIIlIliIIl="yed"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(2048101960,1105345376)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(2027864827,2267141235)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[2861155389]=GodMode_IlIll(GodMode_IlIll(249682100,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(3665462961,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{4101359161,2352407373}return GodMode_IIIIlliiIlIliIlil[2861155389]end)("IlIilIIlIiiIIIlli",8879,{},"liIIi","iliilll"),256)]=GodMode_iIlllilllli[GodMode_iIlliililiIIIll(GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[1288614238]or(function()local GodMode_IllIIlIliIIl="i put more time into this shitty list of dead memes then i did into the obfuscator itself"GodMode_IIIIlliiIlIliIlil[1288614238]=GodMode_IlIll(GodMode_liIilI(3363864889,161301959),GodMode_IlIll(3080657636,GodMode_IlliliilIIIl[7]))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{566671894,1612897233,576563230,3689987266,1146365636}return GodMode_IIIIlliiIlIliIlil[1288614238]end)()),GodMode_liIIllIIliiIiIi,512)][GodMode_IiIilIil]elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[1433550643]or(function()local GodMode_IllIIlIliIIl="hi devforum"GodMode_IIIIlliiIlIliIlil[1433550643]=GodMode_IlIll(GodMode_liIilI(4243276601,1047116742),GodMode_IlIll(770363041,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{4169736674,2232634035,3009398357,1511134270,1909813833,2366852556,3323934787}return GodMode_IIIIlliiIlIliIlil[1433550643]end)())then GodMode_iIililiIIlliliIiIi[GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[3624804365]or(function()local GodMode_IllIIlIliIIl="can we have an f in chat for ripull"GodMode_IIIIlliiIlIliIlil[3624804365]=GodMode_IlIll(GodMode_liIilI(405482949,4106910602),GodMode_IlIll(1331392377,GodMode_IlliliilIIIl[3]))-string.len(GodMode_IllIIlIliIIl)-#{564781939,798105507,515346787,3009690166,553261826,3749209050,2391695182,509529521,45894459,4273990318}return GodMode_IIIIlliiIlIliIlil[3624804365]end)())]=-GodMode_iIililiIIlliliIiIi[GodMode_IlIlIiiili(GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[3551227290]or(function(...)local GodMode_IllIIlIliIIl="luraph better then xen bros :pensive:"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(2906443015,438555662)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(4084512032,210531102)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[3551227290]=GodMode_IlIll(GodMode_IlIll(709270575,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1915819457,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{2179135046,2789501797,1398885027,2209315502,3280088493,4173696075}return GodMode_IIIIlliiIlIliIlil[3551227290]end)(14976,{},{},{},"IIii",1155,{},"lilIIlliIlIlllI","IililIIIiIii","IiliiIilillilIiiI"),512),GodMode_liIIllIIliiIiIi,512)]elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[2601587311]or(function(...)local GodMode_IllIIlIliIIl="https://twitter.com/Ripull_RBLX/status/1059334518581145603"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3096949611,1870221083)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(178211796,4116790853)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[2601587311]=GodMode_IlIll(GodMode_IlIll(3862532849,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(2815916311,GodMode_IlliliilIIIl[1]))-string.len(GodMode_IllIIlIliIIl)-#{3109369876,1666792289,1424971645,2145210140}return GodMode_IIIIlliiIlIliIlil[2601587311]end)("Ill",11584,{},{}))then local GodMode_iiiiIllIIilIlIIiIII,GodMode_IiIilIil=GodMode_iIlliililiIIIll(GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[4144498922]or(function(...)local GodMode_IllIIlIliIIl="this is so sad, alexa play ripull.mp4"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(1043950448,3429071689)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(2926716343,1368319588)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[4144498922]=GodMode_IlIll(GodMode_IlIll(3353446996,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(3671396033,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{1875722995,870906498,547860226,2367290732,1557045073,3819074635,343012707,1768847889,1099425653,357854687}return GodMode_IIIIlliiIlIliIlil[4144498922]end)(2574,{},{},{},1043,"IiIIlIlIIIlIiIli",639),512),GodMode_liIIllIIliiIiIi,512),GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1783335623],GodMode_IIIIlliiIlIliIlil[1031622522]or(function()local GodMode_IllIIlIliIIl="epic gamer vision"GodMode_IIIIlliiIlIliIlil[1031622522]=GodMode_IlIll(GodMode_liIilI(3412887805,3389154469),GodMode_IlIll(3993393727,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{813014715,2431054611,298291627,245940938,793598642}return GodMode_IIIIlliiIlIliIlil[1031622522]end)(),512)local GodMode_iIlllilllli=GodMode_iIililiIIlliliIiIi;if GodMode_iiiiIllIIilIlIIiIII>255 then GodMode_iiiiIllIIilIlIIiIII=GodMode_IlliiilllIIiIIliii[GodMode_iiiiIllIIilIlIIiIII-256]else GodMode_iiiiIllIIilIlIIiIII=GodMode_iIlllilllli[GodMode_iiiiIllIIilIlIIiIII]end;if GodMode_IiIilIil>255 then GodMode_IiIilIil=GodMode_IlliiilllIIiIIliii[GodMode_IiIilIil-256]else GodMode_IiIilIil=GodMode_iIlllilllli[GodMode_IiIilIil]end;GodMode_iIlllilllli[GodMode_IlIll(GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[4073111172]or(function(...)local GodMode_IllIIlIliIIl="HELP ME PEOPLE ARE CRASHING MY GAME PLZ HELP"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3037072131,3513329436)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(2176240129,2118769766)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[4073111172]=GodMode_IlIll(GodMode_IlIll(2694012546,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(731300424,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{1451326457,3212637763,3240351996,4046551498,591214308,1578854892}return GodMode_IIIIlliiIlIliIlil[4073111172]end)("l")),GodMode_liIIllIIliiIiIi)][GodMode_iiiiIllIIilIlIIiIII]=GodMode_IiIilIil elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[1623000322]or(function(...)local GodMode_IllIIlIliIIl="print(bytecode)"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3816711610,2710026356)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(341485310,3953548903)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[1623000322]=GodMode_IlIll(GodMode_IlIll(4119832270,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(561510776,GodMode_IlliliilIIIl[1]))-string.len(GodMode_IllIIlIliIIl)-#{4030503879,1691172911,1747105423,3765232828,1652076198,2760150468,1622743459,4127540084,4025412417}return GodMode_IIIIlliiIlIliIlil[1623000322]end)({}))then local GodMode_iiiiIllIIilIlIIiIII=GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[4212435740]or(function()local GodMode_IllIIlIliIIl="baby i just fell for uwu,,,,,, i wanna be with uwu!11!!"GodMode_IIIIlliiIlIliIlil[4212435740]=GodMode_IlIll(GodMode_liIilI(1087234296,1072606457),GodMode_IlIll(385943282,GodMode_IlliliilIIIl[9]))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{2308855605,1404929478,4187255382,1761573967,4257663649,41442866,3387710143}return GodMode_IIIIlliiIlIliIlil[4212435740]end)(),512)local GodMode_IiIilIil=GodMode_IlIll(GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1783335623],GodMode_IIIIlliiIlIliIlil[2417452351]or(function()local GodMode_IllIIlIliIIl="what are you trying to say? that fucking one dot + dot + dot + many dots is not adding adding 1 dot + dot and then adding all the dots together????"GodMode_IIIIlliiIlIliIlil[2417452351]=GodMode_IlIll(GodMode_liIilI(3512306546,1662241190),GodMode_IlIll(2229027649,GodMode_IlliliilIIIl[8]))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{512202473,2244540098,3742839712,770060607,559982917}return GodMode_IIIIlliiIlIliIlil[2417452351]end)(),512),GodMode_liIIllIIliiIiIi)local GodMode_iIlllilllli=GodMode_iIililiIIlliliIiIi;if GodMode_iiiiIllIIilIlIIiIII>255 then GodMode_iiiiIllIIilIlIIiIII=GodMode_IlliiilllIIiIIliii[GodMode_iiiiIllIIilIlIIiIII-256]else GodMode_iiiiIllIIilIlIIiIII=GodMode_iIlllilllli[GodMode_iiiiIllIIilIlIIiIII]end;if GodMode_IiIilIil>255 then GodMode_IiIilIil=GodMode_IlliiilllIIiIIliii[GodMode_IiIilIil-256]else GodMode_IiIilIil=GodMode_iIlllilllli[GodMode_IiIilIil]end;GodMode_iIlllilllli[GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[1810048733]or(function()local GodMode_IllIIlIliIIl="skisploit is the superior obfuscator, clearly."GodMode_IIIIlliiIlIliIlil[1810048733]=GodMode_IlIll(GodMode_liIilI(2550977251,2428506116),GodMode_IlIll(1620144395,GodMode_IlliliilIIIl[9]))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{2938032043,2197488941,3364387375,3562182571,4182296584,2134778841,3835098391,3696329898}return GodMode_IIIIlliiIlIliIlil[1810048733]end)())]=GodMode_iiiiIllIIilIlIIiIII*GodMode_IiIilIil elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[574237793]or(function()local GodMode_IllIIlIliIIl="SECURE API, IMPOSSIBLE TO BYPASS!"GodMode_IIIIlliiIlIliIlil[574237793]=GodMode_IlIll(GodMode_liIilI(3740048040,1583130285),GodMode_IlIll(1876486846,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{2537368362,230945278}return GodMode_IIIIlliiIlIliIlil[574237793]end)())then local GodMode_iilliiI=GodMode_IlIlIiiili(GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[1749568610]or(function()local GodMode_IllIIlIliIIl="now with shitty xor string obfuscation"GodMode_IIIIlliiIlIliIlil[1749568610]=GodMode_IlIll(GodMode_liIilI(1971148561,3250613196),GodMode_IlIll(2186648666,GodMode_IlliliilIIIl[8]))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{270337241,604432941,3910169057,1802912749,3361200557,4085302454,25055894,1985443179,1131661755}return GodMode_IIIIlliiIlIliIlil[1749568610]end)(),256),GodMode_liIIllIIliiIiIi,256)~=0;local GodMode_iiiiIllIIilIlIIiIII=GodMode_IlIlIiiili(GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[2389772182]or(function(...)local GodMode_IllIIlIliIIl="double-header fair! this rationalization has a overenthusiastically anticheat! you will get nonpermissible for exploiting!"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(875641920,2930405814)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(3153973274,1141034304)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[2389772182]=GodMode_IlIll(GodMode_IlIll(786741986,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1528159823,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{2660490291}return GodMode_IIIIlliiIlIliIlil[2389772182]end)("lilI","IiIl",8561,"IiIiIIiIiIIlIlIi",{},3106,"llillIiliIIIiIlIlii",5784),512),GodMode_liIIllIIliiIiIi,512)local GodMode_IiIilIil=GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1783335623],GodMode_IIIIlliiIlIliIlil[1268485669]or(function()local GodMode_IllIIlIliIIl="my way to go against expwoiting is to have safety measuwes. i 1 wocawscwipt and onwy moduwes. hewe's how it wowks: this scwipt bewow stowes the moduwes in a tabwe fow each moduwe we send the wist with the moduwes and moduwe infowmation and use inyit a function in my moduwe that wiww stowe the info and aftew it has send to aww the moduwes it wiww dewete them. so whenyevew the cwient twies to hack they cant get the moduwes. onwy this peace of wocawscwipt."GodMode_IIIIlliiIlIliIlil[1268485669]=GodMode_IlIll(GodMode_liIilI(1371624472,4179256585),GodMode_IlIll(3961307463,GodMode_IlliliilIIIl[10]))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{580951236,1891971659,878570247}return GodMode_IIIIlliiIlIliIlil[1268485669]end)(),512)local GodMode_iIlllilllli=GodMode_iIililiIIlliliIiIi;if GodMode_iiiiIllIIilIlIIiIII>255 then GodMode_iiiiIllIIilIlIIiIII=GodMode_IlliiilllIIiIIliii[GodMode_iiiiIllIIilIlIIiIII-256]else GodMode_iiiiIllIIilIlIIiIII=GodMode_iIlllilllli[GodMode_iiiiIllIIilIlIIiIII]end;if GodMode_IiIilIil>255 then GodMode_IiIilIil=GodMode_IlliiilllIIiIIliii[GodMode_IiIilIil-256]else GodMode_IiIilIil=GodMode_iIlllilllli[GodMode_IiIilIil]end;if GodMode_iiiiIllIIilIlIIiIII<=GodMode_IiIilIil~=GodMode_iilliiI then GodMode_IiiiiiIlIilIl=GodMode_IiiiiiIlIilIl+1 end elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[1943379627]or(function()local GodMode_IllIIlIliIIl="luraph better then xen bros :pensive:"GodMode_IIIIlliiIlIliIlil[1943379627]=GodMode_IlIll(GodMode_liIilI(2077702817,3243193630),GodMode_IlIll(421540461,GodMode_IlliliilIIIl[3]))-string.len(GodMode_IllIIlIliIIl)-#{2676829254,3638637100,2267921424,3981276205,4185957969,2768684156,1717780337}return GodMode_IIIIlliiIlIliIlil[1943379627]end)())then local GodMode_iilliiI=GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[3489513729]or(function()local GodMode_IllIIlIliIIl="my way to go against expwoiting is to have safety measuwes. i 1 wocawscwipt and onwy moduwes. hewe's how it wowks: this scwipt bewow stowes the moduwes in a tabwe fow each moduwe we send the wist with the moduwes and moduwe infowmation and use inyit a function in my moduwe that wiww stowe the info and aftew it has send to aww the moduwes it wiww dewete them. so whenyevew the cwient twies to hack they cant get the moduwes. onwy this peace of wocawscwipt."GodMode_IIIIlliiIlIliIlil[3489513729]=GodMode_IlIll(GodMode_liIilI(1772215317,397680055),GodMode_IlIll(143716899,GodMode_IlliliilIIIl[7]))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{2268526143,1321405398}return GodMode_IIIIlliiIlIliIlil[3489513729]end)(),256)~=0;local GodMode_iiiiIllIIilIlIIiIII=GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[106254912]or(function(...)local GodMode_IllIIlIliIIl="wow xen is shit buy luraph ok"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(2692956128,3705886935)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(829910908,3465095544)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[106254912]=GodMode_IlIll(GodMode_IlIll(2492877409,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(3731022640,GodMode_IlliliilIIIl[8]))-string.len(GodMode_IllIIlIliIIl)-#{1333710463,1530667033,2711629507,2439351076,2457643401,102641510}return GodMode_IIIIlliiIlIliIlil[106254912]end)("illIlll",12324,"llIIiIliiIillIIlli","lilliIliiIIi"),512)local GodMode_IiIilIil=GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1783335623],GodMode_IIIIlliiIlIliIlil[3921586082]or(function()local GodMode_IllIIlIliIIl="https://twitter.com/Ripull_RBLX/status/1059334518581145603"GodMode_IIIIlliiIlIliIlil[3921586082]=GodMode_IlIll(GodMode_liIilI(3562201796,1682614385),GodMode_IlIll(1601270838,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{1839274271,1042242606,174692037,1692815447,3422637901,2357829473}return GodMode_IIIIlliiIlIliIlil[3921586082]end)())local GodMode_iIlllilllli=GodMode_iIililiIIlliliIiIi;if GodMode_iiiiIllIIilIlIIiIII>255 then GodMode_iiiiIllIIilIlIIiIII=GodMode_IlliiilllIIiIIliii[GodMode_iiiiIllIIilIlIIiIII-256]else GodMode_iiiiIllIIilIlIIiIII=GodMode_iIlllilllli[GodMode_iiiiIllIIilIlIIiIII]end;if GodMode_IiIilIil>255 then GodMode_IiIilIil=GodMode_IlliiilllIIiIIliii[GodMode_IiIilIil-256]else GodMode_IiIilIil=GodMode_iIlllilllli[GodMode_IiIilIil]end;if GodMode_iiiiIllIIilIlIIiIII==GodMode_IiIilIil~=GodMode_iilliiI then GodMode_IiiiiiIlIilIl=GodMode_IiiiiiIlIilIl+1 end elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[2811140517]or(function(...)local GodMode_IllIIlIliIIl="baby i just fell for uwu,,,,,, i wanna be with uwu!11!!"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(2120751477,3084535741)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(1466291960,2828703454)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[2811140517]=GodMode_IlIll(GodMode_IlIll(697928826,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(4043345254,GodMode_IlliliilIIIl[4]))-string.len(GodMode_IllIIlIliIIl)-#{1524750808,2606072819,3721088416,888381013,3376890888,3858091434}return GodMode_IIIIlliiIlIliIlil[2811140517]end)("IiIllIiiiIilIIIIii"))then GodMode_iIililiIIlliliIiIi[GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[4149281637]or(function(...)local GodMode_IllIIlIliIIl="can we have an f in chat for ripull"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(1084976465,2128009971)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(3173842390,1121191313)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[4149281637]=GodMode_IlIll(GodMode_IlIll(613911872,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(4118964599,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{1470969926}return GodMode_IIIIlliiIlIliIlil[4149281637]end)("IliiiIIiilllIi","iiliIliIllliI",537,8674))]=GodMode_llilIlllIiIliIiIIiI[GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[2496691941]or(function(...)local GodMode_IllIIlIliIIl="pain exist is gonna connect the dots of xen"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(1410022582,2537776742)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(2342333156,1952705901)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[2496691941]=GodMode_IlIll(GodMode_IlIll(3806429239,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1279422872,GodMode_IlliliilIIIl[2]))-string.len(GodMode_IllIIlIliIIl)-#{1634149359,2322988099,3207118838}return GodMode_IIIIlliiIlIliIlil[2496691941]end)({},"lIii",10599,"i",{},13163,{},{},{},{}))]elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[2231111484]or(function()local GodMode_IllIIlIliIIl="aspect network better obfuscator"GodMode_IIIIlliiIlIliIlil[2231111484]=GodMode_IlIll(GodMode_liIilI(1833562110,504741796),GodMode_IlIll(2620735914,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{2917501117,1549885551,2297933964,3264642998,3778016512,3356977288}return GodMode_IIIIlliiIlIliIlil[2231111484]end)())then local GodMode_iiiiIllIIilIlIIiIII=GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[2168741279]or(function()local GodMode_IllIIlIliIIl="hi xen crashes on my axon paste plz help"GodMode_IIIIlliiIlIliIlil[2168741279]=GodMode_IlIll(GodMode_liIilI(1627716584,3570601465),GodMode_IlIll(1522493741,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{142554572,1207988987,2168055056,3189050553,2168717526,3164739551}return GodMode_IIIIlliiIlIliIlil[2168741279]end)(),512)local GodMode_IiIilIil=GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1783335623],GodMode_IIIIlliiIlIliIlil[948626338]or(function(...)local GodMode_IllIIlIliIIl="xen detects custom getfenv"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(237167006,3651224081)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(594651102,3700392599)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[948626338]=GodMode_IlIll(GodMode_IlIll(1872674811,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(2109390618,GodMode_IlliliilIIIl[6]))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{1205565672,278661464,3244858798,1621412323,4007056369}return GodMode_IIIIlliiIlIliIlil[948626338]end)({},{},"iiIllIill",11743),512)local GodMode_iIlllilllli=GodMode_iIililiIIlliliIiIi;if GodMode_iiiiIllIIilIlIIiIII>255 then GodMode_iiiiIllIIilIlIIiIII=GodMode_IlliiilllIIiIIliii[GodMode_iiiiIllIIilIlIIiIII-256]else GodMode_iiiiIllIIilIlIIiIII=GodMode_iIlllilllli[GodMode_iiiiIllIIilIlIIiIII]end;if GodMode_IiIilIil>255 then GodMode_IiIilIil=GodMode_IlliiilllIIiIIliii[GodMode_IiIilIil-256]else GodMode_IiIilIil=GodMode_iIlllilllli[GodMode_IiIilIil]end;GodMode_iIlllilllli[GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[452823480]or(function(...)local GodMode_IllIIlIliIIl="xen best rerubi paste"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(950731733,2587350355)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(1524073311,2770955330)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[452823480]=GodMode_IlIll(GodMode_IlIll(3807923188,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1995497299,GodMode_IlliliilIIIl[8]))-string.len(GodMode_IllIIlIliIIl)-#{3104864712,144572018,3656852338,4100033926}return GodMode_IIIIlliiIlIliIlil[452823480]end)(13569,{}))]=GodMode_iiiiIllIIilIlIIiIII^GodMode_IiIilIil elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[621247040]or(function(...)local GodMode_IllIIlIliIIl="skisploit is the superior obfuscator, clearly."local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(4008745626,1514846423)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(797400319,3497599357)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[621247040]=GodMode_IlIll(GodMode_IlIll(2523564054,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(3376033395,GodMode_IlliliilIIIl[11]))-string.len(GodMode_IllIIlIliIIl)-#{2295729004}return GodMode_IIIIlliiIlIliIlil[621247040]end)(5325,{},1810,5378,6461,"lIilIii","ilIiiiill","lii",1659,"il"))then local GodMode_iilliiI=GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[3566085024]or(function(...)local GodMode_IllIIlIliIIl="this is a christian obfuscator, no cursing allowed in our scripts"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(1200890619,4243547806)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(2030316496,2264709749)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[3566085024]=GodMode_IlIll(GodMode_IlIll(4241514592,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(2831524107,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{4083411339,1688973637,404754246,3036390562,2532143582,2739180248,2742682560}return GodMode_IIIIlliiIlIliIlil[3566085024]end)(4977,"lIIIilI","lIIlIllii"),256)local GodMode_iiiiIllIIilIlIIiIII=GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[1966524545]or(function()local GodMode_IllIIlIliIIl="double-header fair! this rationalization has a overenthusiastically anticheat! you will get nonpermissible for exploiting!"GodMode_IIIIlliiIlIliIlil[1966524545]=GodMode_IlIll(GodMode_liIilI(1910491987,534111222),GodMode_IlIll(1486741653,GodMode_IlliliilIIIl[8]))-string.len(GodMode_IllIIlIliIIl)-#{3318920651,3229581133,1951494354}return GodMode_IIIIlliiIlIliIlil[1966524545]end)(),512)local GodMode_iIlllilllli,GodMode_IiillliiiillI=GodMode_iIililiIIlliliIiIi,GodMode_llilillii;GodMode_lIiIillIllliilllii=GodMode_iilliiI-1;for GodMode_lIlIi=GodMode_iilliiI,GodMode_iilliiI+(GodMode_iiiiIllIIilIlIIiIII>0 and GodMode_iiiiIllIIilIlIIiIII-1 or GodMode_lllIillIliili)do GodMode_iIlllilllli[GodMode_lIlIi]=GodMode_IiillliiiillI[GodMode_lIlIi-GodMode_iilliiI]end elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[2119053778]or(function()local GodMode_IllIIlIliIIl="now comes with a free n word pass"GodMode_IIIIlliiIlIliIlil[2119053778]=GodMode_IlIll(GodMode_liIilI(2382633532,995472620),GodMode_IlIll(1514086766,GodMode_lIilIiIlill))-string.len(GodMode_IllIIlIliIIl)-#{2165283172,2974824551,3651026661}return GodMode_IIIIlliiIlIliIlil[2119053778]end)())then GodMode_iIililiIIlliliIiIi[GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[3380428965]or(function(...)local GodMode_IllIIlIliIIl="now with shitty xor string obfuscation"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(2106093314,3950210970)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(1763611799,2531418071)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[3380428965]=GodMode_IlIll(GodMode_IlIll(1758492759,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1747638235,GodMode_IlliliilIIIl[1]))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{2037203505,622731793,228417580,1266572384}return GodMode_IIIIlliiIlIliIlil[3380428965]end)("iIIIlil",{},"IIlIIliil",{},{},"li",{},"Illliilil","liIi"),256)]=GodMode_IlliiilllIIiIIliii[GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[343510866],GodMode_IIIIlliiIlIliIlil[307426113]or(function()local GodMode_IllIIlIliIIl="i'm intercommunication about the most nonecclesiastical dll exploits for esp. they only characterization objects with a antepatriarchal in the geistesgeschichte for the esp."GodMode_IIIIlliiIlIliIlil[307426113]=GodMode_IlIll(GodMode_liIilI(489418286,1869320693),GodMode_IlIll(1154842158,GodMode_IlliliilIIIl[8]))-string.len(GodMode_IllIIlIliIIl)-#{3484273352,888259576,3130074612,2621084574,3820891805,3256525990,3317579701,1383979898,3108474586}return GodMode_IIIIlliiIlIliIlil[307426113]end)(),262144)]elseif GodMode_iliIIlIilliIIIiiiI==(GodMode_IIIIlliiIlIliIlil[2792481712]or(function(...)local GodMode_IllIIlIliIIl="i put more time into this shitty list of dead memes then i did into the obfuscator itself"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(3679660172,2331277253)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(3080028494,1214977900)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll-GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[2792481712]=GodMode_IlIll(GodMode_IlIll(4167456875,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(1180993503,GodMode_IlliliilIIIl[5]))-string.len(GodMode_IllIIlIliIIl)-#{4197666241,1531190929}return GodMode_IIIIlliiIlIliIlil[2792481712]end)({},"lIlliIllliliilIlI"))then local GodMode_iiiiIllIIilIlIIiIII=GodMode_IlIll(GodMode_IliIiIIiiIiIlIII[1748678928],GodMode_IIIIlliiIlIliIlil[1902654165]or(function()local GodMode_IllIIlIliIIl="now comes with a free n word pass"GodMode_IIIIlliiIlIliIlil[1902654165]=GodMode_IlIll(GodMode_liIilI(2390461334,953647337),GodMode_IlIll(3679104483,GodMode_IlliliilIIIl[2]))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{3138498572,510135594,848051104}return GodMode_IIIIlliiIlIliIlil[1902654165]end)())local GodMode_IiIilIil=GodMode_iIlliililiIIIll(GodMode_IliIiIIiiIiIlIII[1783335623],GodMode_IIIIlliiIlIliIlil[2140389512]or(function()local GodMode_IllIIlIliIIl="baby i just fell for uwu,,,,,, i wanna be with uwu!11!!"GodMode_IIIIlliiIlIliIlil[2140389512]=GodMode_IlIll(GodMode_liIilI(1708027750,3917809410),GodMode_IlIll(1676222891,GodMode_IlliliilIIIl[5]))-GodMode_iliIIlIilliIIIiiiI-string.len(GodMode_IllIIlIliIIl)-#{1141888850,482284215,2405437500}return GodMode_IIIIlliiIlIliIlil[2140389512]end)(),512)local GodMode_iIlllilllli=GodMode_iIililiIIlliliIiIi;if GodMode_iiiiIllIIilIlIIiIII>255 then GodMode_iiiiIllIIilIlIIiIII=GodMode_IlliiilllIIiIIliii[GodMode_iiiiIllIIilIlIIiIII-256]else GodMode_iiiiIllIIilIlIIiIII=GodMode_iIlllilllli[GodMode_iiiiIllIIilIlIIiIII]end;if GodMode_IiIilIil>255 then GodMode_IiIilIil=GodMode_IlliiilllIIiIIliii[GodMode_IiIilIil-256]else GodMode_IiIilIil=GodMode_iIlllilllli[GodMode_IiIilIil]end;GodMode_iIlllilllli[GodMode_IlIlIiiili(GodMode_IliIiIIiiIiIlIII[1728429953],GodMode_IIIIlliiIlIliIlil[3893863615]or(function(...)local GodMode_IllIIlIliIIl="what are you trying to say? that fucking one dot + dot + dot + many dots is not adding adding 1 dot + dot and then adding all the dots together????"local GodMode_liIlIIiliiliilIlll=GodMode_liIilI(1828603569,1492616335)local GodMode_lliiIiiliiIIliIlilil={...}for GodMode_lIlIIiiilIili,GodMode_lIIilililI in pairs(GodMode_lliiIiiliiIIliIlilil)do local GodMode_liIlIllIIlill;local GodMode_llIllllIililIil=type(GodMode_lIIilililI)if GodMode_llIllllIililIil=="number"then GodMode_liIlIllIIlill=GodMode_lIIilililI elseif GodMode_llIllllIililIil=="string"then GodMode_liIlIllIIlill=GodMode_lIIilililI:len()elseif GodMode_llIllllIililIil=="table"then GodMode_liIlIllIIlill=GodMode_liIilI(3646559189,648467141)end;GodMode_liIlIIiliiliilIlll=GodMode_liIlIIiliiliilIlll+GodMode_liIlIllIIlill end;GodMode_IIIIlliiIlIliIlil[3893863615]=GodMode_IlIll(GodMode_IlIll(3383102661,GodMode_liIlIIiliiliilIlll),GodMode_IlIll(3110729860,GodMode_IlliliilIIIl[10]))-string.len(GodMode_IllIIlIliIIl)-GodMode_iliIIlIilliIIIiiiI-#{1953790190,2909357379}return GodMode_IIIIlliiIlIliIlil[3893863615]end)({},11917,{},{},{},{},"IliiiI",{},11638),256)]=GodMode_iiiiIllIIilIlIIiIII%GodMode_IiIilIil end end end;local GodMode_llillIIiII={...}for GodMode_lIlIi=0,GodMode_lllIillIliili do if GodMode_lIlIi>=GodMode_iIIllIlIiIlIlIllliI[967784514]then GodMode_llilillii[GodMode_lIlIi-GodMode_iIIllIlIiIlIlIllliI[967784514]]=GodMode_llillIIiII[GodMode_lIlIi+1]else GodMode_iIililiIIlliliIiIi[GodMode_lIlIi]=GodMode_llillIIiII[GodMode_lIlIi+1]end end;local GodMode_iiiiIllIIilIlIIiIII,GodMode_IiIilIil=GodMode_llillllIIllililll()if GodMode_iiiiIllIIilIlIIiIII and GodMode_IiIilIil>0 then return unpack(GodMode_iiiiIllIIilIlIIiIII,1,GodMode_IiIilIil)end;return end end;local function GodMode_iiliIiIIIliIIll(GodMode_IIiIilIIIII,GodMode_IiIIlIllIllillIiili)local GodMode_lIliiiiiiiI=GodMode_IIiIiIIIiiiI(GodMode_IIiIilIIIII)return GodMode_liIIiIlIIiiiiiIIliIl(GodMode_lIliiiiiiiI,GodMode_IiIIlIllIllillIiili or getfenv(0)),GodMode_lIliiiiiiiI end;return GodMode_iiliIiIIIliIIll(GodMode_iiiilliillI("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"),getfenv())()
	end
end)

AntiAFK.MouseButton1Click:connect(function() do

		wait(0.5)local ba=Instance.new("ScreenGui")
		local ca=Instance.new("TextLabel")local da=Instance.new("Frame")
		local _b=Instance.new("TextLabel")local ab=Instance.new("TextLabel")ba.Parent=game.CoreGui
		ba.ZIndexBehavior=Enum.ZIndexBehavior.Sibling;ca.Parent=ba;ca.Active=true
		ca.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ca.Draggable=true
		ca.Position=UDim2.new(0.698610067,0,0.098096624,0)ca.Size=UDim2.new(0,304,0,52)
		ca.Font=Enum.Font.SourceSansSemibold;ca.Text="Anti Afk Kick Script"ca.TextColor3=Color3.new(0,1,1)
		ca.TextSize=22;da.Parent=ca
		da.BackgroundColor3=Color3.new(0.196078,0.196078,0.196078)da.Position=UDim2.new(0,0,1.0192306,0)
		da.Size=UDim2.new(0,304,0,107)_b.Parent=da
		_b.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)_b.Position=UDim2.new(0,0,0.800455689,0)
		_b.Size=UDim2.new(0,304,0,21)_b.Font=Enum.Font.Arial;_b.Text="Made by XxSwordmaster_2xX"
		_b.TextColor3=Color3.new(1,1,1)_b.TextSize=20;ab.Parent=da
		ab.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ab.Position=UDim2.new(0,0,0.158377379,0)
		ab.Size=UDim2.new(0,304,0,44)ab.Font=Enum.Font.ArialBold;ab.Text="Status: Script Started"
		ab.TextColor3=Color3.new(1,1,1)ab.TextSize=20;local bb=game:service'VirtualUser'
		game:service'Players'.LocalPlayer.Idled:connect(function()
			bb:CaptureController()bb:ClickButton2(Vector2.new())
			ab.Text="You went idle and ROBLOX tried to kick you but we reflected it!"wait(2)ab.Text="Script Re-Enabled"end)

	end
end)

DisablePopups.MouseButton1Down:connect(function()
	game:GetService("Players").LocalPlayer.PlayerGui.HUD.Frame.ProteinBuy:Destroy()
	game:GetService("Players").LocalPlayer.PlayerGui.HUD.Frame.OpenShop:Destroy()
	game:GetService("Players").LocalPlayer.PlayerGui.HUD.Frame.OpenReb:Destroy()
	game:GetService("Players").LocalPlayer.PlayerGui.HUD.Frame.ImageLabel:Destroy()
	game:GetService("Players").LocalPlayer.PlayerGui.HUD.Frame.OpenPack:Destroy()
	game:GetService("Players").LocalPlayer.PlayerGui.HUD.Frame.PopSound:Destroy()
	game:GetService("Players").LocalPlayer.PlayerGui.HUD.Frame.BlackMarket:Destroy()
	game:GetService("Players").LocalPlayer.PlayerGui.HUD.Frame.LiftRemind:Destroy()
	game:GetService("Players").LocalPlayer.PlayerGui.HUD.Frame.MuscleGain.Gains:Destroy()
	game:GetService("Players").LocalPlayer.PlayerGui.HUD.Frame.RebFrame:Destroy()
	game:GetService("Players").LocalPlayer.PlayerGui.HUD.Frame.ShopFrame:Destroy()
	game:GetService("Players").LocalPlayer.PlayerGui.HUD.Frame.OpenSkins:Destroy()
	game:GetService("Players").LocalPlayer.PlayerGui.HUD.Frame.Bar:Destroy()
	game:GetService("Players").LocalPlayer.PlayerGui.HUD.Frame.StrengthHolder.ImageLabel:Destroy()
	game:GetService("Players").LocalPlayer.PlayerGui.HUD.Frame.CashHolder:Destroy()
	game:GetService("Players").LocalPlayer.PlayerGui.HUD.Frame.CashButton:Destroy()

end)

Admin.MouseButton1Down:connect(function()
	-- Creator: illremember#3799

	-- Credits to infinite yield, harkinian, dex creators

	prefix = ";"
	wait(0.3)
	Commands = {
		'[-] cmdbar is shown when ; is pressed.',
		'[1] kill [plr] -- You need a tool! Will kill the player, use rkill to kill you and player',
		'[2] bring [plr] -- You need a tool! Will bring player to you',
		'[3] spin [plr] -- You need a tool! Makes you and the player spin crazy',
		'[4] unspin -- Use after using spin cmd and dying, so you stop loop teleporting',
		'[5] attach [plr] -- You need a tool! Attaches you to player',
		'[6] unattach [plr] -- Attempts to unattach you from a player',
		'[7] follow [plr] -- Makes you follow behind the player',
		'[8] unfollow',
		'[9] freefall [plr] -- You need a tool! Teleports you and the player up into the air',
		'[10] trail [plr] -- The opposite of follow, you stay infront of player',
		'[11] untrail',
		'[12] orbit [plr] -- Makes you orbit the player',
		'[13] unorbit',
		'[14] fling [plr] -- Makes you fling the player',
		'[15] unfling',
		'[16] fecheck -- Checks if the game is FE or not',
		'[17] void [plr] -- Teleports player to the void',
		'[18] noclip -- Gives you noclip to walk through walls',
		'[19] clip -- Removes noclip',
		'[20] speed [num]/ws [num] -- Changes how fast you walk 16 is default',
		'[21] jumppower [num]/jp [num] -- Changes how high you jump 50 is default',
		'[22] hipheight [num]/hh [num] -- Changes how high you float 0 is default',
		'[23] default -- Changes your speed, jumppower and hipheight to default values',
		'[24] annoy [plr] -- Loop teleports you to the player',
		'[25] unannoy',
		'[26] headwalk [plr] -- Loop teleports you to the player head',
		'[27] unheadwalk',
		'[28] nolimbs -- Removes your arms and legs',
		'[29] god -- Gives you FE Godmode',
		'[30] drophats -- Drops your accessories',
		'[31] droptool -- Drops any tool you have equipped',
		'[32] loopdhats -- Loop drops your accessories',
		'[33] unloopdhats',
		'[34] loopdtool -- Loop drops any tools you have equipped',
		'[35] unloopdtool',
		'[36] invisible -- Gives you invisibility CREDIT TO TIMELESS',
		'[37] view [plr] -- Changes your camera to the player character',
		'[38] unview',
		'[39] goto [plr] -- Teleports you to player',
		'[40] fly -- Allows you to fly, credit to Infinite Yield',
		'[41] unfly',
		'[42] chat [msg] -- Makes you chat a message',
		'[43] spam [msg] -- Spams a message',
		'[44] unspam',
		'[45] spamwait [num] -- Changes delay of chatting a message for the spam command in seconds default is 1 second',
		'[46] pmspam [plr] -- Spams a player in private message',
		'[47] unpmspam',
		'[48] cfreeze [plr] -- Freezes a player on your client, they will only be frozen for you',
		'[49] uncfreeze [plr]',
		'[50] unlockws -- Unlocks the workspace',
		'[51] lockws -- Locks the workspace',
		'[52] btools -- Gives you btools that will only show to you useful for deleting certain blocks only for you',
		'[53] pstand -- Enables platform stand',
		'[54] unpstand -- Disables platform stand',
		'[55] blockhead -- Removes your head mesh',
		'[56] sit',
		'[57] bringobj [obj] -- Only shows on client, brings an object/part to you constantly, can be used to bring healing parts, weapons, money etc, type in exact name',
		'[58] wsvis [num] -- Changes visibility of workspace parts, num should be between 0 and 1, only shows client sided',
		'[59] hypertotal -- Loads in my FE GUI Hypertotal',
		'[60] cmds -- Prints all commands',
		'[61] rmeshhats/blockhats -- Removes the meshes of all your accessories aka block hats',
		'[62] rmeshtool/blocktool -- Removes the mesh of the tool you have equipped aka block tool',
		'[63] spinner -- Makes you spin',
		'[64] nospinner',
		'[65] reach [num] -- Gives you reach, mostly used for swords, say ;reachd for default and enter number after for custom',
		'[66] noreach -- Removes reach, must have tool equipped',
		'[67] rkill [plr] -- Kills you and the player, use kill to just kill the player without dying',
		'[68] tp me [plr] -- Alternative to goto',
		'[69] cbring [plr] -- Brings player infront of you, shows only on client, allows you to do damage to player',
		'[70] uncbring',
		'[71] swap [plr] -- You need a tool! Swaps players position with yours and your position with players',
		'[72] givetool [plr] -- Gives the tool you have equipped to the player',
		'[73] glitch [plr] -- Glitches you and the player, looks very cool',
		'[74] unglitch -- Unglitches you',
		'[75] grespawn -- Alternative to normal respawn and usually works best for when you want to reset with FE Godmode',
		'[76] explorer -- Loads up DEX',
		'[77] reset -- Resets your character.',
		'[78] anim [id] -- Applies an animation on you, must be created by ROBLOX',
		'[79] animgui -- Loads up Energize animations GUI',
		'[80] savepos -- Saves your current position',
		'[81] loadpos -- Teleports you to your saved position',
		'[82] bang [plr] -- 18+ will not work if you have FE Godmode on',
		'[83] unbang',
		'[84] delcmdbar -- Removes the command bar completely',
		'[85] bringmod [obj] -- Brings all the parts in a model, client only, comes from ;bringobj enter exact name of model',
		'[86] shutdown -- Uses harkinians script to shutdown server',
		'[87] respawn -- If grespawn doesnt work you can use respawn',
		'[88] delobj [obj] -- Deletes a certain brick in workspace, client sided',
		'[89] getplrs -- Prints all players in game',
		'[90] deldecal -- Deletes all decals client sided',
		'[91] opfinality -- Loads in my FE GUI Opfinality',
		'[92] remotes -- Prints all remotes in the game in the console when added',
		'[93] noremotes -- Stops printing remotes',
		'[94] tpdefault -- Stops all loop teleports to a player',
		'[95] stopsit -- Will not allow you to sit',
		'[96] gosit -- Allows you to sit',
		'[97] clicktp -- Enables click tp',
		'[98] noclicktp -- Disables click tp',
		'[99] toolson -- If any tools are dropped in the workspace you will automatically get them',
		'[100] toolsoff -- Stops ;toolson',
		'[101] version -- Gets the admin version',
		'[102] state [num] -- Changes your humanoid state, ;unstate to stop.',
		'[103] gravity [num] -- Changes workspace gravity default is 196.2',
		'[104] pgs -- Checks if the game has PGSPhysicsSolverEnabled enabled',
		'[105] clickdel -- Delete any block you press q on, client sided',
		'[106] noclickdel -- Stops clickdel',
		'[107] looprhats -- Loop removes mesh of your hats/loop block hats',
		'[108] unlooprhats -- Stops loop removing mesh',
		'[109] looprtool -- Loop removes mesh of your tool/loop block tools',
		'[110] unlooprtool -- Stops loop removing mesh',
		'[111] givealltools [plr] -- Gives all the tools you have in your backpack to the player',
		'[112] age [plr] -- Makes you chat the account age of the player',
		'[113] id [plr] -- Makes you chat the account ID of the player',
		'[114] .age [plr] -- Privately shows you the account age of the player',
		'[115] .id [plr] -- Privately shows you the account ID of the player',
		'[116] gameid -- Shows the game ID',
		'[117] removeinvis -- Removes all invisible walls/parts, client sided',
		'[118] removefog -- Removes fog, client sided',
		'[119] disable -- Disables your character by removing humanoid',
		'[120] enable -- Enables your character by adding humanoid',
		'[121] prefix [key] -- Changes the prefix used, default is ;',
		'[122] ;resetprefix -- Resets the prefix to ; incase you change it to an unusable prefix. Say exactly ";resetprefix" to do this command, no matter what your prefix is set to.',
		'[123] flyspeed [num] -- Change your fly speed, default is 1',
		'[124] carpet [plr] -- Makes you a carpet for a player, will not work if FE Godmode is on',
		'[125] uncarpet -- Stops carpet player',
		'[126] stare [plr] -- Turns your character to stare at another player',
		'[127] unstare -- Stops stare player',
		'[128] logchat -- Logs all chat (including /e and whispers) of all players',
		'[129] unlogchat -- Disables logchat',
		'[130] fixcam -- Fixes/resets your camera',
		'[131] unstate -- Stops changing state',
	}
	speedget = 1

	lplayer = game:GetService("Players").LocalPlayer

	lplayer.CharacterAdded:Connect(function(character)
		spin = false
		flying = false
		staring = false
		banpl = false
	end)

	function change()
		prefix = prefix
		speedfly = speedfly
	end

	function GetPlayer(String) -- Credit to Timeless/xFunnieuss
		local Found = {}
		local strl = String:lower()
		if strl == "all" then
			for i,v in pairs(game:GetService("Players"):GetPlayers()) do
				table.insert(Found,v)
			end
		elseif strl == "others" then
			for i,v in pairs(game:GetService("Players"):GetPlayers()) do
				if v.Name ~= lplayer.Name then
					table.insert(Found,v)
				end
			end   
		elseif strl == "me" then
			for i,v in pairs(game:GetService("Players"):GetPlayers()) do
				if v.Name == lplayer.Name then
					table.insert(Found,v)
				end
			end  
		else
			for i,v in pairs(game:GetService("Players"):GetPlayers()) do
				if v.Name:lower():sub(1, #String) == String:lower() then
					table.insert(Found,v)
				end
			end    
		end
		return Found    
	end

	local Mouse = lplayer:GetMouse()

	spin = false
	followed = false
	traill = false
	noclip = false
	annoying = false
	hwalk = false
	droppinghats = false
	droppingtools = false
	flying = false
	spamdelay = 1
	spamming = false
	spammingpm = false
	cbringing = false
	remotes = true
	added = true
	binds = false
	stopsitting = false
	clickgoto = false
	gettingtools = false
	removingmeshhats = false
	removingmeshtool = false
	clickdel = false
	staring = false
	chatlogs = false
	banpl = false
	changingstate = false
	statechosen = 0

	adminversion = "Reviz Admin by illremember, Version 2.0"

	flying = false
	speedfly = 1

	function plrchat(plr, chat)
		print(plr.Name..": "..tick().."\n"..chat)
	end

	for i,v in pairs(game:GetService("Players"):GetPlayers()) do
		v.Chatted:connect(function(chat)
			if chatlogs then
				plrchat(v, chat)
			end
		end)
	end
	game:GetService("Players").PlayerAdded:connect(function(plr)
		plr.Chatted:connect(function(chat)
			if chatlogs then
				plrchat(plr, chat)
			end
		end)
	end)


	local ScreenGui = Instance.new("ScreenGui")
	local Frame = Instance.new("Frame")
	local CMDBAR = Instance.new("TextBox")
	ScreenGui.Parent = game:GetService("CoreGui")
	Frame.Parent = ScreenGui
	Frame.BackgroundColor3 = Color3.new(0.3, 0.1, 0.1)
	Frame.BackgroundTransparency = 0.3
	Frame.Position = UDim2.new(0.5, 0, 0, 10)
	Frame.Size = UDim2.new(0, 200, 0, 40)
	Frame.Active = true
	Frame.Draggable = true
	CMDBAR.Name = "CMDBAR"
	CMDBAR.Parent = Frame
	CMDBAR.BackgroundColor3 = Color3.new(0.105882, 0.164706, 0.207843)
	CMDBAR.BackgroundTransparency = 0.20000000298023
	CMDBAR.Size = UDim2.new(0, 180, 0, 20)
	CMDBAR.Position = UDim2.new(0.05, 0, 0.25, 0)
	CMDBAR.Font = Enum.Font.SourceSansLight
	CMDBAR.FontSize = Enum.FontSize.Size14
	CMDBAR.TextColor3 = Color3.new(0.945098, 0.945098, 0.945098)
	CMDBAR.TextScaled = true
	CMDBAR.TextSize = 14
	CMDBAR.TextWrapped = true
	CMDBAR.Text = "Press ; to type, Enter to execute"

	local CMDS = Instance.new("ScreenGui")
	local CMDSFRAME = Instance.new("Frame")
	local ScrollingFrame = Instance.new("ScrollingFrame")
	local TextLabel = Instance.new("TextLabel")
	local closegui = Instance.new("TextButton")
	CMDS.Name = "CMDS"
	CMDS.Parent = game:GetService("CoreGui")
	CMDSFRAME.Name = "CMDSFRAME"
	CMDSFRAME.Parent = CMDS
	CMDSFRAME.Active = true
	CMDSFRAME.BackgroundColor3 = Color3.new(0.223529, 0.231373, 0.309804)
	CMDSFRAME.BorderSizePixel = 0
	CMDSFRAME.Draggable = true
	CMDSFRAME.Position = UDim2.new(0, 315, 0, 100)
	CMDSFRAME.Size = UDim2.new(0, 275, 0, 275)
	CMDSFRAME.Visible = false
	ScrollingFrame.Parent = CMDSFRAME
	ScrollingFrame.BackgroundColor3 = Color3.new(0.160784, 0.160784, 0.203922)
	ScrollingFrame.BorderSizePixel = 0
	ScrollingFrame.Position = UDim2.new(0, 0, 0.0729999989, 0)
	ScrollingFrame.Size = UDim2.new(1.04999995, 0, 0.92900002, 0)
	ScrollingFrame.CanvasSize = UDim2.new(0, 0, 10, 0)
	TextLabel.Parent = ScrollingFrame
	TextLabel.BackgroundColor3 = Color3.new(1, 1, 1)
	TextLabel.BackgroundTransparency = 1
	TextLabel.Size = UDim2.new(0.930000007, 0, 1, 0)
	TextLabel.Font = Enum.Font.SourceSans
	TextLabel.FontSize = Enum.FontSize.Size18
	TextLabel.Text = "[-] cmdbar is shown when ; is pressed.,\n[1] kill [plr] -- You need a tool! Will kill the player, use rkill to kill you and player,\n[2] bring [plr] -- You need a tool! Will bring player to you,\n[3] spin [plr] -- You need a tool! Makes you and the player spin crazy,\n[4] unspin -- Use after using spin cmd and dying, so you stop loop teleporting,\n[5] attach [plr] -- You need a tool! Attaches you to player,\n[6] unattach [plr] -- Attempts to unattach you from a player,\n[7] follow [plr] -- Makes you follow behind the player,\n[8] unfollow,\n[9] freefall [plr] -- You need a tool! Teleports you and the player up into the air,\n[10] trail [plr] -- The opposite of follow, you stay infront of player,\n[11] untrail,\n[12] orbit [plr] -- Makes you orbit the player,\n[13] unorbit,\n[14] fling [plr] -- Makes you fling the player,\n[15] unfling,\n[16] fecheck -- Checks if the game is FE or not,\n[17] void [plr] -- Teleports player to the void,\n[18] noclip -- Gives you noclip to walk through walls,\n[19] clip -- Removes noclip,\n[20] speed [num]/ws [num] -- Changes how fast you walk 16 is default,\n[21] jumppower [num]/jp [num] -- Changes how high you jump 50 is default,\n[22] hipheight [num]/hh [num] -- Changes how high you float 0 is default,\n[23] default -- Changes your speed, jumppower and hipheight to default values,\n[24] annoy [plr] -- Loop teleports you to the player,\n[25] unannoy,\n[26] headwalk [plr] -- Loop teleports you to the player head,\n[27] unheadwalk,\n[28] nolimbs -- Removes your arms and legs,\n[29] god -- Gives you FE Godmode,\n[30] drophats -- Drops your accessories,\n[31] droptool -- Drops any tool you have equipped,\n[32] loopdhats -- Loop drops your accessories,\n[33] unloopdhats,\n[34] loopdtool -- Loop drops any tools you have equipped,\n[35] unloopdtool,\n[36] invisible -- Gives you invisibility CREDIT TO TIMELESS,\n[37] view [plr] -- Changes your camera to the player character,\n[38] unview,\n[39] goto [plr] -- Teleports you to player,\n[40] fly -- Allows you to fly,\n[41] unfly,\n[42] chat [msg] -- Makes you chat a message,\n[43] spam [msg] -- Spams a message,\n[44] unspam,\n[45] spamwait [num] -- Changes delay of chatting a message for the spam command in seconds default is 1 second,\n[46] pmspam [plr] -- Spams a player in private message,\n[47] unpmspam,\n[48] cfreeze [plr] -- Freezes a player on your client, they will only be frozen for you,\n[49] uncfreeze [plr],\n[50] unlockws -- Unlocks the workspace,\n[51] lockws -- Locks the workspace,\n[52] btools -- Gives you btools that will only show to you useful for deleting certain blocks only for you,\n[53] pstand -- Enables platform stand,\n[54] unpstand -- Disables platform stand,\n[55] blockhead -- Removes your head mesh,\n[56] sit,\n[57] bringobj [obj] -- Only shows on client, brings an object/part to you constantly, can be used to bring healing parts, weapons, money etc, type in exact name,\n[58] wsvis [num] -- Changes visibility of workspace parts, num should be between 0 and 1, only shows client sided,\n[59] hypertotal -- Loads in my FE GUI Hypertotal,\n[60] cmds -- Prints all commands,\n[61] rmeshhats/blockhats -- Removes the meshes of all your accessories aka block hats,\n[62] rmeshtool/blocktool -- Removes the mesh of the tool you have equipped aka block tool,\n[63] spinner -- Makes you spin,\n[64] nospinner,\n[65] reach [num] -- Gives you reach, mostly used for swords, say ;reachd for default and enter number after for custom,\n[66] noreach -- Removes reach, must have tool equipped,\n[67] rkill [plr] -- Kills you and the player, use kill to just kill the player without dying,\n[68] tp me [plr] -- Alternative to goto,\n[69] cbring [plr] -- Brings player infront of you, shows only on client, allows you to do damage to player,\n[70] uncbring,\n[71] swap [plr] -- You need a tool! Swaps players position with yours and your position with players,\n[72] givetool [plr] -- Gives the tool you have equipped to the player,\n[73] glitch [plr] -- Glitches you and the player, looks very cool,\n[74] unglitch -- Unglitches you,\n[75] grespawn -- Alternative to normal respawn and usually works best for when you want to reset with FE Godmode,\n[76] explorer -- Loads up DEX,\n[77] reset -- Resets your character.,\n[78] anim [id] -- Applies an animation on you, must be created by ROBLOX,\n[79] animgui -- Loads up Energize animations GUI,\n[80] savepos -- Saves your current position,\n[81] loadpos -- Teleports you to your saved position,\n[82] bang [plr] -- 18+,\n[83] unbang,\n[84] delcmdbar -- Removes the command bar completely,\n[85] bringmod [obj] -- Brings all the parts in a model, client only, comes from ;bringobj enter exact name of model,\n[86] shutdown -- Uses harkinians script to shutdown server,\n[87] respawn -- If grespawn doesnt work you can use respawn,\n[88] delobj [obj] -- Deletes a certain brick in workspace, client sided,\n[89] getplrs -- Prints all players in game,\n[90] deldecal -- Deletes all decals client sided,\n[91] opfinality -- Loads in my FE GUI Opfinality,\n[92] remotes -- Prints all remotes in the game in the console when added,\n[93] noremotes -- Stops printing remotes,\n[94] tpdefault -- Stops all loop teleports to a player,\n[95] stopsit -- Will not allow you to sit,\n[96] gosit -- Allows you to sit,\n[97] clicktp -- Enables click tp,\n[98] noclicktp -- Disables click tp,\n[99] toolson -- If any tools are dropped in the workspace you will automatically get them,\n[100] toolsoff -- Stops ;toolson,\n[101] version -- Gets the admin version, \n This list of commands is NOT showing everything, go to my thread in the pastebin link to see ALL commands."
	TextLabel.TextColor3 = Color3.new(1, 1, 1)
	TextLabel.TextSize = 15
	TextLabel.TextWrapped = true
	TextLabel.TextXAlignment = Enum.TextXAlignment.Left
	TextLabel.TextYAlignment = Enum.TextYAlignment.Top
	closegui.Name = "closegui"
	closegui.Parent = CMDSFRAME
	closegui.BackgroundColor3 = Color3.new(0.890196, 0.223529, 0.0588235)
	closegui.BorderSizePixel = 0
	closegui.Position = UDim2.new(0.995000005, 0, 0, 0)
	closegui.Size = UDim2.new(0.0545952693, 0, 0.0728644878, 0)
	closegui.Font = Enum.Font.SourceSansBold
	closegui.FontSize = Enum.FontSize.Size24
	closegui.Text = "X"
	closegui.TextColor3 = Color3.new(1, 1, 1)
	closegui.TextSize = 20

	closegui.MouseButton1Click:connect(function()
		CMDSFRAME.Visible = false
	end)

	game:GetService('RunService').Stepped:connect(function()
		if spin then
			lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[spinplr.Name].Character.HumanoidRootPart.CFrame
		end
		if followed then
			lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[flwplr.Name].Character.HumanoidRootPart.CFrame + game:GetService("Players")[flwplr.Name].Character.HumanoidRootPart.CFrame.lookVector * -5
		end
		if traill then
			lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[trlplr.Name].Character.HumanoidRootPart.CFrame + game:GetService("Players")[trlplr.Name].Character.HumanoidRootPart.CFrame.lookVector * 5
		end
		if annoying then
			lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[annplr.Name].Character.HumanoidRootPart.CFrame
		end
		if hwalk then
			lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[hdwplr.Name].Character.HumanoidRootPart.CFrame + Vector3.new(0, 4, 0)
		end
		if staring then
			lplayer.Character.HumanoidRootPart.CFrame = CFrame.new(lplayer.Character.Torso.Position, game:GetService("Players")[stareplr.Name].Character.Torso.Position)
		end
	end)
	game:GetService('RunService').Stepped:connect(function()
		if noclip then
			if lplayer.Character.Humanoid.RigType == Enum.HumanoidRigType.R6 then
				lplayer.Character.Head.CanCollide = false
				lplayer.Character.Torso.CanCollide = false
				lplayer.Character["Left Leg"].CanCollide = false
				lplayer.Character["Right Leg"].CanCollide = false
			else
				lplayer.Character.Humanoid:ChangeState(11)
			end
		end
		if changingstate then
			lplayer.Character.Humanoid:ChangeState(statechosen)
		end
	end)
	game:GetService('RunService').Stepped:connect(function()
		if droppinghats then
			for i,v in pairs(lplayer.Character:GetChildren()) do
				if (v:IsA("Accessory")) or (v:IsA("Hat")) then
					v.Parent = workspace
				end
			end
		end
		if droppingtools then
			for i,v in pairs(lplayer.Character:GetChildren()) do
				if (v:IsA("Tool")) then
					v.Parent = workspace
				end
			end
		end
		if removingmeshhats then
			for i,v in pairs(lplayer.Character:GetChildren()) do
				if (v:IsA("Accessory")) or (v:IsA("Hat")) then
					v.Handle.Mesh:Destroy()
				end
			end
		end
		if removingmeshtool then
			for i,v in pairs(lplayer.Character:GetChildren()) do
				if (v:IsA("Tool")) then
					v.Handle.Mesh:Destroy()
				end
			end
		end
	end)
	game:GetService('RunService').Stepped:connect(function()
		if banpl then
			lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[bplrr].Character.HumanoidRootPart.CFrame
		end
	end)
	game:GetService('RunService').Stepped:connect(function()
		if stopsitting then
			lplayer.Character.Humanoid.Sit = false
		end
	end)

	plr = lplayer 
	hum = plr.Character.HumanoidRootPart
	mouse = plr:GetMouse() 
	mouse.KeyDown:connect(function(key) 
		if key == "e" then 
			if mouse.Target then 
				if clickgoto then
					hum.CFrame = CFrame.new(mouse.Hit.x, mouse.Hit.y + 5, mouse.Hit.z)
				elseif clickdel then
					mouse.Target:Destroy()
				end
			end 
		end
	end)

	game:GetService("Workspace").ChildAdded:connect(function(part)
		if gettingtools then
			if part:IsA("Tool") then
				part.Handle.CFrame = lplayer.Character.HumanoidRootPart.CFrame
			end
		end
	end)

	lplayer.Chatted:Connect(function(msg)
		if string.sub(msg, 1, 6) == (prefix.."kill ") then
			if string.sub(msg, 7) == "me" then
				lplayer.Character.HumanoidRootPart.CFrame = CFrame.new(100000,0,100000)
			else
				for i,v in pairs(GetPlayer(string.sub(msg, 7)))do
					local NOW = lplayer.Character.HumanoidRootPart.CFrame
					lplayer.Character.Humanoid.Name = 1
					local l = lplayer.Character["1"]:Clone()
					l.Parent = lplayer.Character
					l.Name = "Humanoid"
					wait(0.1)
					lplayer.Character["1"]:Destroy()
					game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character
					lplayer.Character.Animate.Disabled = true
					wait(0.1)
					lplayer.Character.Animate.Disabled = false
					lplayer.Character.Humanoid.DisplayDistanceType = "None"
					for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
						lplayer.Character.Humanoid:EquipTool(v)
					end
					local function tp(player,player2)
						local char1,char2=player.Character,player2.Character
						if char1 and char2 then
							char1:MoveTo(char2.Head.Position)
						end
					end
					wait(0.1)
					lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
					wait(0.2)
					lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
					wait(0.5)
					lplayer.Character.HumanoidRootPart.CFrame = CFrame.new(Vector3.new(-100000,10,-100000))
					wait(0.7)
					tp(lplayer,game:GetService("Players")[v.Name])
					wait(0.7)
					lplayer.Character.HumanoidRootPart.CFrame = NOW
					game:GetService("StarterGui"):SetCore("SendNotification", {
						Title = "Tools needed!";
						Text = "You need a tool in your backpack for this command!";
					})
				end
			end
		end
		if string.sub(msg, 1, 7) == (prefix.."bring ") then
			for i,v in pairs(GetPlayer(string.sub(msg, 8)))do
				local NOW = lplayer.Character.HumanoidRootPart.CFrame
				lplayer.Character.Humanoid.Name = 1
				local l = lplayer.Character["1"]:Clone()
				l.Parent = lplayer.Character
				l.Name = "Humanoid"
				wait(0.1)
				lplayer.Character["1"]:Destroy()
				game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character
				lplayer.Character.Animate.Disabled = true
				wait(0.1)
				lplayer.Character.Animate.Disabled = false
				lplayer.Character.Humanoid.DisplayDistanceType = "None"
				for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
					lplayer.Character.Humanoid:EquipTool(v)
				end
				local function tp(player,player2)
					local char1,char2=player.Character,player2.Character
					if char1 and char2 then
						char1.HumanoidRootPart.CFrame = char2.HumanoidRootPart.CFrame
					end
				end
				local function getout(player,player2)
					local char1,char2=player.Character,player2.Character
					if char1 and char2 then
						char1:MoveTo(char2.Head.Position)
					end
				end
				tp(game:GetService("Players")[v.Name], lplayer)
				wait(0.2)
				tp(game:GetService("Players")[v.Name], lplayer)
				wait(0.5)
				lplayer.Character.HumanoidRootPart.CFrame = NOW
				wait(0.5)
				getout(lplayer, game:GetService("Players")[v.Name])
				wait(0.3)
				lplayer.Character.HumanoidRootPart.CFrame = NOW
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Tools needed!";
					Text = "You need a tool in your backpack for this command!";
				})
			end
		end
		if string.sub(msg, 1, 6) == (prefix.."spin ") then
			for i,v in pairs(GetPlayer(string.sub(msg, 7))) do
				lplayer.Character.Humanoid.Name = 1
				local l = lplayer.Character["1"]:Clone()
				l.Parent = lplayer.Character
				l.Name = "Humanoid"
				wait(0.1)
				lplayer.Character["1"]:Destroy()
				game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character
				lplayer.Character.Animate.Disabled = true
				wait(0.1)
				lplayer.Character.Animate.Disabled = false
				lplayer.Character.Humanoid.DisplayDistanceType = "None"
				lplayer.Character.Animate.Disabled = false
				for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
					lplayer.Character.Humanoid:EquipTool(v)
				end
				lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character["Left Arm"].CFrame
				spinplr = v
				wait(0.5)
				spin = true
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Tools needed!";
					Text = "You need a tool in your backpack for this command!";
				})
			end
		end
		if string.sub(msg, 1, 7) == (prefix.."unspin") then
			spin = false
		end
		if string.sub(msg, 1, 8) == (prefix.."attach ") then
			for i,v in pairs(GetPlayer(string.sub(msg, 9))) do
				lplayer.Character.Humanoid.Name = 1
				local l = lplayer.Character["1"]:Clone()
				l.Parent = lplayer.Character
				l.Name = "Humanoid"
				wait(0.1)
				lplayer.Character["1"]:Destroy()
				game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character
				lplayer.Character.Animate.Disabled = true
				wait(0.1)
				lplayer.Character.Animate.Disabled = false
				lplayer.Character.Humanoid.DisplayDistanceType = "None"
				for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
					lplayer.Character.Humanoid:EquipTool(v)
				end
				lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character["Left Arm"].CFrame
				wait(0.3)
				lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character["Left Arm"].CFrame
				attplr = v
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Tools needed!";
					Text = "You need a tool in your backpack for this command!";
				})
			end
		end
		if string.sub(msg, 1, 10) == (prefix.."unattach ") then
			for i,v in pairs(GetPlayer(string.sub(msg, 11))) do
				local function getout(player,player2)
					local char1,char2=player.Character,player2.Character
					if char1 and char2 then
						char1:MoveTo(char2.Head.Position)
					end
				end
				getout(lplayer, game:GetService("Players")[v.Name])
			end
		end
		if string.sub(msg, 1, 8) == (prefix.."follow ") then
			for i,v in pairs(GetPlayer(string.sub(msg, 9))) do
				followed = true
				flwplr = v
			end
		end
		if string.sub(msg, 1, 9) == (prefix.."unfollow") then
			followed = false
		end
		if string.sub(msg, 1, 10) == (prefix.."freefall ") then
			for i,v in pairs(GetPlayer(string.sub(msg, 11))) do
				local NOW = lplayer.Character.HumanoidRootPart.CFrame
				lplayer.Character.Humanoid.Name = 1
				local l = lplayer.Character["1"]:Clone()
				l.Parent = lplayer.Character
				l.Name = "Humanoid"
				wait(0.1)
				lplayer.Character["1"]:Destroy()
				game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character
				lplayer.Character.Animate.Disabled = true
				wait(0.1)
				lplayer.Character.Animate.Disabled = false
				lplayer.Character.Humanoid.DisplayDistanceType = "None"
				for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
					lplayer.Character.Humanoid:EquipTool(v)
				end
				lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
				wait(0.2)
				lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
				wait(0.6)
				lplayer.Character.HumanoidRootPart.CFrame = NOW
				wait(0.6)
				lplayer.Character.HumanoidRootPart.CFrame = CFrame.new(0,50000,0)
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Tools needed!";
					Text = "You need a tool in your backpack for this command!";
				})
			end
		end
		if string.sub(msg, 1, 7) == (prefix.."trail ") then
			for i,v in pairs(GetPlayer(string.sub(msg, 8))) do
				traill = true
				trlplr = v
			end
		end
		if string.sub(msg, 1, 8) == (prefix.."untrail") then
			traill = false
		end
		if string.sub(msg, 1, 7) == (prefix.."orbit ") then
			if string.sub(msg, 8) == "all" or string.sub(msg, 8) == "others" or string.sub(msg, 8) == "me" then
				lplayer.Character.HumanoidRootPart.CFrame = lplayer.Character.HumanoidRootPart.CFrame
			else
				for i,v in pairs(GetPlayer(string.sub(msg, 8))) do
					local o = Instance.new("RocketPropulsion")
					o.Parent = lplayer.Character.HumanoidRootPart
					o.Name = "Orbit"
					o.Target = game:GetService("Players")[v.Name].Character.HumanoidRootPart
					o:Fire()
					noclip = true
				end
			end
		end
		if string.sub(msg, 1, 8) == (prefix.."unorbit") then
			lplayer.Character.HumanoidRootPart.Orbit:Destroy()
			noclip = false
		end
		if string.sub(msg, 1, 7) == (prefix.."fling ") then
			if string.sub(msg, 8) == "all" or string.sub(msg, 8) == "others" or string.sub(msg, 8) == "me" then
				lplayer.Character.HumanoidRootPart.CFrame = lplayer.Character.HumanoidRootPart.CFrame
			else
				for i,v in pairs(GetPlayer(string.sub(msg, 8))) do
					local y = Instance.new("RocketPropulsion")
					y.Parent = lplayer.Character.HumanoidRootPart
					y.CartoonFactor = 1
					y.MaxThrust = 800000
					y.MaxSpeed = 1000
					y.ThrustP = 200000
					y.Name = "Fling"
					game:GetService("Workspace").CurrentCamera.CameraSubject = game:GetService("Players")[v.Name].Character.Head
					y.Target = game:GetService("Players")[v.Name].Character.HumanoidRootPart
					y:Fire()
					noclip = true
				end
			end
		end
		if string.sub(msg, 1, 8) == (prefix.."unfling") then
			noclip = false
			lplayer.Character.HumanoidRootPart.Fling:Destroy()
			game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character.Head
			wait(0.4)
			lplayer.Character.HumanoidRootPart.Fling:Destroy()
		end
		if string.sub(msg, 1, 8) == (prefix.."fecheck") then
			if game:GetService("Workspace").FilteringEnabled == true then
				warn("FE is Enabled (Filtering Enabled)")
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "FE is Enabled";
					Text = "Filtering Enabled. Enjoy using Reviz Admin!";
				})
			else
				warn("FE is Disabled (Filtering Disabled) Consider using a different admin script.")
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "FE is Disabled";
					Text = "Filtering Disabled. Consider using a different admin script.";
				})
			end
		end
		if string.sub(msg, 1, 6) == (prefix.."void ") then
			for i,v in pairs(GetPlayer(string.sub(msg, 7))) do
				lplayer.Character.Humanoid.Name = 1
				local l = lplayer.Character["1"]:Clone()
				l.Parent = lplayer.Character
				l.Name = "Humanoid"
				wait(0.1)
				lplayer.Character["1"]:Destroy()
				game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character
				lplayer.Character.Animate.Disabled = true
				wait(0.1)
				lplayer.Character.Animate.Disabled = false
				lplayer.Character.Humanoid.DisplayDistanceType = "None"
				for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
					lplayer.Character.Humanoid:EquipTool(v)
				end
				lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
				wait(0.2)
				lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
				wait(0.6)
				lplayer.Character.HumanoidRootPart.CFrame = CFrame.new(999999999999999,0,999999999999999)
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Tools needed!";
					Text = "You need a tool in your backpack for this command!";
				})
			end
		end
		if string.sub(msg, 1, 7) == (prefix.."noclip") then
			noclip = true
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Noclip enabled";
				Text = "Type ;clip to disable";
			})
		end
		if string.sub(msg, 1, 5) == (prefix.."clip") then
			noclip = false
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Noclip disabled";
				Text = "Type ;noclip to enable";
			})
		end
		if string.sub(msg, 1, 7) == (prefix.."speed ") then
			lplayer.Character.Humanoid.WalkSpeed = (string.sub(msg, 8))
		end
		if string.sub(msg, 1, 4) == (prefix.."ws ") then
			lplayer.Character.Humanoid.WalkSpeed = (string.sub(msg, 5))
		end
		if string.sub(msg, 1, 11) == (prefix.."hipheight ") then
			lplayer.Character.Humanoid.HipHeight = (string.sub(msg, 12))
		end
		if string.sub(msg, 1, 4) == (prefix.."hh ") then
			lplayer.Character.Humanoid.HipHeight = (string.sub(msg, 5))
		end
		if string.sub(msg, 1, 11) == (prefix.."jumppower ") then
			lplayer.Character.Humanoid.JumpPower = (string.sub(msg, 12))
		end
		if string.sub(msg, 1, 4) == (prefix.."jp ") then
			lplayer.Character.Humanoid.JumpPower = (string.sub(msg, 5))
		end
		if string.sub(msg, 1, 8) == (prefix.."default") then
			lplayer.Character.Humanoid.JumpPower = 50
			lplayer.Character.Humanoid.WalkSpeed = 16
			lplayer.Character.Humanoid.HipHeight = 0
		end
		if string.sub(msg, 1, 7) == (prefix.."annoy ") then
			for i,v in pairs(GetPlayer(string.sub(msg, 8))) do
				annoying = true
				annplr = v
			end
		end
		if string.sub(msg, 1, 8) == (prefix.."unannoy") then
			annoying = false
		end
		if string.sub(msg, 1, 10) == (prefix.."headwalk ") then
			for i,v in pairs(GetPlayer(string.sub(msg, 11))) do
				hwalk = true
				hdwplr = v
			end
		end
		if string.sub(msg, 1, 11) == (prefix.."unheadwalk") then
			hwalk = false
		end
		if string.sub(msg, 1, 8) == (prefix.."nolimbs") then
			lplayer.Character["Left Leg"]:Destroy()
			lplayer.Character["Left Arm"]:Destroy()
			lplayer.Character["Right Leg"]:Destroy()
			lplayer.Character["Right Arm"]:Destroy()
		end
		if string.sub(msg, 1, 4) == (prefix.."god") then
			lplayer.Character.Humanoid.Name = 1
			local l = lplayer.Character["1"]:Clone()
			l.Parent = lplayer.Character
			l.Name = "Humanoid"
			wait(0.1)
			lplayer.Character["1"]:Destroy()
			game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character
			lplayer.Character.Animate.Disabled = true
			wait(0.1)
			lplayer.Character.Animate.Disabled = false
			lplayer.Character.Humanoid.DisplayDistanceType = "None"
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "FE Godmode enabled";
				Text = "Use ;grespawn or ;respawn to remove";
			})
		end
		if string.sub(msg, 1, 9) == (prefix.."drophats") then
			for i,v in pairs(lplayer.Character:GetChildren()) do
				if (v:IsA("Accessory")) or (v:IsA("Hat")) then
					v.Parent = workspace
				end
			end
		end
		if string.sub(msg, 1, 9) == (prefix.."droptool") then
			for i,v in pairs(lplayer.Character:GetChildren()) do
				if (v:IsA("Tool")) then
					v.Parent = workspace
				end
			end
		end
		if string.sub(msg, 1, 10) == (prefix.."loopdhats") then
			droppinghats = true
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Loop Drop Enabled";
				Text = "Type ;unloopdhats to disable";
			})
		end
		if string.sub(msg, 1, 12) == (prefix.."unloopdhats") then
			droppinghats = false
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Loop Drop Disabled";
				Text = "Type ;loopdhats to enable.";
			})
		end
		if string.sub(msg, 1, 10) == (prefix.."loopdtool") then
			droppingtools = true
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Loop Drop Enabled";
				Text = "Type ;unloopdtool to disable";
			})
		end
		if string.sub(msg, 1, 12) == (prefix.."unloopdtool") then
			droppingtools = false
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Loop Drop Disabled";
				Text = "Type ;loopdtool to enable.";
			})
		end
		if string.sub(msg, 1, 10) == (prefix.."invisible") then -- Credit to Timeless
			Local = game:GetService('Players').LocalPlayer
			Char  = Local.Character
			touched,tpdback = false, false
			box = Instance.new('Part',workspace)
			box.Anchored = true
			box.CanCollide = true
			box.Size = Vector3.new(10,1,10)
			box.Position = Vector3.new(0,10000,0)
			box.Touched:connect(function(part)
				if (part.Parent.Name == Local.Name) then
					if touched == false then
						touched = true
						function apply()
							if script.Disabled ~= true then
								no = Char.HumanoidRootPart:Clone()
								wait(.25)
								Char.HumanoidRootPart:Destroy()
								no.Parent = Char
								Char:MoveTo(loc)
								touched = false
							end end
						if Char then
							apply()
						end
					end
				end
			end)
			repeat wait() until Char
			loc = Char.HumanoidRootPart.Position
			Char:MoveTo(box.Position + Vector3.new(0,.5,0))
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Invisibility enabled!";
				Text = "Reset or use ;respawn to remove.";
			})
		end
		if string.sub(msg, 1, 6) == (prefix.."view ") then
			for i,v in pairs(GetPlayer(string.sub(msg, 7))) do
				if game:GetService("Players")[v.Name].Character.Humanoid then
					game:GetService("Workspace").CurrentCamera.CameraSubject = game:GetService("Players")[v.Name].Character.Humanoid
				else
					game:GetService("Workspace").CurrentCamera.CameraSubject = game:GetService("Players")[v.Name].Character.Head
				end
			end
		end
		if string.sub(msg, 1, 7) == (prefix.."unview") then
			if lplayer.Character.Humanoid then
				game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character.Humanoid
			else
				game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character.Head
			end
		end
		if string.sub(msg, 1, 6) == (prefix.."goto ") then
			for i,v in pairs(GetPlayer(string.sub(msg, 7))) do
				lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
			end
		end
		if string.sub(msg, 1, 4) == (prefix.."fly") then
			repeat wait() until lplayer and lplayer.Character and lplayer.Character:FindFirstChild('HumanoidRootPart') and lplayer.Character:FindFirstChild('Humanoid')
			repeat wait() until Mouse

			local T = lplayer.Character.HumanoidRootPart
			local CONTROL = {F = 0, B = 0, L = 0, R = 0}
			local lCONTROL = {F = 0, B = 0, L = 0, R = 0}
			local SPEED = speedget

			local function fly()
				flying = true
				local BG = Instance.new('BodyGyro', T)
				local BV = Instance.new('BodyVelocity', T)
				BG.P = 9e4
				BG.maxTorque = Vector3.new(9e9, 9e9, 9e9)
				BG.cframe = T.CFrame
				BV.velocity = Vector3.new(0, 0.1, 0)
				BV.maxForce = Vector3.new(9e9, 9e9, 9e9)
				spawn(function()
					repeat wait()
						lplayer.Character.Humanoid.PlatformStand = true
						if CONTROL.L + CONTROL.R ~= 0 or CONTROL.F + CONTROL.B ~= 0 then
							SPEED = 50
						elseif not (CONTROL.L + CONTROL.R ~= 0 or CONTROL.F + CONTROL.B ~= 0) and SPEED ~= 0 then
							SPEED = 0
						end
						if (CONTROL.L + CONTROL.R) ~= 0 or (CONTROL.F + CONTROL.B) ~= 0 then
							BV.velocity = ((workspace.CurrentCamera.CoordinateFrame.lookVector * (CONTROL.F + CONTROL.B)) + ((workspace.CurrentCamera.CoordinateFrame * CFrame.new(CONTROL.L + CONTROL.R, (CONTROL.F + CONTROL.B) * 0.2, 0).p) - workspace.CurrentCamera.CoordinateFrame.p)) * SPEED
							lCONTROL = {F = CONTROL.F, B = CONTROL.B, L = CONTROL.L, R = CONTROL.R}
						elseif (CONTROL.L + CONTROL.R) == 0 and (CONTROL.F + CONTROL.B) == 0 and SPEED ~= 0 then
							BV.velocity = ((workspace.CurrentCamera.CoordinateFrame.lookVector * (lCONTROL.F + lCONTROL.B)) + ((workspace.CurrentCamera.CoordinateFrame * CFrame.new(lCONTROL.L + lCONTROL.R, (lCONTROL.F + lCONTROL.B) * 0.2, 0).p) - workspace.CurrentCamera.CoordinateFrame.p)) * SPEED
						else
							BV.velocity = Vector3.new(0, 0.1, 0)
						end
						BG.cframe = workspace.CurrentCamera.CoordinateFrame
					until not flying
					CONTROL = {F = 0, B = 0, L = 0, R = 0}
					lCONTROL = {F = 0, B = 0, L = 0, R = 0}
					SPEED = 0
					BG:destroy()
					BV:destroy()
					lplayer.Character.Humanoid.PlatformStand = false
				end)
			end
			Mouse.KeyDown:connect(function(KEY)
				if KEY:lower() == 'w' then
					CONTROL.F = speedfly
				elseif KEY:lower() == 's' then
					CONTROL.B = -speedfly
				elseif KEY:lower() == 'a' then
					CONTROL.L = -speedfly 
				elseif KEY:lower() == 'd' then 
					CONTROL.R = speedfly
				end
			end)
			Mouse.KeyUp:connect(function(KEY)
				if KEY:lower() == 'w' then
					CONTROL.F = 0
				elseif KEY:lower() == 's' then
					CONTROL.B = 0
				elseif KEY:lower() == 'a' then
					CONTROL.L = 0
				elseif KEY:lower() == 'd' then
					CONTROL.R = 0
				end
			end)
			fly()
		end
		if string.sub(msg, 1, 6) == (prefix.."unfly") then
			flying = false
			lplayer.Character.Humanoid.PlatformStand = false
		end
		if string.sub(msg, 1, 6) == (prefix.."chat ") then
			game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer((string.sub(msg, 7)), "All")
		end
		if string.sub(msg, 1, 6) == (prefix.."spam ") then
			spamtext = (string.sub(msg, 7))
			spamming = true
		end
		if string.sub(msg, 1, 7) == (prefix.."unspam") then
			spamming = false
		end
		if string.sub(msg, 1, 10) == (prefix.."spamwait ") then
			spamdelay = (string.sub(msg, 11))
		end
		if string.sub(msg, 1, 8) == (prefix.."pmspam ") then
			for i,v in pairs(GetPlayer(string.sub(msg, 9))) do
				pmspammed = v.Name
				spammingpm = true
			end
		end
		if string.sub(msg, 1, 9) == (prefix.."unpmspam") then
			spammingpm = false
		end
		if string.sub(msg, 1, 9) == (prefix.."cfreeze ") then
			for i,v in pairs(GetPlayer(string.sub(msg, 10))) do
				v.Character["Left Leg"].Anchored = true
				v.Character["Left Arm"].Anchored = true
				v.Character["Right Leg"].Anchored = true
				v.Character["Right Arm"].Anchored = true
				v.Character.Torso.Anchored = true
				v.Character.Head.Anchored = true
			end
		end
		if string.sub(msg, 1, 11) == (prefix.."uncfreeze ") then
			for i,v in pairs(GetPlayer(string.sub(msg, 12))) do
				v.Character["Left Leg"].Anchored = false
				v.Character["Left Arm"].Anchored = false
				v.Character["Right Leg"].Anchored = false
				v.Character["Right Arm"].Anchored = false
				v.Character.Torso.Anchored = false
				v.Character.Head.Anchored = false
			end
		end
		if string.sub(msg, 1, 9) == (prefix.."unlockws") then
			local a = game:GetService("Workspace"):getChildren()
			for i = 1, #a do
				if a[i].className == "Part" then
					a[i].Locked = false
				elseif a[i].className == "Model" then
					local r = a[i]:getChildren()
					for i = 1, #r do
						if r[i].className == "Part" then
							r[i].Locked = false
						end
					end
				end
			end
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Success!";
				Text = "Workspace unlocked. Use ;lockws to lock.";
			})
		end
		if string.sub(msg, 1, 7) == (prefix.."lockws") then
			local a = game:GetService("Workspace"):getChildren()
			for i = 1, #a do
				if a[i].className == "Part" then
					a[i].Locked = true
				elseif a[i].className == "Model" then
					local r = a[i]:getChildren()
					for i = 1, #r do
						if r[i].className == "Part" then
							r[i].Locked = true
						end
					end
				end
			end
		end
		if string.sub(msg, 1, 7) == (prefix.."btools") then
			local Clone_T = Instance.new("HopperBin",lplayer.Backpack)
			Clone_T.BinType = "Clone"
			local Destruct = Instance.new("HopperBin",lplayer.Backpack)
			Destruct.BinType = "Hammer"
			local Hold_T = Instance.new("HopperBin",lplayer.Backpack)
			Hold_T.BinType = "Grab"
		end
		if string.sub(msg, 1, 7) == (prefix.."pstand") then
			lplayer.Character.Humanoid.PlatformStand = true
		end
		if string.sub(msg, 1, 9) == (prefix.."unpstand") then
			lplayer.Character.Humanoid.PlatformStand = false
		end
		if string.sub(msg, 1, 10) == (prefix.."blockhead") then
			lplayer.Character.Head.Mesh:Destroy()
		end
		if string.sub(msg, 1, 4) == (prefix.."sit") then
			lplayer.Character.Humanoid.Sit = true
		end
		if string.sub(msg, 1, 10) == (prefix.."bringobj ") then
			local function bringobjw()
				for i,obj in ipairs(game:GetService("Workspace"):GetDescendants()) do
					if obj.Name == (string.sub(msg, 11)) then
						obj.CFrame = lplayer.Character.HumanoidRootPart.CFrame
						obj.CanCollide = false
						obj.Transparency = 0.7
						wait()
						obj.CFrame = lplayer.Character["Left Leg"].CFrame
						wait()
						obj.CFrame = lplayer.Character["Right Leg"].CFrame
						wait()
						obj.CFrame = lplayer.Character["Head"].CFrame
					end
				end
			end
			while wait() do
				bringobjw()
			end
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "BringObj";
				Text = "BringObj enabled.";
			})
		end
		if string.sub(msg, 1, 7) == (prefix.."wsvis ") then
			vis = (string.sub(msg, 8))
			local a = game:GetService("Workspace"):GetDescendants()
			for i = 1, #a do
				if a[i].className == "Part" then
					a[i].Transparency = vis
				elseif a[i].className == "Model" then
					local r = a[i]:getChildren()
					for i = 1, #r do
						if r[i].className == "Part" then
							r[i].Transparency = vis
						end
					end
				end
			end
		end
		if string.sub(msg, 1, 11) == (prefix.."hypertotal") then
			loadstring(game:GetObjects("rbxassetid://1255063809")[1].Source)()
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Success!";
				Text = "HyperTotal GUI Loaded!";
			})
		end
		if string.sub(msg, 1, 5) == (prefix.."cmds") then
			CMDSFRAME.Visible = true
		end
		if string.sub(msg, 1, 10) == (prefix.."rmeshhats") then
			for i,v in pairs(lplayer.Character:GetChildren()) do
				if (v:IsA("Accessory")) or (v:IsA("Hat")) then
					v.Handle.Mesh:Destroy()
				end
			end
		end
		if string.sub(msg, 1, 10) == (prefix.."blockhats") then
			for i,v in pairs(lplayer.Character:GetChildren()) do
				if (v:IsA("Accessory")) or (v:IsA("Hat")) then
					v.Handle.Mesh:Destroy()
				end
			end
		end
		if string.sub(msg, 1, 10) == (prefix.."rmeshtool") then
			for i,v in pairs(lplayer.Character:GetChildren()) do
				if (v:IsA("Tool")) then
					v.Handle.Mesh:Destroy()
				end
			end
		end
		if string.sub(msg, 1, 10) == (prefix.."blocktool") then
			for i,v in pairs(lplayer.Character:GetChildren()) do
				if (v:IsA("Tool")) then
					v.Handle.Mesh:Destroy()
				end
			end
		end
		if string.sub(msg, 1, 8) == (prefix.."spinner") then
			local p = Instance.new("RocketPropulsion")
			p.Parent = lplayer.Character.HumanoidRootPart
			p.Name = "Spinner"
			p.Target = lplayer.Character["Left Arm"]
			p:Fire()
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Spinner enabled";
				Text = "Type ;nospinner to disable.";
			})
		end
		if string.sub(msg, 1, 10) == (prefix.."nospinner") then
			lplayer.Character.HumanoidRootPart.Spinner:Destroy()
		end
		if string.sub(msg, 1, 7) == (prefix.."reachd") then
			for i,v in pairs(game:GetService'Players'.LocalPlayer.Character:GetChildren())do
				if v:isA("Tool") then
					local a = Instance.new("SelectionBox",v.Handle)
					a.Adornee = v.Handle
					v.Handle.Size = Vector3.new(0.5,0.5,60)
					v.GripPos = Vector3.new(0,0,0)
					lplayer.Character.Humanoid:UnequipTools()
				end
			end
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Reach applied!";
				Text = "Applied to equipped sword. Use ;noreach to disable.";
			})
		end
		if string.sub(msg, 1, 7) == (prefix.."reach ") then
			for i,v in pairs(game:GetService'Players'.LocalPlayer.Character:GetChildren())do
				if v:isA("Tool") then
					handleSize = v.Handle.Size
					wait()
					local a = Instance.new("SelectionBox",v.Handle)
					a.Name = "a"
					a.Adornee = v.Handle
					v.Handle.Size = Vector3.new(0.5,0.5,(string.sub(msg, 8)))
					v.GripPos = Vector3.new(0,0,0)
					lplayer.Character.Humanoid:UnequipTools()
				end
			end
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Reach applied!";
				Text = "Applied to equipped sword. Use ;noreach to disable.";
			})
		end
		if string.sub(msg, 1, 8) == (prefix.."noreach") then
			for i,v in pairs(game:GetService'Players'.LocalPlayer.Character:GetChildren())do
				if v:isA("Tool") then
					v.Handle.a:Destroy()
					v.Handle.Size = handleSize
				end
			end
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Reach removed!";
				Text = "Removed reach from equipped sword.";
			})
		end
		if string.sub(msg, 1, 7) == (prefix.."rkill ") then
			for i,v in pairs(GetPlayer(string.sub(msg, 8)))do
				lplayer.Character.Humanoid.Name = 1
				local l = lplayer.Character["1"]:Clone()
				l.Parent = lplayer.Character
				l.Name = "Humanoid"
				wait(0.1)
				lplayer.Character["1"]:Destroy()
				game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character
				lplayer.Character.Animate.Disabled = true
				wait(0.1)
				lplayer.Character.Animate.Disabled = false
				lplayer.Character.Humanoid.DisplayDistanceType = "None"
				for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
					lplayer.Character.Humanoid:EquipTool(v)
				end
				wait(0.1)
				lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
				wait(0.2)
				lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
				wait(0.5)
				lplayer.Character.HumanoidRootPart.CFrame = CFrame.new(Vector3.new(-100000,10,-100000))
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Tools needed!";
					Text = "You need a tool in your backpack for this command!";
				})
			end
		end
		if string.sub(msg, 1, 7) == (prefix.."tp me ") then
			for i,v in pairs(GetPlayer(string.sub(msg, 8))) do
				lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
			end
		end
		if string.sub(msg, 1, 8) == (prefix.."cbring ") then
			if (string.sub(msg, 9)) == "all" or (string.sub(msg, 9)) == "All" or (string.sub(msg, 9)) == "ALL" then
				cbringall = true
			else
				for i,v in pairs(GetPlayer(string.sub(msg, 9))) do
					brplr = v.Name
				end
			end
			cbring = true
		end
		if string.sub(msg, 1, 9) == (prefix.."uncbring") then
			cbring = false
			cbringall = false
		end
		if string.sub(msg, 1, 6) == (prefix.."swap ") then
			for i,v in pairs(GetPlayer(string.sub(msg, 7))) do
				local NOWPLR = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
				local NOW = lplayer.Character.HumanoidRootPart.CFrame
				lplayer.Character.Humanoid.Name = 1
				local l = lplayer.Character["1"]:Clone()
				l.Parent = lplayer.Character
				l.Name = "Humanoid"
				wait(0.1)
				lplayer.Character["1"]:Destroy()
				game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character
				lplayer.Character.Animate.Disabled = true
				wait(0.1)
				lplayer.Character.Animate.Disabled = false
				lplayer.Character.Humanoid.DisplayDistanceType = "None"
				for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
					lplayer.Character.Humanoid:EquipTool(v)
				end
				local function tp(player,player2)
					local char1,char2=player.Character,player2.Character
					if char1 and char2 then
						char1:MoveTo(char2.Head.Position)
					end
				end
				wait(0.1)
				lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
				wait(0.2)
				lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
				wait(0.5)
				lplayer.Character.HumanoidRootPart.CFrame = NOW
				wait(0.6)
				tp(lplayer, game:GetService("Players")[v.Name])
				wait(0.4)
				lplayer.Character.HumanoidRootPart.CFrame = NOWPLR
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Tools needed!";
					Text = "You need a tool in your backpack for this command!";
				})
			end
		end
		if string.sub(msg, 1, 8) == (prefix.."glitch ") then
			for i,v in pairs(GetPlayer(string.sub(msg, 9))) do
				lplayer.Character.Humanoid.Name = 1
				local l = lplayer.Character["1"]:Clone()
				l.Parent = lplayer.Character
				l.Name = "Humanoid"
				wait(0.1)
				lplayer.Character["1"]:Destroy()
				game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character
				lplayer.Character.Animate.Disabled = true
				wait(0.1)
				lplayer.Character.Animate.Disabled = false
				lplayer.Character.Humanoid.DisplayDistanceType = "None"
				for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
					lplayer.Character.Humanoid:EquipTool(v)
				end
				lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character["Left Arm"].CFrame
				wait(0.3)
				lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character["Left Arm"].CFrame
				wait(0.4)
				b = Instance.new("BodyForce")
				b.Parent = lplayer.Character.HumanoidRootPart
				b.Name = "Glitch"
				b.Force = Vector3.new(100000000,5000,0)
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Tools needed!";
					Text = "You need a tool in your backpack for this command!";
				})
			end
		end
		if string.sub(msg, 1, 9) == (prefix.."unglitch") then
			lplayer.Character.HumanoidRootPart.Glitch:Destroy()
			lplayer.Character.HumanoidRootPart.CFrame = CFrame.new(10000,0,10000)
			b = Instance.new("BodyForce")
			b.Parent = lplayer.Character.HumanoidRootPart
			b.Name = "unGlitch"
			b.Force = Vector3.new(0,-5000000,0)
			wait(2)
			lplayer.Character.HumanoidRootPart.unGlitch:Destroy()
		end
		if string.sub(msg, 1, 9) == (prefix.."grespawn") then
			lplayer.Character.Humanoid.Health = 0
			wait(1)
			lplayer.Character.Head.CFrame = CFrame.new(1000000,0,1000000)
			lplayer.Character.Torso.CFrame = CFrame.new(1000000,0,1000000)
		end
		if string.sub(msg, 1, 9) == (prefix.."explorer") then
			loadstring(game:GetObjects("rbxassetid://492005721")[1].Source)()
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Success!";
				Text = "DEX Explorer has loaded.";
			})
		end
		if string.sub(msg, 1, 6) == (prefix.."anim ") then
			local Anim = Instance.new("Animation")
			Anim.AnimationId = "rbxassetid://"..(string.sub(msg, 7))
			local track = lplayer.Character.Humanoid:LoadAnimation(Anim)
			track:Play(.1, 1, 1)
		end
		if string.sub(msg, 1, 8) == (prefix.."animgui") then
			loadstring(game:GetObjects("rbxassetid://1202558084")[1].Source)()
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Success!";
				Text = "Energize Animations GUI has loaded.";
			})
		end
		if string.sub(msg, 1, 8) == (prefix.."savepos") then
			saved = lplayer.Character.HumanoidRootPart.CFrame
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Position Saved";
				Text = "Use ;loadpos to return to saved position.";
			})
		end
		if string.sub(msg, 1, 8) == (prefix.."loadpos") then
			lplayer.Character.HumanoidRootPart.CFrame = saved
		end
		if string.sub(msg, 1, 6) == (prefix.."bang ") then
			for i,v in pairs(GetPlayer(string.sub(msg, 7))) do
				local Anim2 = Instance.new("Animation")
				Anim2.AnimationId = "rbxassetid://148840371"
				local track2 = lplayer.Character.Humanoid:LoadAnimation(Anim2)
				track2:Play(.1, 1, 1)
				bplrr = v.Name
				banpl = true
			end
		end
		if string.sub(msg, 1, 7) == (prefix.."unbang") then
			banpl = false
		end
		if string.sub(msg, 1, 10) == (prefix.."bringmod ") then
			local function bringmodw()
				for i,obj in ipairs(game:GetService("Workspace"):GetDescendants()) do
					if obj.Name == (string.sub(msg, 11)) then
						for i,ch in pairs(obj:GetDescendants()) do
							if (ch:IsA("BasePart")) then
								ch.CFrame = lplayer.Character.HumanoidRootPart.CFrame
								ch.CanCollide = false
								ch.Transparency = 0.7
								wait()
								ch.CFrame = lplayer.Character["Left Leg"].CFrame
								wait()
								ch.CFrame = lplayer.Character["Right Leg"].CFrame
								wait()
								ch.CFrame = lplayer.Character["Head"].CFrame
							end
						end
					end
				end
			end
			while wait() do
				bringmodw()
			end
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "BringMod";
				Text = "BringMod enabled.";
			})
		end
		if string.sub(msg, 1, 8) == (prefix.."respawn") then
			local mod = Instance.new('Model', workspace) mod.Name = 're '..lplayer.Name
			local hum = Instance.new('Humanoid', mod)
			local ins = Instance.new('Part', mod) ins.Name = 'Torso' ins.CanCollide = false ins.Transparency = 1
			lplayer.Character = mod
		end
		if string.sub(msg, 1, 9) == (prefix.."shutdown") then
			game:GetService'RunService'.Stepped:Connect(function()
				pcall(function()
					for i,v in pairs(game:GetService'Players':GetPlayers()) do
						if v.Character ~= nil and v.Character:FindFirstChild'Head' then
							for _,x in pairs(v.Character.Head:GetChildren()) do
								if x:IsA'Sound' then x.Playing = true x.CharacterSoundEvent:FireServer(true, true) end
							end
						end
					end
				end)
			end)
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Attempting Shutdown";
				Text = "Shutdown Attempt has begun.";
			})
		end
		if string.sub(msg, 1, 8) == (prefix.."delobj ") then
			objtodel = (string.sub(msg, 9))
			for i,v in pairs(game:GetService("Workspace"):GetDescendants()) do
				if v.Name == objtodel then
					v:Destroy()
				end
			end
		end
		if string.sub(msg, 1, 8) == (prefix.."getplrs") then
			for i,v in pairs(game:GetService("Players"):GetPlayers())do
				print(v)
			end
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Printed";
				Text = "Players have been printed to console. (F9)";
			})
		end
		if string.sub(msg, 1, 9) == (prefix.."deldecal") then
			for i,v in pairs(game:GetService("Workspace"):GetDescendants())do
				if (v:IsA("Decal")) then
					v:Destroy()
				end
			end
		end
		if string.sub(msg, 1, 11) == (prefix.."opfinality") then
			loadstring(game:GetObjects("rbxassetid://1294358929")[1].Source)()
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Success!";
				Text = "OpFinality GUI has loaded.";
			})
		end
		if string.sub(msg, 1, 8) == (prefix.."remotes") then
			remotes = true
			added = true
			game.DescendantAdded:connect(function(rmt)
				if added == true then
					if remotes == true then 
						if rmt:IsA("RemoteEvent") then
							print("A RemoteEvent was added!")
							print(" game." .. rmt:GetFullName() .. " | RemoteEvent")
							print(" game." .. rmt:GetFullName() .. " | RemoteEvent", 247, 0, 0, true)
						end end end
			end)
			game.DescendantAdded:connect(function(rmtfnctn)
				if added == true then
					if remotes == true then 
						if rmtfnctn:IsA("RemoteFunction") then
							warn("A RemoteFunction was added!")
							warn(" game." .. rmtfnctn:GetFullName() .. " | RemoteFunction")
							print(" game." .. rmtfnctn:GetFullName() .. " | RemoteFunction", 5, 102, 198, true)
						end end end
			end)

			game.DescendantAdded:connect(function(bndfnctn)
				if added == true then
					if binds == true then 
						if bndfnctn:IsA("BindableFunction") then
							print("A BindableFunction was added!")
							print(" game." .. bndfnctn:GetFullName() .. " | BindableFunction")
							print(" game." .. bndfnctn:GetFullName() .. " | BindableFunction", 239, 247, 4, true)
						end end end
			end)

			game.DescendantAdded:connect(function(bnd)
				if added == true then
					if binds == true then 
						if bnd:IsA("BindableEvent") then
							warn("A BindableEvent was added!")
							warn(" game." .. bnd:GetFullName() .. " | BindableEvent")
							print(" game." .. bnd:GetFullName() .. " | BindableEvent", 13, 193, 22, true)
						end end end
			end)


			if binds == true then
				for i,v in pairs(game:GetDescendants()) do
					if v:IsA("BindableFunction") then
						print(" game." .. v:GetFullName() .. " | BindableFunction")
						print(" game." .. v:GetFullName() .. " | BindableFunction", 239, 247, 4, true)
					end end
				for i,v in pairs(game:GetDescendants()) do
					if v:IsA("BindableEvent") then
						warn(" game." .. v:GetFullName() .. " | BindableEvent")
						print(" game." .. v:GetFullName() .. " | BindableEvent", 13, 193, 22, true)
					end end
			else
				print("Off")
			end
			if remotes == true then
				for i,v in pairs(game:GetDescendants()) do
					if v:IsA("RemoteFunction") then
						warn(" game." .. v:GetFullName() .. " | RemoteFunction")
						print(" game." .. v:GetFullName() .. " | RemoteFunction", 5, 102, 198, true)
					end end
				wait()
				for i,v in pairs(game:GetDescendants()) do
					if v:IsA("RemoteEvent") then
						print(" game." .. v:GetFullName() .. " | RemoteEvent")
						print(" game." .. v:GetFullName() .. " | RemoteEvent", 247, 0, 0, true)
					end end
			else
				print("Off")
			end
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Printing Remotes";
				Text = "Type ;noremotes to disable.";
			})
		end
		if string.sub(msg, 1, 10) == (prefix.."noremotes") then
			remotes = false
			added = false
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Printing Remotes Disabled";
				Text = "Type ;remotes to enable.";
			})
		end
		if string.sub(msg, 1, 10) == (prefix.."tpdefault") then
			spin = false
			followed = false
			traill = false
			noclip = false
			annoying = false
			hwalk = false
			cbringing = false
		end
		if string.sub(msg, 1, 8) == (prefix.."stopsit") then
			stopsitting = true
		end
		if string.sub(msg, 1, 6) == (prefix.."gosit") then
			stopsitting = false
		end
		if string.sub(msg, 1, 8) == (prefix.."version") then
			print(adminversion)
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Version";
				Text = adminversion;
			})
		end
		if string.sub(msg, 1, 8) == (prefix.."clicktp") then
			clickgoto = true
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Click TP";
				Text = "Press E to teleport to mouse position, ;noclicktp to stop";
			})
		end
		if string.sub(msg, 1, 9) == (prefix.."clickdel") then
			clickdel = true
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Click Delete";
				Text = "Press E to delete part at mouse, ;noclickdel to stop";
			})
		end
		if string.sub(msg, 1, 11) == (prefix.."noclickdel") then
			clickdel = false
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Click Delete";
				Text = "Click delete has been disabled.";
			})
		end
		if string.sub(msg, 1, 10) == (prefix.."noclicktp") then
			clickgoto = false
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Click TP";
				Text = "Click TP has been disabled.";
			})
		end
		if string.sub(msg, 1, 8) == (prefix.."toolson") then
			gettingtools = true
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Tools Enabled";
				Text = "Automatically colleting tools dropped.";
			})
		end
		if string.sub(msg, 1, 9) == (prefix.."toolsoff") then
			gettingtools = false
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Tools Disabled";
				Text = "Click TP has been disabled.";
			})
		end
		if string.sub(msg, 1, 10) == (prefix.."delcmdbar") then
			ScreenGui:Destroy()
		end
		if string.sub(msg, 1, 6) == (prefix.."reset") then
			lplayer.Character.Head:Destroy()
		end
		if string.sub(msg, 1, 7) == (prefix.."state ") then
			statechosen = string.sub(msg, 8)
			changingstate = true
		end
		if string.sub(msg, 1, 9) == (prefix.."gravity ") then
			game:GetService("Workspace").Gravity = string.sub(msg, 10)
		end
		if string.sub(msg, 1, 10) == (prefix.."looprhats") then
			removingmeshhats = true
		end
		if string.sub(msg, 1, 12) == (prefix.."unlooprhats") then
			removingmeshhats = false
		end
		if string.sub(msg, 1, 10) == (prefix.."looprtool") then
			removingmeshtool = true
		end
		if string.sub(msg, 1, 12) == (prefix.."unlooprtool") then
			removingmeshtool = false
		end
		if string.sub(msg, 1, 10) == (prefix.."givetool ") then
			for i,v in pairs(game:GetService("Players").LocalPlayer.Character:GetDescendants()) do
				if v:IsA("Tool") then
					for i,player in pairs(GetPlayer(string.sub(msg, 11))) do
						v.Parent = player.Character
					end
				end
			end
		end
		if string.sub(msg, 1, 14) == (prefix.."givealltools ") then
			for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetDescendants()) do
				if v:IsA("Tool") then
					v.Parent = lplayer.Character
					wait()
					for i,player in pairs(GetPlayer(string.sub(msg, 15))) do
						v.Parent = player.Character
					end
				end
			end
		end
		if string.sub(msg, 1, 5) == (prefix.."age ") then
			for i,player in pairs(GetPlayer(string.sub(msg, 6))) do
				game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(player.Name.." Account Age: "..player.AccountAge.." days!", "All")
			end
		end
		if string.sub(msg, 1, 4) == (prefix.."id ") then
			for i,player in pairs(GetPlayer(string.sub(msg, 5))) do
				game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(player.Name.." Account ID: "..player.UserId, "All")
			end
		end
		if string.sub(msg, 1, 6) == (prefix..".age ") then
			for i,player in pairs(GetPlayer(string.sub(msg, 7))) do
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = player.AccountAge.." Days";
					Text = "Account age of "..player.Name;
				})
			end
		end
		if string.sub(msg, 1, 5) == (prefix..".id ") then
			for i,player in pairs(GetPlayer(string.sub(msg, 6))) do
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = player.UserId.." ID";
					Text = "Account ID of "..player.Name;
				})
			end
		end
		if string.sub(msg, 1, 7) == (prefix.."gameid") then
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Game ID";
				Text = "Game ID: ".. game.GameId;
			})
		end
		if string.sub(msg, 1, 4) == (prefix.."pgs") then
			local pgscheck = game:GetService("Workspace"):PGSIsEnabled()
			if pgscheck == true then
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "PGSPhysicsSolverEnabled";
					Text = "PGS is Enabled!";
				})
			else
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "PGSPhysicsSolverEnabled";
					Text = "PGS is Disabled!";
				})
			end
		end
		if string.sub(msg, 1, 12) == (prefix.."removeinvis") then
			for i,v in pairs(game:GetService("Workspace"):GetDescendants()) do
				if v:IsA("Part") then
					if v.Transparency == 1 then
						if v.Name ~= "HumanoidRootPart" then
							v:Destroy()
						end
					end
				end
			end
		end
		if string.sub(msg, 1, 10) == (prefix.."removefog") then
			game:GetService("Lighting").FogStart = 0
			game:GetService("Lighting").FogEnd = 9999999999999
		end
		if string.sub(msg, 1, 8) == (prefix.."disable") then
			lplayer.Character.Humanoid.Parent = lplayer
		end
		if string.sub(msg, 1, 7) == (prefix.."enable") then
			lplayer.Humanoid.Parent = lplayer.Character
		end
		if string.sub(msg, 1, 8) == (prefix.."prefix ") then
			prefix = (string.sub(msg, 9, 9))
			wait(0.1)
			change()
			wait(0.1)
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Prefix changed!";
				Text = "Prefix is now "..prefix..". Use ;resetprefix to reset to ;";
			})
		end
		if string.sub(msg, 1, 12) == (";resetprefix") then
			prefix = ";"
			wait(0.1)
			change()
			wait(0.1)
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "Prefix changed!";
				Text = "Prefix is now "..prefix..". Make sure it's one key!";
			})
		end
		if string.sub(msg, 1, 10) == (prefix.."flyspeed ") then
			speedfly = string.sub(msg, 11)
			wait()
			change()
		end
		if string.sub(msg, 1, 8) == (prefix.."carpet ") then
			for i,v in pairs(GetPlayer(string.sub(msg, 9))) do
				local Anim3 = Instance.new("Animation")
				Anim3.AnimationId = "rbxassetid://282574440"
				local track3 = lplayer.Character.Humanoid:LoadAnimation(Anim3)
				track3:Play(.1, 1, 1)
				bplrr = v.Name
				banpl = true
			end
		end
		if string.sub(msg, 1, 9) == (prefix.."uncarpet") then
			banpl = false
		end
		if string.sub(msg, 1, 7) == (prefix.."stare ") then
			for i,v in pairs(GetPlayer(string.sub(msg, 8))) do
				staring = true
				stareplr = v
			end
		end
		if string.sub(msg, 1, 8) == (prefix.."unstare") then
			staring = false
		end
		if string.sub(msg, 1, 8) == (prefix.."logchat") then
			chatlogs = true
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "LogChat enabled";
				Text = "Now logging all player chat.";
			})
		end
		if string.sub(msg, 1, 10) == (prefix.."unlogchat") then
			chatlogs = false
			game:GetService("StarterGui"):SetCore("SendNotification", {
				Title = "LogChat disabled";
				Text = "Stopped logging all player chat.";
			})
		end
		if string.sub(msg, 1, 7) == (prefix.."fixcam") then
			game:GetService("Workspace").CurrentCamera:Destroy()
			wait(0.1)
			game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character.Humanoid
			game:GetService("Workspace").CurrentCamera.CameraType = "Custom"
			lplayer.CameraMinZoomDistance = 0.5
			lplayer.CameraMaxZoomDistance = 400
			lplayer.CameraMode = "Classic"
		end
		if string.sub(msg, 1, 8) == (prefix.."unstate") then
			changingstate = false
		end
	end)

	local function tp()
		for i, player in ipairs(game:GetService("Players"):GetPlayers()) do
			if player.Character and player.Character:FindFirstChild("HumanoidRootPart") then
				if player.Name == brplr then
					player.Character.HumanoidRootPart.CFrame = lplayer.Character.HumanoidRootPart.CFrame + lplayer.Character.HumanoidRootPart.CFrame.lookVector * 2
				end
			end
		end
	end
	local function tpall()
		for i, player in ipairs(game:GetService("Players"):GetPlayers()) do
			if player.Character and player.Character:FindFirstChild("HumanoidRootPart") then
				player.Character.HumanoidRootPart.CFrame = lplayer.Character.HumanoidRootPart.CFrame + lplayer.Character.HumanoidRootPart.CFrame.lookVector * 3
			end
		end
	end
	spawn(function()
		while wait(spamdelay) do
			if spamming == true then
				game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(spamtext, "All")
			end
		end
	end)
	spawn(function()
		while wait(spamdelay) do
			if spammingpm == true then
				game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer("/w "..pmspammed.." @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@", "All")
			end
		end
	end)
	spawn(function()
		while wait() do
			if cbring == true then
				tp()
			end
		end
	end)
	spawn(function()
		while wait() do
			if cbringall == true then
				tpall()
			end
		end
	end)

	Mouse.KeyDown:connect(function(Key)
		if Key == prefix then
			CMDBAR:CaptureFocus()
		end
	end)

	CMDBAR.FocusLost:connect(function(enterPressed)
		if enterPressed then
			if string.sub(CMDBAR.Text, 1, 5) == ("kill ") then
				if string.sub(CMDBAR.Text, 6) == "me" then
					lplayer.Character.HumanoidRootPart.CFrame = CFrame.new(100000,0,100000)
				else
					for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 6)))do
						local NOW = lplayer.Character.HumanoidRootPart.CFrame
						lplayer.Character.Humanoid.Name = 1
						local l = lplayer.Character["1"]:Clone()
						l.Parent = lplayer.Character
						l.Name = "Humanoid"
						wait(0.1)
						lplayer.Character["1"]:Destroy()
						game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character
						lplayer.Character.Animate.Disabled = true
						wait(0.1)
						lplayer.Character.Animate.Disabled = false
						lplayer.Character.Humanoid.DisplayDistanceType = "None"
						for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
							lplayer.Character.Humanoid:EquipTool(v)
						end
						local function tp(player,player2)
							local char1,char2=player.Character,player2.Character
							if char1 and char2 then
								char1:MoveTo(char2.Head.Position)
							end
						end
						wait(0.1)
						lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
						wait(0.2)
						lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
						wait(0.5)
						lplayer.Character.HumanoidRootPart.CFrame = CFrame.new(Vector3.new(-100000,10,-100000))
						wait(0.7)
						tp(lplayer,game:GetService("Players")[v.Name])
						wait(0.7)
						lplayer.Character.HumanoidRootPart.CFrame = NOW
						game:GetService("StarterGui"):SetCore("SendNotification", {
							Title = "Tools needed!";
							Text = "You need a tool in your backpack for this command!";
						})
					end
				end
			end
			if string.sub(CMDBAR.Text, 1, 6) == ("bring ") then
				for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 7)))do
					local NOW = lplayer.Character.HumanoidRootPart.CFrame
					lplayer.Character.Humanoid.Name = 1
					local l = lplayer.Character["1"]:Clone()
					l.Parent = lplayer.Character
					l.Name = "Humanoid"
					wait(0.1)
					lplayer.Character["1"]:Destroy()
					game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character
					lplayer.Character.Animate.Disabled = true
					wait(0.1)
					lplayer.Character.Animate.Disabled = false
					lplayer.Character.Humanoid.DisplayDistanceType = "None"
					for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
						lplayer.Character.Humanoid:EquipTool(v)
					end
					local function tp(player,player2)
						local char1,char2=player.Character,player2.Character
						if char1 and char2 then
							char1.HumanoidRootPart.CFrame = char2.HumanoidRootPart.CFrame
						end
					end
					local function getout(player,player2)
						local char1,char2=player.Character,player2.Character
						if char1 and char2 then
							char1:MoveTo(char2.Head.Position)
						end
					end
					tp(game:GetService("Players")[v.Name], lplayer)
					wait(0.2)
					tp(game:GetService("Players")[v.Name], lplayer)
					wait(0.5)
					lplayer.Character.HumanoidRootPart.CFrame = NOW
					wait(0.5)
					getout(lplayer, game:GetService("Players")[v.Name])
					wait(0.3)
					lplayer.Character.HumanoidRootPart.CFrame = NOW
					game:GetService("StarterGui"):SetCore("SendNotification", {
						Title = "Tools needed!";
						Text = "You need a tool in your backpack for this command!";
					})
				end
			end
			if string.sub(CMDBAR.Text, 1, 5) == ("spin ") then
				for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 6))) do
					lplayer.Character.Humanoid.Name = 1
					local l = lplayer.Character["1"]:Clone()
					l.Parent = lplayer.Character
					l.Name = "Humanoid"
					wait(0.1)
					lplayer.Character["1"]:Destroy()
					game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character
					lplayer.Character.Animate.Disabled = true
					wait(0.1)
					lplayer.Character.Animate.Disabled = false
					lplayer.Character.Humanoid.DisplayDistanceType = "None"
					for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
						lplayer.Character.Humanoid:EquipTool(v)
					end
					lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character["Left Arm"].CFrame
					spinplr = v
					wait(0.5)
					spin = true
					game:GetService("StarterGui"):SetCore("SendNotification", {
						Title = "Tools needed!";
						Text = "You need a tool in your backpack for this command!";
					})
				end
			end
			if string.sub(CMDBAR.Text, 1, 6) == ("unspin") then
				spin = false
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("attach ") then
				for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 8))) do
					lplayer.Character.Humanoid.Name = 1
					local l = lplayer.Character["1"]:Clone()
					l.Parent = lplayer.Character
					l.Name = "Humanoid"
					wait(0.1)
					lplayer.Character["1"]:Destroy()
					game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character
					lplayer.Character.Animate.Disabled = true
					wait(0.1)
					lplayer.Character.Animate.Disabled = false
					lplayer.Character.Humanoid.DisplayDistanceType = "None"
					for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
						lplayer.Character.Humanoid:EquipTool(v)
					end
					lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character["Left Arm"].CFrame
					wait(0.3)
					lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character["Left Arm"].CFrame
					attplr = v
					game:GetService("StarterGui"):SetCore("SendNotification", {
						Title = "Tools needed!";
						Text = "You need a tool in your backpack for this command!";
					})
				end
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("unattach ") then
				for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 10))) do
					local function getout(player,player2)
						local char1,char2=player.Character,player2.Character
						if char1 and char2 then
							char1:MoveTo(char2.Head.Position)
						end
					end
					getout(lplayer, game:GetService("Players")[v.Name])
				end
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("follow ") then
				for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 8))) do
					followed = true
					flwplr = v
				end
			end
			if string.sub(CMDBAR.Text, 1, 8) == ("unfollow") then
				followed = false
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("freefall ") then
				for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 10))) do
					local NOW = lplayer.Character.HumanoidRootPart.CFrame
					lplayer.Character.Humanoid.Name = 1
					local l = lplayer.Character["1"]:Clone()
					l.Parent = lplayer.Character
					l.Name = "Humanoid"
					wait(0.1)
					lplayer.Character["1"]:Destroy()
					game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character
					lplayer.Character.Animate.Disabled = true
					wait(0.1)
					lplayer.Character.Animate.Disabled = false
					lplayer.Character.Humanoid.DisplayDistanceType = "None"
					for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
						lplayer.Character.Humanoid:EquipTool(v)
					end
					lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
					wait(0.2)
					lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
					wait(0.6)
					lplayer.Character.HumanoidRootPart.CFrame = NOW
					wait(0.6)
					lplayer.Character.HumanoidRootPart.CFrame = CFrame.new(0,50000,0)
					game:GetService("StarterGui"):SetCore("SendNotification", {
						Title = "Tools needed!";
						Text = "You need a tool in your backpack for this command!";
					})
				end
			end
			if string.sub(CMDBAR.Text, 1, 6) == ("trail ") then
				for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 7))) do
					traill = true
					trlplr = v
				end
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("untrail") then
				traill = false
			end
			if string.sub(CMDBAR.Text, 1, 6) == ("orbit ") then
				if string.sub(CMDBAR.Text, 7) == "all" or string.sub(CMDBAR.Text, 7) == "others" or string.sub(CMDBAR.Text, 7) == "me" then
					lplayer.Character.HumanoidRootPart.CFrame = lplayer.Character.HumanoidRootPart.CFrame
				else
					for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 7))) do
						local o = Instance.new("RocketPropulsion")
						o.Parent = lplayer.Character.HumanoidRootPart
						o.Name = "Orbit"
						o.Target = game:GetService("Players")[v.Name].Character.HumanoidRootPart
						o:Fire()
						noclip = true
					end
				end
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("unorbit") then
				lplayer.Character.HumanoidRootPart.Orbit:Destroy()
				noclip = false
			end
			if string.sub(CMDBAR.Text, 1, 6) == ("fling ") then
				if string.sub(CMDBAR.Text, 7) == "all" or string.sub(CMDBAR.Text, 7) == "others" or string.sub(CMDBAR.Text, 7) == "me" then
					lplayer.Character.HumanoidRootPart.CFrame = lplayer.Character.HumanoidRootPart.CFrame
				else
					for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 7))) do
						local y = Instance.new("RocketPropulsion")
						y.Parent = lplayer.Character.HumanoidRootPart
						y.CartoonFactor = 1
						y.MaxThrust = 800000
						y.MaxSpeed = 1000
						y.ThrustP = 200000
						y.Name = "Fling"
						game:GetService("Workspace").CurrentCamera.CameraSubject = game:GetService("Players")[v.Name].Character.Head
						y.Target = game:GetService("Players")[v.Name].Character.HumanoidRootPart
						y:Fire()
						noclip = true
					end
				end
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("unfling") then
				noclip = false
				lplayer.Character.HumanoidRootPart.Fling:Destroy()
				game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character.Head
				wait(0.4)
				lplayer.Character.HumanoidRootPart.Fling:Destroy()
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("fecheck") then
				if game:GetService("Workspace").FilteringEnabled == true then
					warn("FE is Enabled (Filtering Enabled)")
					game:GetService("StarterGui"):SetCore("SendNotification", {
						Title = "FE is Enabled";
						Text = "Filtering Enabled. Enjoy using Reviz Admin!";
					})
				else
					warn("FE is Disabled (Filtering Disabled) Consider using a different admin script.")
					game:GetService("StarterGui"):SetCore("SendNotification", {
						Title = "FE is Disabled";
						Text = "Filtering Disabled. Consider using a different admin script.";
					})
				end
			end
			if string.sub(CMDBAR.Text, 1, 5) == ("void ") then
				for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 6))) do
					lplayer.Character.Humanoid.Name = 1
					local l = lplayer.Character["1"]:Clone()
					l.Parent = lplayer.Character
					l.Name = "Humanoid"
					wait(0.1)
					lplayer.Character["1"]:Destroy()
					game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character
					lplayer.Character.Animate.Disabled = true
					wait(0.1)
					lplayer.Character.Animate.Disabled = false
					lplayer.Character.Humanoid.DisplayDistanceType = "None"
					for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
						lplayer.Character.Humanoid:EquipTool(v)
					end
					lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
					wait(0.2)
					lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
					wait(0.6)
					lplayer.Character.HumanoidRootPart.CFrame = CFrame.new(999999999999999,0,999999999999999)
					game:GetService("StarterGui"):SetCore("SendNotification", {
						Title = "Tools needed!";
						Text = "You need a tool in your backpack for this command!";
					})
				end
			end
			if string.sub(CMDBAR.Text, 1, 6) == ("noclip") then
				noclip = true
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Noclip enabled";
					Text = "Type ;clip to disable";
				})
			end
			if string.sub(CMDBAR.Text, 1, 4) == ("clip") then
				noclip = false
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Noclip disabled";
					Text = "Type ;noclip to enable";
				})
			end
			if string.sub(CMDBAR.Text, 1, 6) == ("speed ") then
				lplayer.Character.Humanoid.WalkSpeed = (string.sub(CMDBAR.Text, 7))
			end
			if string.sub(CMDBAR.Text, 1, 3) == ("ws ") then
				lplayer.Character.Humanoid.WalkSpeed = (string.sub(CMDBAR.Text, 4))
			end
			if string.sub(CMDBAR.Text, 1, 10) == ("hipheight ") then
				lplayer.Character.Humanoid.HipHeight = (string.sub(CMDBAR.Text, 11))
			end
			if string.sub(CMDBAR.Text, 1, 3) == ("hh ") then
				lplayer.Character.Humanoid.HipHeight = (string.sub(CMDBAR.Text, 4))
			end
			if string.sub(CMDBAR.Text, 1, 10) == ("jumppower ") then
				lplayer.Character.Humanoid.JumpPower = (string.sub(CMDBAR.Text, 11))
			end
			if string.sub(CMDBAR.Text, 1, 3) == ("jp ") then
				lplayer.Character.Humanoid.JumpPower = (string.sub(CMDBAR.Text, 4))
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("default") then
				lplayer.Character.Humanoid.JumpPower = 50
				lplayer.Character.Humanoid.WalkSpeed = 16
				lplayer.Character.Humanoid.HipHeight = 0
			end
			if string.sub(CMDBAR.Text, 1, 6) == ("annoy ") then
				for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 7))) do
					annoying = true
					annplr = v
				end
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("unannoy") then
				annoying = false
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("headwalk ") then
				for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 10))) do
					hwalk = true
					hdwplr = v
				end
			end
			if string.sub(CMDBAR.Text, 1, 10) == ("unheadwalk") then
				hwalk = false
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("nolimbs") then
				lplayer.Character["Left Leg"]:Destroy()
				lplayer.Character["Left Arm"]:Destroy()
				lplayer.Character["Right Leg"]:Destroy()
				lplayer.Character["Right Arm"]:Destroy()
			end
			if string.sub(CMDBAR.Text, 1, 3) == ("god") then
				lplayer.Character.Humanoid.Name = 1
				local l = lplayer.Character["1"]:Clone()
				l.Parent = lplayer.Character
				l.Name = "Humanoid"
				wait(0.1)
				lplayer.Character["1"]:Destroy()
				game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character
				lplayer.Character.Animate.Disabled = true
				wait(0.1)
				lplayer.Character.Animate.Disabled = false
				lplayer.Character.Humanoid.DisplayDistanceType = "None"
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "FE Godmode enabled";
					Text = "Use ;grespawn or ;respawn to remove.";
				})
			end
			if string.sub(CMDBAR.Text, 1, 8) == ("drophats") then
				for i,v in pairs(lplayer.Character:GetChildren()) do
					if (v:IsA("Accessory")) or (v:IsA("Hat")) then
						v.Parent = workspace
					end
				end
			end
			if string.sub(CMDBAR.Text, 1, 8) == ("droptool") then
				for i,v in pairs(lplayer.Character:GetChildren()) do
					if (v:IsA("Tool")) then
						v.Parent = workspace
					end
				end
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("loopdhats") then
				droppinghats = true
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Loop Drop Enabled";
					Text = "Type ;unloopdhats to disable";
				})
			end
			if string.sub(CMDBAR.Text, 1, 11) == ("unloopdhats") then
				droppinghats = false
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Loop Drop Disabled";
					Text = "Type ;loopdhats to enable.";
				})
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("loopdtool") then
				droppingtools = true
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Loop Drop Enabled";
					Text = "Type ;unloopdtool to disable";
				})
			end
			if string.sub(CMDBAR.Text, 1, 11) == ("unloopdtool") then
				droppingtools = false
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Loop Drop Disabled";
					Text = "Type ;loopdtool to enable.";
				})
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("invisible") then -- Credit to Timeless
				Local = game:GetService('Players').LocalPlayer
				Char  = Local.Character
				touched,tpdback = false, false
				box = Instance.new('Part',workspace)
				box.Anchored = true
				box.CanCollide = true
				box.Size = Vector3.new(10,1,10)
				box.Position = Vector3.new(0,10000,0)
				box.Touched:connect(function(part)
					if (part.Parent.Name == Local.Name) then
						if touched == false then
							touched = true
							function apply()
								if script.Disabled ~= true then
									no = Char.HumanoidRootPart:Clone()
									wait(.25)
									Char.HumanoidRootPart:Destroy()
									no.Parent = Char
									Char:MoveTo(loc)
									touched = false
								end end
							if Char then
								apply()
							end
						end
					end
				end)
				repeat wait() until Char
				loc = Char.HumanoidRootPart.Position
				Char:MoveTo(box.Position + Vector3.new(0,.5,0))
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Invisibility enabled!";
					Text = "Reset or use ;respawn to remove.";
				})
			end
			if string.sub(CMDBAR.Text, 1, 5) == ("view ") then
				for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 6))) do
					if game:GetService("Players")[v.Name].Character.Humanoid then
						game:GetService("Workspace").CurrentCamera.CameraSubject = game:GetService("Players")[v.Name].Character.Humanoid
					else
						game:GetService("Workspace").CurrentCamera.CameraSubject = game:GetService("Players")[v.Name].Character.Head
					end
				end
			end
			if string.sub(CMDBAR.Text, 1, 6) == ("unview") then
				if lplayer.Character.Humanoid then
					game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character.Humanoid
				else
					game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character.Head
				end
			end
			if string.sub(CMDBAR.Text, 1, 5) == ("goto ") then
				for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 6))) do
					lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
				end
			end
			if string.sub(CMDBAR.Text, 1, 3) == ("fly") then
				repeat wait() until lplayer and lplayer.Character and lplayer.Character:FindFirstChild('HumanoidRootPart') and lplayer.Character:FindFirstChild('Humanoid')
				repeat wait() until Mouse

				local T = lplayer.Character.HumanoidRootPart
				local CONTROL = {F = 0, B = 0, L = 0, R = 0}
				local lCONTROL = {F = 0, B = 0, L = 0, R = 0}
				local SPEED = speedget

				local function fly()
					flying = true
					local BG = Instance.new('BodyGyro', T)
					local BV = Instance.new('BodyVelocity', T)
					BG.P = 9e4
					BG.maxTorque = Vector3.new(9e9, 9e9, 9e9)
					BG.cframe = T.CFrame
					BV.velocity = Vector3.new(0, 0.1, 0)
					BV.maxForce = Vector3.new(9e9, 9e9, 9e9)
					spawn(function()
						repeat wait()
							lplayer.Character.Humanoid.PlatformStand = true
							if CONTROL.L + CONTROL.R ~= 0 or CONTROL.F + CONTROL.B ~= 0 then
								SPEED = 50
							elseif not (CONTROL.L + CONTROL.R ~= 0 or CONTROL.F + CONTROL.B ~= 0) and SPEED ~= 0 then
								SPEED = 0
							end
							if (CONTROL.L + CONTROL.R) ~= 0 or (CONTROL.F + CONTROL.B) ~= 0 then
								BV.velocity = ((workspace.CurrentCamera.CoordinateFrame.lookVector * (CONTROL.F + CONTROL.B)) + ((workspace.CurrentCamera.CoordinateFrame * CFrame.new(CONTROL.L + CONTROL.R, (CONTROL.F + CONTROL.B) * 0.2, 0).p) - workspace.CurrentCamera.CoordinateFrame.p)) * SPEED
								lCONTROL = {F = CONTROL.F, B = CONTROL.B, L = CONTROL.L, R = CONTROL.R}
							elseif (CONTROL.L + CONTROL.R) == 0 and (CONTROL.F + CONTROL.B) == 0 and SPEED ~= 0 then
								BV.velocity = ((workspace.CurrentCamera.CoordinateFrame.lookVector * (lCONTROL.F + lCONTROL.B)) + ((workspace.CurrentCamera.CoordinateFrame * CFrame.new(lCONTROL.L + lCONTROL.R, (lCONTROL.F + lCONTROL.B) * 0.2, 0).p) - workspace.CurrentCamera.CoordinateFrame.p)) * SPEED
							else
								BV.velocity = Vector3.new(0, 0.1, 0)
							end
							BG.cframe = workspace.CurrentCamera.CoordinateFrame
						until not flying
						CONTROL = {F = 0, B = 0, L = 0, R = 0}
						lCONTROL = {F = 0, B = 0, L = 0, R = 0}
						SPEED = 0
						BG:destroy()
						BV:destroy()
						lplayer.Character.Humanoid.PlatformStand = false
					end)
				end
				Mouse.KeyDown:connect(function(KEY)
					if KEY:lower() == 'w' then
						CONTROL.F = speedfly
					elseif KEY:lower() == 's' then
						CONTROL.B = -speedfly
					elseif KEY:lower() == 'a' then
						CONTROL.L = -speedfly 
					elseif KEY:lower() == 'd' then 
						CONTROL.R = speedfly
					end
				end)
				Mouse.KeyUp:connect(function(KEY)
					if KEY:lower() == 'w' then
						CONTROL.F = 0
					elseif KEY:lower() == 's' then
						CONTROL.B = 0
					elseif KEY:lower() == 'a' then
						CONTROL.L = 0
					elseif KEY:lower() == 'd' then
						CONTROL.R = 0
					end
				end)
				fly()
			end
			if string.sub(CMDBAR.Text, 1, 5) == ("unfly") then
				flying = false
				lplayer.Character.Humanoid.PlatformStand = false
			end
			if string.sub(CMDBAR.Text, 1, 5) == ("chat ") then
				game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer((string.sub(CMDBAR.Text, 6)), "All")
			end
			if string.sub(CMDBAR.Text, 1, 5) == ("spam ") then
				spamtext = (string.sub(CMDBAR.Text, 6))
				spamming = true
			end
			if string.sub(CMDBAR.Text, 1, 6) == ("unspam") then
				spamming = false
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("spamwait ") then
				spamdelay = (string.sub(CMDBAR.Text, 10))
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("pmspam ") then
				for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 8))) do
					pmspammed = v.Name
					spammingpm = true
				end
			end
			if string.sub(CMDBAR.Text, 1, 8) == ("unpmspam") then
				spammingpm = false
			end
			if string.sub(CMDBAR.Text, 1, 8) == ("cfreeze ") then
				for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 9))) do
					v.Character["Left Leg"].Anchored = true
					v.Character["Left Arm"].Anchored = true
					v.Character["Right Leg"].Anchored = true
					v.Character["Right Arm"].Anchored = true
					v.Character.Torso.Anchored = true
					v.Character.Head.Anchored = true
				end
			end
			if string.sub(CMDBAR.Text, 1, 10) == ("uncfreeze ") then
				for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 11))) do
					v.Character["Left Leg"].Anchored = false
					v.Character["Left Arm"].Anchored = false
					v.Character["Right Leg"].Anchored = false
					v.Character["Right Arm"].Anchored = false
					v.Character.Torso.Anchored = false
					v.Character.Head.Anchored = false
				end
			end
			if string.sub(CMDBAR.Text, 1, 8) == ("unlockws") then
				local a = game:GetService("Workspace"):getChildren()
				for i = 1, #a do
					if a[i].className == "Part" then
						a[i].Locked = false
					elseif a[i].className == "Model" then
						local r = a[i]:getChildren()
						for i = 1, #r do
							if r[i].className == "Part" then
								r[i].Locked = false
							end
						end
					end
				end
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Success!";
					Text = "Workspace unlocked. Use ;lockws to lock.";
				})
			end
			if string.sub(CMDBAR.Text, 1, 6) == ("lockws") then
				local a = game:GetService("Workspace"):getChildren()
				for i = 1, #a do
					if a[i].className == "Part" then
						a[i].Locked = true
					elseif a[i].className == "Model" then
						local r = a[i]:getChildren()
						for i = 1, #r do
							if r[i].className == "Part" then
								r[i].Locked = true
							end
						end
					end
				end
			end
			if string.sub(CMDBAR.Text, 1, 6) == ("btools") then
				local Clone_T = Instance.new("HopperBin",lplayer.Backpack)
				Clone_T.BinType = "Clone"
				local Destruct = Instance.new("HopperBin",lplayer.Backpack)
				Destruct.BinType = "Hammer"
				local Hold_T = Instance.new("HopperBin",lplayer.Backpack)
				Hold_T.BinType = "Grab"
			end
			if string.sub(CMDBAR.Text, 1, 6) == ("pstand") then
				lplayer.Character.Humanoid.PlatformStand = true
			end
			if string.sub(CMDBAR.Text, 1, 8) == ("unpstand") then
				lplayer.Character.Humanoid.PlatformStand = false
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("blockhead") then
				lplayer.Character.Head.Mesh:Destroy()
			end
			if string.sub(CMDBAR.Text, 1, 3) == ("sit") then
				lplayer.Character.Humanoid.Sit = true
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("bringobj ") then
				local function bringobjw()
					for i,obj in ipairs(game:GetService("Workspace"):GetDescendants()) do
						if obj.Name == (string.sub(CMDBAR.Text, 10)) then
							obj.CFrame = lplayer.Character.HumanoidRootPart.CFrame
							obj.CanCollide = false
							obj.Transparency = 0.7
							wait()
							obj.CFrame = lplayer.Character["Left Leg"].CFrame
							wait()
							obj.CFrame = lplayer.Character["Right Leg"].CFrame
							wait()
							obj.CFrame = lplayer.Character["Head"].CFrame
						end
					end
				end
				while wait() do
					bringobjw()
				end
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "BringObj";
					Text = "BringObj enabled.";
				})
			end
			if string.sub(CMDBAR.Text, 1, 6) == ("wsvis ") then
				vis = (string.sub(CMDBAR.Text, 7))
				local a = game:GetService("Workspace"):GetDescendants()
				for i = 1, #a do
					if a[i].className == "Part" then
						a[i].Transparency = vis
					elseif a[i].className == "Model" then
						local r = a[i]:getChildren()
						for i = 1, #r do
							if r[i].className == "Part" then
								r[i].Transparency = vis
							end
						end
					end
				end
			end
			if string.sub(CMDBAR.Text, 1, 10) == ("hypertotal") then
				loadstring(game:GetObjects("rbxassetid://1255063809")[1].Source)()
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Success!";
					Text = "HyperTotal GUI Loaded!";
				})
			end
			if string.sub(CMDBAR.Text, 1, 4) == ("cmds") then
				CMDSFRAME.Visible = true
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("rmeshhats") then
				for i,v in pairs(lplayer.Character:GetChildren()) do
					if (v:IsA("Accessory")) or (v:IsA("Hat")) then
						v.Handle.Mesh:Destroy()
					end
				end
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("blockhats") then
				for i,v in pairs(lplayer.Character:GetChildren()) do
					if (v:IsA("Accessory")) or (v:IsA("Hat")) then
						v.Handle.Mesh:Destroy()
					end
				end
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("rmeshtool") then
				for i,v in pairs(lplayer.Character:GetChildren()) do
					if (v:IsA("Tool")) then
						v.Handle.Mesh:Destroy()
					end
				end
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("blocktool") then
				for i,v in pairs(lplayer.Character:GetChildren()) do
					if (v:IsA("Tool")) then
						v.Handle.Mesh:Destroy()
					end
				end
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("spinner") then
				local p = Instance.new("RocketPropulsion")
				p.Parent = lplayer.Character.HumanoidRootPart
				p.Name = "Spinner"
				p.Target = lplayer.Character["Left Arm"]
				p:Fire()
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Spinner enabled";
					Text = "Type ;nospinner to disable.";
				})
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("nospinner") then
				lplayer.Character.HumanoidRootPart.Spinner:Destroy()
			end
			if string.sub(CMDBAR.Text, 1, 6) == ("reachd") then
				for i,v in pairs(game:GetService'Players'.LocalPlayer.Character:GetChildren())do
					if v:isA("Tool") then
						local a = Instance.new("SelectionBox",v.Handle)
						a.Adornee = v.Handle
						v.Handle.Size = Vector3.new(0.5,0.5,60)
						v.GripPos = Vector3.new(0,0,0)
						lplayer.Character.Humanoid:UnequipTools()
					end
				end
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Reach applied!";
					Text = "Applied to equipped sword. Use ;noreach to disable.";
				})
			end
			if string.sub(CMDBAR.Text, 1, 6) == ("reach ") then
				for i,v in pairs(game:GetService'Players'.LocalPlayer.Character:GetChildren())do
					if v:isA("Tool") then
						local a = Instance.new("SelectionBox",v.Handle)
						a.Name = "Reach"
						a.Adornee = v.Handle
						v.Handle.Size = Vector3.new(0.5,0.5,(string.sub(CMDBAR.Text, 7)))
						v.GripPos = Vector3.new(0,0,0)
						lplayer.Character.Humanoid:UnequipTools()
					end
				end
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Reach applied!";
					Text = "Applied to equipped sword. Use ;noreach to disable.";
				})
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("noreach") then
				for i,v in pairs(game:GetService'Players'.LocalPlayer.Character:GetChildren())do
					if v:isA("Tool") then
						v.Handle.Reach:Destroy()
					end
				end
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Reach removed!";
					Text = "Removed reach from equipped sword.";
				})
			end
			if string.sub(CMDBAR.Text, 1, 6) == ("rkill ") then
				for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 7)))do
					lplayer.Character.Humanoid.Name = 1
					local l = lplayer.Character["1"]:Clone()
					l.Parent = lplayer.Character
					l.Name = "Humanoid"
					wait(0.1)
					lplayer.Character["1"]:Destroy()
					game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character
					lplayer.Character.Animate.Disabled = true
					wait(0.1)
					lplayer.Character.Animate.Disabled = false
					lplayer.Character.Humanoid.DisplayDistanceType = "None"
					for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
						lplayer.Character.Humanoid:EquipTool(v)
					end
					wait(0.1)
					lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
					wait(0.2)
					lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
					wait(0.5)
					lplayer.Character.HumanoidRootPart.CFrame = CFrame.new(Vector3.new(-100000,10,-100000))
					game:GetService("StarterGui"):SetCore("SendNotification", {
						Title = "Tools needed!";
						Text = "You need a tool in your backpack for this command!";
					})
				end
			end
			if string.sub(CMDBAR.Text, 1, 6) == ("tp me ") then
				for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 7))) do
					lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
				end
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("cbring ") then
				if (string.sub(CMDBAR.Text, 8)) == "all" or (string.sub(CMDBAR.Text, 8)) == "All" or (string.sub(CMDBAR.Text, 8)) == "ALL" then
					cbringall = true
				else
					for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 8))) do
						brplr = v.Name
					end
				end
				cbring = true
			end
			if string.sub(CMDBAR.Text, 1, 8) == ("uncbring") then
				cbring = false
				cbringall = false
			end
			if string.sub(CMDBAR.Text, 1, 5) == ("swap ") then
				for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 6))) do
					local NOWPLR = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
					local NOW = lplayer.Character.HumanoidRootPart.CFrame
					lplayer.Character.Humanoid.Name = 1
					local l = lplayer.Character["1"]:Clone()
					l.Parent = lplayer.Character
					l.Name = "Humanoid"
					wait(0.1)
					lplayer.Character["1"]:Destroy()
					game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character
					lplayer.Character.Animate.Disabled = true
					wait(0.1)
					lplayer.Character.Animate.Disabled = false
					lplayer.Character.Humanoid.DisplayDistanceType = "None"
					for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
						lplayer.Character.Humanoid:EquipTool(v)
					end
					local function tp(player,player2)
						local char1,char2=player.Character,player2.Character
						if char1 and char2 then
							char1:MoveTo(char2.Head.Position)
						end
					end
					wait(0.1)
					lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
					wait(0.2)
					lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character.HumanoidRootPart.CFrame
					wait(0.5)
					lplayer.Character.HumanoidRootPart.CFrame = NOW
					wait(0.6)
					tp(lplayer, game:GetService("Players")[v.Name])
					wait(0.4)
					lplayer.Character.HumanoidRootPart.CFrame = NOWPLR
					game:GetService("StarterGui"):SetCore("SendNotification", {
						Title = "Tools needed!";
						Text = "You need a tool in your backpack for this command!";
					})
				end
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("glitch ") then
				for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 8))) do
					lplayer.Character.Humanoid.Name = 1
					local l = lplayer.Character["1"]:Clone()
					l.Parent = lplayer.Character
					l.Name = "Humanoid"
					wait(0.1)
					lplayer.Character["1"]:Destroy()
					game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character
					lplayer.Character.Animate.Disabled = true
					wait(0.1)
					lplayer.Character.Animate.Disabled = false
					lplayer.Character.Humanoid.DisplayDistanceType = "None"
					for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
						lplayer.Character.Humanoid:EquipTool(v)
					end
					lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character["Left Arm"].CFrame
					wait(0.3)
					lplayer.Character.HumanoidRootPart.CFrame = game:GetService("Players")[v.Name].Character["Left Arm"].CFrame
					wait(0.4)
					b = Instance.new("BodyForce")
					b.Parent = lplayer.Character.HumanoidRootPart
					b.Name = "Glitch"
					b.Force = Vector3.new(100000000,5000,0)
					game:GetService("StarterGui"):SetCore("SendNotification", {
						Title = "Tools needed!";
						Text = "You need a tool in your backpack for this command!";
					})
				end
			end
			if string.sub(CMDBAR.Text, 1, 8) == ("unglitch") then
				lplayer.Character.HumanoidRootPart.Glitch:Destroy()
				lplayer.Character.HumanoidRootPart.CFrame = CFrame.new(10000,0,10000)
				b = Instance.new("BodyForce")
				b.Parent = lplayer.Character.HumanoidRootPart
				b.Name = "unGlitch"
				b.Force = Vector3.new(0,-5000000,0)
				wait(2)
				lplayer.Character.HumanoidRootPart.unGlitch:Destroy()
			end
			if string.sub(CMDBAR.Text, 1, 8) == ("grespawn") then
				lplayer.Character.Humanoid.Health = 0
				wait(1)
				lplayer.Character.Head.CFrame = CFrame.new(1000000,0,1000000)
				lplayer.Character.Torso.CFrame = CFrame.new(1000000,0,1000000)
			end
			if string.sub(CMDBAR.Text, 1, 8) == ("explorer") then
				loadstring(game:GetObjects("rbxassetid://492005721")[1].Source)()
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Success!";
					Text = "DEX Explorer has loaded.";
				})
			end
			if string.sub(CMDBAR.Text, 1, 5) == ("anim ") then
				local Anim = Instance.new("Animation")
				Anim.AnimationId = "rbxassetid://"..(string.sub(CMDBAR.Text, 6))
				local track = lplayer.Character.Humanoid:LoadAnimation(Anim)
				track:Play(.1, 1, 1)
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("animgui") then
				loadstring(game:GetObjects("rbxassetid://1202558084")[1].Source)()
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Success!";
					Text = "Energize Animations GUI has loaded.";
				})
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("savepos") then
				saved = lplayer.Character.HumanoidRootPart.CFrame
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Position Saved";
					Text = "Use ;loadpos to return to saved position.";
				})
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("loadpos") then
				lplayer.Character.HumanoidRootPart.CFrame = saved
			end
			if string.sub(CMDBAR.Text, 1, 5) == ("bang ") then
				for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 6))) do
					local Anim2 = Instance.new("Animation")
					Anim2.AnimationId = "rbxassetid://148840371"
					local track2 = lplayer.Character.Humanoid:LoadAnimation(Anim2)
					track2:Play(.1, 1, 1)
					bplrr = v.Name
					banpl = true
				end
			end
			if string.sub(CMDBAR.Text, 1, 6) == ("unbang") then
				banpl = false
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("bringmod ") then
				local function bringmodw()
					for i,obj in ipairs(game:GetService("Workspace"):GetDescendants()) do
						if obj.Name == (string.sub(CMDBAR.Text, 10)) then
							for i,ch in pairs(obj:GetDescendants()) do
								if (ch:IsA("BasePart")) then
									ch.CFrame = lplayer.Character.HumanoidRootPart.CFrame
									ch.CanCollide = false
									ch.Transparency = 0.7
									wait()
									ch.CFrame = lplayer.Character["Left Leg"].CFrame
									wait()
									ch.CFrame = lplayer.Character["Right Leg"].CFrame
									wait()
									ch.CFrame = lplayer.Character["Head"].CFrame
								end
							end
						end
					end
				end
				while wait() do
					bringmodw()
				end
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "BringMod";
					Text = "BringMod enabled.";
				})
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("respawn") then
				local mod = Instance.new('Model', workspace) mod.Name = 're '..lplayer.Name
				local hum = Instance.new('Humanoid', mod)
				local ins = Instance.new('Part', mod) ins.Name = 'Torso' ins.CanCollide = false ins.Transparency = 1
				lplayer.Character = mod
			end
			if string.sub(CMDBAR.Text, 1, 8) == ("shutdown") then
				game:GetService'RunService'.Stepped:Connect(function()
					pcall(function()
						for i,v in pairs(game:GetService'Players':GetPlayers()) do
							if v.Character ~= nil and v.Character:FindFirstChild'Head' then
								for _,x in pairs(v.Character.Head:GetChildren()) do
									if x:IsA'Sound' then x.Playing = true x.CharacterSoundEvent:FireServer(true, true) end
								end
							end
						end
					end)
				end)
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Attempting Shutdown";
					Text = "Shutdown Attempt has begun.";
				})
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("delobj ") then
				objtodel = (string.sub(CMDBAR.Text, 8))
				for i,v in pairs(game:GetService("Workspace"):GetDescendants()) do
					if v.Name == objtodel then
						v:Destroy()
					end
				end
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("getplrs") then
				for i,v in pairs(game:GetService("Players"):GetPlayers())do
					print(v)
				end
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Printed";
					Text = "Players have been printed to console. (F9)";
				})
			end
			if string.sub(CMDBAR.Text, 1, 8) == ("deldecal") then
				for i,v in pairs(game:GetService("Workspace"):GetDescendants())do
					if (v:IsA("Decal")) then
						v:Destroy()
					end
				end
			end
			if string.sub(CMDBAR.Text, 1, 10) == ("opfinality") then
				loadstring(game:GetObjects("rbxassetid://1294358929")[1].Source)()
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Success!";
					Text = "OpFinality GUI has loaded.";
				})
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("remotes") then
				remotes = true
				added = true
				game.DescendantAdded:connect(function(rmt)
					if added == true then
						if remotes == true then 
							if rmt:IsA("RemoteEvent") then
								print("A RemoteEvent was added!")
								print(" game." .. rmt:GetFullName() .. " | RemoteEvent")
								print(" game." .. rmt:GetFullName() .. " | RemoteEvent", 247, 0, 0, true)
							end end end
				end)
				game.DescendantAdded:connect(function(rmtfnctn)
					if added == true then
						if remotes == true then 
							if rmtfnctn:IsA("RemoteFunction") then
								warn("A RemoteFunction was added!")
								warn(" game." .. rmtfnctn:GetFullName() .. " | RemoteFunction")
								print(" game." .. rmtfnctn:GetFullName() .. " | RemoteFunction", 5, 102, 198, true)
							end end end
				end)

				game.DescendantAdded:connect(function(bndfnctn)
					if added == true then
						if binds == true then 
							if bndfnctn:IsA("BindableFunction") then
								print("A BindableFunction was added!")
								print(" game." .. bndfnctn:GetFullName() .. " | BindableFunction")
								print(" game." .. bndfnctn:GetFullName() .. " | BindableFunction", 239, 247, 4, true)
							end end end
				end)

				game.DescendantAdded:connect(function(bnd)
					if added == true then
						if binds == true then 
							if bnd:IsA("BindableEvent") then
								warn("A BindableEvent was added!")
								warn(" game." .. bnd:GetFullName() .. " | BindableEvent")
								print(" game." .. bnd:GetFullName() .. " | BindableEvent", 13, 193, 22, true)
							end end end
				end)


				if binds == true then
					for i,v in pairs(game:GetDescendants()) do
						if v:IsA("BindableFunction") then
							print(" game." .. v:GetFullName() .. " | BindableFunction")
							print(" game." .. v:GetFullName() .. " | BindableFunction", 239, 247, 4, true)
						end end
					for i,v in pairs(game:GetDescendants()) do
						if v:IsA("BindableEvent") then
							warn(" game." .. v:GetFullName() .. " | BindableEvent")
							print(" game." .. v:GetFullName() .. " | BindableEvent", 13, 193, 22, true)
						end end
				else
					print("Off")
				end
				if remotes == true then
					for i,v in pairs(game:GetDescendants()) do
						if v:IsA("RemoteFunction") then
							warn(" game." .. v:GetFullName() .. " | RemoteFunction")
							print(" game." .. v:GetFullName() .. " | RemoteFunction", 5, 102, 198, true)
						end end
					wait()
					for i,v in pairs(game:GetDescendants()) do
						if v:IsA("RemoteEvent") then
							print(" game." .. v:GetFullName() .. " | RemoteEvent")
							print(" game." .. v:GetFullName() .. " | RemoteEvent", 247, 0, 0, true)
						end end
				else
					print("Off")
				end
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Printing Remotes";
					Text = "Type ;noremotes to disable.";
				})
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("noremotes") then
				remotes = false
				added = false
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Printing Remotes Disabled";
					Text = "Type ;remotes to enable.";
				})
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("tpdefault") then
				spin = false
				followed = false
				traill = false
				noclip = false
				annoying = false
				hwalk = false
				cbringing = false
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("stopsit") then
				stopsitting = true
			end
			if string.sub(CMDBAR.Text, 1, 5) == ("gosit") then
				stopsitting = false
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("version") then
				print(adminversion)
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Version";
					Text = adminversion;
				})
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("clicktp") then
				clickgoto = true
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Click TP";
					Text = "Press E to teleport to mouse position";
				})
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("noclicktp") then
				clickgoto = false
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Click TP";
					Text = "Click TP has been disabled.";
				})
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("toolson") then
				gettingtools = true
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Tools Enabled";
					Text = "Automatically colleting tools dropped.";
				})
			end
			if string.sub(CMDBAR.Text, 1, 8) == ("toolsoff") then
				gettingtools = false
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Tools Disabled";
					Text = "Click TP has been disabled.";
				})
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("delcmdbar") then
				ScreenGui:Destroy()
			end
			if string.sub(CMDBAR.Text, 1, 5) == ("reset") then
				lplayer.Character.Head:Destroy()
			end
			if string.sub(CMDBAR.Text, 1, 6) == ("state ") then
				statechosen = string.sub(CMDBAR.Text, 7)
				changingstate = true
			end
			if string.sub(CMDBAR.Text, 1, 8) == ("gravity ") then
				game:GetService("Workspace").Gravity = string.sub(CMDBAR.Text, 9)
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("looprhats") then
				removingmeshhats = true
			end
			if string.sub(CMDBAR.Text, 1, 11) == ("unlooprhats") then
				removingmeshhats = false
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("looprtool") then
				removingmeshtool = true
			end
			if string.sub(CMDBAR.Text, 1, 11) == ("unlooprtool") then
				removingmeshtool = false
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("givetool ") then
				for i,v in pairs(game:GetService("Players").LocalPlayer.Character:GetDescendants()) do
					if v:IsA("Tool") then
						for i,player in pairs(GetPlayer(string.sub(CMDBAR.Text, 10))) do
							v.Parent = player.Character
						end
					end
				end
			end
			if string.sub(CMDBAR.Text, 1, 4) == ("age ") then
				for i,player in pairs(GetPlayer(string.sub(CMDBAR.Text, 5))) do
					game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(player.Name.." Account Age: "..player.AccountAge.." days!", "All")
				end
			end
			if string.sub(CMDBAR.Text, 1, 3) == ("id ") then
				for i,player in pairs(GetPlayer(string.sub(CMDBAR.Text, 4))) do
					game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(player.Name.." Account ID: "..player.UserId, "All")
				end
			end
			if string.sub(CMDBAR.Text, 1, 5) == (".age ") then
				for i,player in pairs(GetPlayer(string.sub(CMDBAR.Text, 6))) do
					game:GetService("StarterGui"):SetCore("SendNotification", {
						Title = player.AccountAge.." Days";
						Text = "Account age of "..player.Name;
					})
				end
			end
			if string.sub(CMDBAR.Text, 1, 4) == (".id ") then
				for i,player in pairs(GetPlayer(string.sub(CMDBAR.Text, 5))) do
					game:GetService("StarterGui"):SetCore("SendNotification", {
						Title = player.UserId.." ID";
						Text = "Account ID of "..player.Name;
					})
				end
			end
			if string.sub(CMDBAR.Text, 1, 6) == ("gameid") then
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "Game ID";
					Text = "Game ID: ".. game.GameId;
				})
			end
			if string.sub(CMDBAR.Text, 1, 3) == ("pgs") then
				local pgscheck = game:GetService("Workspace"):PGSIsEnabled()
				if pgscheck == true then
					game:GetService("StarterGui"):SetCore("SendNotification", {
						Title = "PGSPhysicsSolverEnabled";
						Text = "PGS is Enabled!";
					})
				else
					game:GetService("StarterGui"):SetCore("SendNotification", {
						Title = "PGSPhysicsSolverEnabled";
						Text = "PGS is Disabled!";
					})
				end
			end
			if string.sub(CMDBAR.Text, 1, 11) == ("removeinvis") then
				for i,v in pairs(game:GetService("Workspace"):GetDescendants()) do
					if v:IsA("Part") then
						if v.Transparency == 1 then
							if v.Name ~= "HumanoidRootPart" then
								v:Destroy()
							end
						end
					end
				end
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("removefog") then
				game:GetService("Lighting").FogStart = 0
				game:GetService("Lighting").FogEnd = 9999999999999
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("disable") then
				lplayer.Character.Humanoid.Parent = lplayer
			end
			if string.sub(CMDBAR.Text, 1, 6) == ("enable") then
				lplayer.Humanoid.Parent = lplayer.Character
			end
			if string.sub(CMDBAR.Text, 1, 13) == ("givealltools ") then
				for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetDescendants()) do
					if v:IsA("Tool") then
						v.Parent = lplayer.Character
						wait()
						for i,player in pairs(GetPlayer(string.sub(CMDBAR.Text, 14))) do
							v.Parent = player.Character
						end
					end
				end
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("flyspeed ") then
				speedfly = string.sub(CMDBAR.Text, 10)
				wait()
				change()
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("carpet ") then
				for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 8))) do
					local Anim3 = Instance.new("Animation")
					Anim3.AnimationId = "rbxassetid://282574440"
					local track3 = lplayer.Character.Humanoid:LoadAnimation(Anim3)
					track3:Play(.1, 1, 1)
					bplrr = v.Name
					banpl = true
				end
			end
			if string.sub(CMDBAR.Text, 1, 8) == ("uncarpet") then
				banpl = false
			end
			if string.sub(CMDBAR.Text, 1, 6) == ("stare ") then
				for i,v in pairs(GetPlayer(string.sub(CMDBAR.Text, 7))) do
					staring = true
					stareplr = v
				end
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("unstare") then
				staring = false
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("logchat") then
				chatlogs = true
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "LogChat enabled";
					Text = "Now logging all player chat.";
				})
			end
			if string.sub(CMDBAR.Text, 1, 9) == ("unlogchat") then
				chatlogs = false
				game:GetService("StarterGui"):SetCore("SendNotification", {
					Title = "LogChat disabled";
					Text = "Stopped logging all player chat.";
				})
			end
			if string.sub(CMDBAR.Text, 1, 6) == ("fixcam") then
				game:GetService("Workspace").CurrentCamera:Destroy()
				wait(0.1)
				game:GetService("Workspace").CurrentCamera.CameraSubject = lplayer.Character.Humanoid
				game:GetService("Workspace").CurrentCamera.CameraType = "Custom"
				lplayer.CameraMinZoomDistance = 0.5
				lplayer.CameraMaxZoomDistance = 400
				lplayer.CameraMode = "Classic"
			end
			if string.sub(CMDBAR.Text, 1, 7) == ("unstate") then
				changingstate = false
			end
			CMDBAR.Text = ""
		end
	end)

	wait(0.3)
	game:GetService("StarterGui"):SetCore("SendNotification", {
		Title = "Loaded successfully!";
		Text = "Reviz Admin V2 by illremember";
	})
	wait(0.1)
	print("Reviz Admin V2 loaded!")
	if game:GetService("Workspace").FilteringEnabled == true then
		warn("FE is Enabled (Filtering Enabled)")
		game:GetService("StarterGui"):SetCore("SendNotification", {
			Title = "FE is Enabled";
			Text = "Filtering Enabled. Enjoy using Reviz Admin!";
		})
	else
		warn("FE is Disabled (Filtering Disabled) Consider using a different admin script.")
		game:GetService("StarterGui"):SetCore("SendNotification", {
			Title = "FE is Disabled";
			Text = "Filtering Disabled. Consider using a different admin script.";
		})
	end

	local intro = Instance.new("ScreenGui")
	local Frame = Instance.new("Frame")
	local ImageLabel = Instance.new("ImageLabel")
	intro.Parent = game:GetService("CoreGui")
	Frame.Parent = intro
	Frame.BackgroundColor3 = Color3.new(1, 1, 1)
	Frame.BackgroundTransparency = 1
	Frame.Size = UDim2.new(1, 0, 0, 300)
	Frame.Position = UDim2.new(0, 0, -0.4, 0)
	ImageLabel.Parent = Frame
	ImageLabel.BackgroundColor3 = Color3.new(1, 1, 1)
	ImageLabel.BackgroundTransparency = 1
	ImageLabel.Position = UDim2.new(0, 0, 0, 0)
	ImageLabel.Size = UDim2.new(1, 0, 1, 0)
	ImageLabel.Image = "http://www.roblox.com/asset/?id=1542162618"
	Frame:TweenPosition(UDim2.new(0, 0, 0.2, 0), "Out", "Elastic", 3)
	wait(3.01)
	Frame:TweenPosition(UDim2.new(0, 0, 1.5, 0), "Out", "Elastic", 5)
	wait(5.01)
	intro:Destroy()
end)

clicktp.MouseButton1Click:connect(function() do
		-- How to use; click 'e' on your keyboard and you will
		-- teleport to where ever your mouse is.

		plr = game.Players.LocalPlayer

		hum = plr.Character.HumanoidRootPart

		mouse = plr:GetMouse()



		mouse.KeyDown:connect(function(key)

			if key == "e" then

				if mouse.Target then

					hum.CFrame = CFrame.new(mouse.Hit.x, mouse.Hit.y + 5, mouse.Hit.z)

				end

			end
		end)
	end
end)

LoopKill.MouseButton1Click:connect(function() do
		loadstring(game:GetObjects('rbxassetid://1010374652')[1].Source)() 
	end
end)
