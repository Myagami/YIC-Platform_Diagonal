MAKEOBJ = makeobj_60-5
DIR = ./
PAK = pak

building.YIC-railstop-platform-1_Diagonal(Side).pak  : YIC_platform-1_Diagonal-Side.dat YIC_platform-1_Diagonal-Side.png platform-1.png
	$(MAKEOBJ) $(PAK) $(DIR) YIC_platform-1_Diagonal-Side.dat

building.YIC-railstop-platform-1_Diagonal(Angle).pak : YIC_platform-1_Diagonal-Angle.dat YIC_platform-1_Diagonal-Angle.png platform-1.png
	$(MAKEOBJ) $(PAK) $(DIR) YIC_platform-1_Diagonal-Angle.dat

building.YIC-railstop-platform-1_Diagonal(Angle-D).pak : YIC_platform-1_Diagonal-Angle_D.dat YIC_platform-1_Diagonal-Angle.png platform-1.png
	$(MAKEOBJ) $(PAK) $(DIR) YIC_platform-1_Diagonal-Angle_D.dat

building.YIC-railstop-platform-1_Diagonal(Side-Fence).pak : YIC_platform-1_Diagonal-SideFence.dat YIC_platform-1_Diagonal-SideFence.png platform-1s.png
	$(MAKEOBJ) $(PAK) $(DIR) YIC_platform-1_Diagonal-SideFence.dat 

all: building.YIC-railstop-platform-1_Diagonal(Angle).pak \
	building.YIC-railstop-platform-1_Diagonal(Side).pak \
	building.YIC-railstop-platform-1_Diagonal(Angle-D).pak \
	building.YIC-railstop-platform-1_Diagonal(Side-Fence).pak\
