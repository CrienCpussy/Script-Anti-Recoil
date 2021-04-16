# Script-Anti-Recoil
que pour Les LOGITECH 


function OnEvent(event, arg)
OutputLogMessage("event = %s, arg = %d\n", event, arg)
if (event == "PROFILE_ACTIVATED") then
EnablePrimaryMouseButtonEvents(true)
elseif event == "PROFILE_DEACTIVATED" then
ReleaseMouseButton(2) -- to prevent it from being stuck on
end
if (event == "MOUSE_BUTTON_PRESSED" and arg == 4) then
recoil = not recoil
spot = not spot
end
if (event == "MOUSE_BUTTON_PRESSED" and arg == 1 and recoil) then
if recoil then
repeat
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1,11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1,11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1,11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1,11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1,11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1,11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1,11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(-1, 11)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(100) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(10) if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 0)
Sleep(20) if not IsMouseButtonPressed(1) then break end
until not IsMouseButtonPressed(1)
end
end
end
