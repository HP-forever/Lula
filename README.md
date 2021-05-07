--[[lua]]
name ="lula"
io.write("Size of string",#name,"\n")
io.write("my name",#name,"\n")

a=1
b=a+1
io.write(b)
io.write("math fuction is",math.ceil(2.5))
--io.write("random number",math.random(5,100),math.randomseed(os.time))
print(string.format("Pi = %.10f",math.pi))
age=13
if age <16 then  
    print("good","\n")
elseif (age >16) and (age <18) then 
    print("nibbb")
else print("no")
end
age= 10
canvote =age >19 and true or false
print("\n")
quete ="i am a good boy"
print("quete length",string.len(quete,"\n"))
print("quete length",#quete,"\n")
io.write("替换",string.gsub(quete,"i","boy"),"\n")
print("index",string.find(quete,"boy" ),"\n")

i=1
while(i<=10) do
    print(i)
    i=i+1
  if i==5 then break end
end

---repeat
   --- print("enter your guess")

   --- guess= io.read()
---until  tonumber(guess)==10

for i =1,10,1 do
    print(i)
end
