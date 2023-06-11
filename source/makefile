MAKEOBJ = makeobj_60-5
DIR = ../pak/
PAK = pak

$(DIR)/building.YIC-railstop-platform-1_Diagonal(Side).pak  : YIC_platform-1_Diagonal-Side.dat YIC_platform-1_Diagonal-Side.png platform-1.png
	$(MAKEOBJ) $(PAK) $(DIR) YIC_platform-1_Diagonal-Side.dat

$(DIR)/building.YIC-railstop-platform-1_Diagonal(Side-D).pak  : YIC_platform-1_Diagonal-Side.dat YIC_platform-1_Diagonal-Side.png platform-1.png
	$(MAKEOBJ) $(PAK) $(DIR) YIC_platform-1_Diagonal-Side_D.dat

$(DIR)/building.YIC-railstop-platform-1_Diagonal(Angle).pak : YIC_platform-1_Diagonal-Angle.dat YIC_platform-1_Diagonal-Angle.png platform-1.png
	$(MAKEOBJ) $(PAK) $(DIR) YIC_platform-1_Diagonal-Angle.dat

$(DIR)/building.YIC-railstop-platform-1_Diagonal(Angle-D).pak : YIC_platform-1_Diagonal-Angle_D.dat YIC_platform-1_Diagonal-Angle.png platform-1.png
	$(MAKEOBJ) $(PAK) $(DIR) YIC_platform-1_Diagonal-Angle_D.dat

$(DIR)/building.YIC-railstop-platform-1_Diagonal(Angle-Fence-FB).pak : YIC_platform-1_Diagonal-Angle_Fence-FB.dat YIC_platform-1_Diagonal-Angle_Fence-FB.png platform-1s.png
	$(MAKEOBJ) $(PAK) $(DIR) YIC_platform-1_Diagonal-Angle_Fence-FB.dat

$(DIR)/building.YIC-railstop-platform-1_Diagonal(Angle-Fence-LR).pak : YIC_platform-1_Diagonal-Angle_Fence-LR.dat YIC_platform-1_Diagonal-Angle_Fence-LR.png platform-1s.png
	$(MAKEOBJ) $(PAK) $(DIR) YIC_platform-1_Diagonal-Angle_Fence-LR.dat

$(DIR)/building.YIC-railstop-platform-1_Diagonal(Angle-Fence-A).pak : YIC_platform-1_Diagonal-Angle_Fence-A.dat YIC_platform-1_Diagonal-Angle_Fence-A.png platform-1s.png
	$(MAKEOBJ) $(PAK) $(DIR) YIC_platform-1_Diagonal-Angle_Fence-A.dat




$(DIR)/building.YIC-railstop-platform-1_Diagonal(Side-Fence).pak : YIC_platform-1_Diagonal-SideFence.dat YIC_platform-1_Diagonal-SideFence.png platform-1s.png
	$(MAKEOBJ) $(PAK) $(DIR) YIC_platform-1_Diagonal-SideFence.dat 

all: $(DIR)/building.YIC-railstop-platform-1_Diagonal(Angle).pak \
	$(DIR)/building.YIC-railstop-platform-1_Diagonal(Side).pak \
	$(DIR)/building.YIC-railstop-platform-1_Diagonal(Side-D).pak \
	$(DIR)/building.YIC-railstop-platform-1_Diagonal(Angle-D).pak \
	$(DIR)/building.YIC-railstop-platform-1_Diagonal(Angle-Fence-FB).pak \
	$(DIR)/building.YIC-railstop-platform-1_Diagonal(Angle-Fence-LR).pak \
	$(DIR)/building.YIC-railstop-platform-1_Diagonal(Angle-Fence-A).pak \
	$(DIR)/building.YIC-railstop-platform-1_Diagonal(Side-Fence).pak \

.PHONY: pre-release
