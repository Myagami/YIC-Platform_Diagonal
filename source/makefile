MAKEOBJ = makeobj_60-5
DIR = ./
PAK = pak

building.YIC-railstop-platform-1_Diagonal(Side).pak  : YIC_platform-1_Diagonal-Side.dat YIC_platform-1_Diagonal-Side.png
	$(MAKEOBJ) $(PAK) $(DIR) YIC_platform-1_Diagonal-Side.dat

building.YIC-railstop-platform-1_Diagonal(Angle).pak : YIC_platform-1_Diagonal-Angle.dat YIC_platform-1_Diagonal-Angle.png
	$(MAKEOBJ) $(PAK) $(DIR) YIC_platform-1_Diagonal-Angle.dat

all: building.YIC-railstop-platform-1_Diagonal(Angle).pak \
	building.YIC-railstop-platform-1_Diagonal(Side).pak 
