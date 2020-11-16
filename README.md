# GeometryBin
I didn't like how some premade geometry functions worked in BASH so I made my own as well as a system for dot products and cross products of those.
To make this work just put these in any PATH folder, make the files executable (chmod +x *), and you should be able to enter 3D vectors as strings delimited by a space.
I wrote these for use with atoms and coordinates so each vector also needs a label, for example: dotp "a 1 1 1" "b 0 0 1" will give us the dot products of a and b


As for a PATH folder I always make one in my home directory called bin and if you do that you can add it as a PATH directory with: 
export PATH="/home/user/bin:$PATH"     but replace user with your username
