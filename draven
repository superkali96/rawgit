if myHero.charName ~= "Draven" then return end

require ("DamageLib")

local closest = math.huge
	local bestAxe = nil
	local bestAxePos = nil
	for _, axes in pairs(CatchPos) do
		if DravenMenu.Misc.AC:Value() and axes and Axe < 3 then
			if GetDistance(axes) < closest then
				closest = GetDistance(axes)
				bestAxe = axes
				Blop = Vector(bestAxe)
				bestAxePos = Blop + (Blop - myHero.pos):normalized() * 100
			end
        end
    end
    
end
