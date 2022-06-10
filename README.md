# TheVoid
Plugin documentation


# Check running script
```lua
api:IsRunning() -- Checks if the code should be running
```

<details><summary>Example</summary>
<p>

  
```lua
print(api:IsRunning()) --> true  
```
```lua
if not api:IsRunning() then
  api:quit()
end
```
  
</p>
</details>
