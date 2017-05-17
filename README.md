# True-weaponSystem
-- Hello, this is Phil and he's the clerk
-- His job is to selll all of you items
-- In this world, mercantilism has established
-- Iron Ingots = 0.5$
-- Gold Ingots = 2.50$
-- Diamond = 50$
-- Diamond Block = 250$
local x = 250
local a = 50
local b = 2.50
local y = 0.5
local "minecraft:diamond_sword" = 100
local "minecraft:diamond_hoe" = 95
local "minecraft:diamond_axe" = 90
local "minecraft:diamond_pickaxe" = 100
local "minecraft:gold_sword" = 85
local "minecraft:gold_hoe" = 80
local "minecraft:gold_axe" = 80
local "minecraft:gold_pickaxe" = 85
local "minecraft:iron_sword" = 75
local "minecraft:iron_axe" = 70
local "minecraft:iron_hoe" = 70
local "minecraft:iron_pickaxe" = 75
local "minecraft:wood_sword" = 5
local "minecraft:wood_axe" = 5
local "minecraft:wood_hoe" = 5
local "minecraft:wood_pickaxe" = 5
 
local function Diamond_process()
-- Basically, this function will aid the turtle
-- identify Diamonds blocks and give back the proper item.
local x = "minecraft:diamond_block"
if turtle.inspect() == "minecraft:diamond_block" then
 turtle.say( "Thank you. that is a suffcient amount of money!" )
 turtle.select(1)
 turtle.drop()
elseif turtle.say( "sorry friend, but that isn't enough to buy this product." )
then end
end
local function DIAMOND()
local a = 50
-- This will do the same thing but for diamonds
if local a = "minecraft:diamond" then
turtle.say( "thank you very much, it is appreciated." )
then turtle.select(1)
turtle.drop()
elseif turtle.say( "sorry but that won't suffice" )
then end
end
 
local function GOLDENEXP()
local b = 2.50
-- Again, rinse and repeat.
if local b = "minecraft:gold_ingot"
