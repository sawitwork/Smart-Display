# Smart-Display

### Tool
Software > DGUS_V7646 
Driver > XR21X141X
NET Framework 3.5

###Command for control display

vp 84 >> 5A01 xxxx สั่งไป หน้าต่างๆ  
5a a5 07 82 00 84 5a 01 00 06  

vp xxxx(vp text ad) >> xx xx xx xx xx (ข้อความ)

0082 >> Brightness Adjust  
0080 >> Synchrodata return  
(20B0 off buzzer (5A A5 00 00 30) | 20B2 on Buzzer (5A A5 00 00 38))  
0004 >> Reset Display (20B4 (55 AA 5A A5))

VP2S >>20B0 (close buzzer) (20B2 open)
