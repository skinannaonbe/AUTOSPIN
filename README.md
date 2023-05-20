while true do
    wait()
    
local args = {
    [1] = "Update1.5Spins"
}

game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("send_code_to_server"):FireServer(unpack(args))
end
