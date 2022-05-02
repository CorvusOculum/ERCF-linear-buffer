# ERCF-linear-buffer

NOTE: This is a work in progress.

This is a filament buffer system designed to replace the "caged loops" style of buffer that is popular, such as the Enraged Rabbit Carrot Patch.  This buffer differs from caged loops in that the filament is pushed down a very long linear channel as a single loop.  The narrow, yet wide channel prevents the filament from twisting.  When a particular channel is in use, the filament is retracted out of the channel and only contacts half of the pulley leading to very little drag in the system.  The channels are cut from 3/8 inch thick foam board.

I designed this system as a low drag alternative to the Carrot Patch style of buffer which can in my own experience be problematice with very long reverse-bowden lengths.  With a looping system, you add loops to add distance to the buffer.  When you add four or five loops, the drag can be quite significant.  This system only ever has a half loop of the pulley and when more length is needed, you simply use longer channels.  

# BOM

(N refers to the number of channels in your MMU system) 

    xN - Buffer Channel Pulley Block
    
    xN - Buffer Channel Top Block
    
    xN - Buffer Channel Pulley
    
    xN - Buffer Channel Pulley Axel
    
    xN - Buffer Channel Bottom Block
    
    xN - Buffer Channel Desiccant Tray
    
    xN - 608 RS "Skateboard" Bearing
         NOTE: I personally remove the seals with a sharp tool, and 
         then use a cleaner such as break cleaner to completely remove 
         all grease from the bearing.  The pulleys should spin like a
         fidget spinner when completed.  I don't know if this helps 
         anything at all...  But I do it anyway...
    
    2 x N / 3 - Buffer Channel Brace Bracket
         NOTE: You will want a 2 braces per channel to support the 
         foam board and mount the buffers to whatever you'll be using. 
         So in a 9 channel MMU system you will want: 2*9/3= 6 Brackets. 
    
    xN - M3 x 35mm SHCS
    xN - M3 Heatset Inserts
    
    28 x N - 6mm x 3mm disc magnets 
          NOTE: Depending on the quality of your magnets you may be able
          to use fewer.  The parts are designed to accomodate a lot of 
          magnets on the assumption that you will be using cheap ones from
          AliExpress or Amazon.  If you have genuine N52's for example, far
          fewer will be required.  Experiment.
    
    2 x N - PC4-M10 Straight through Pneumatic Fitting
	      NOTE: MUST BE A THROUGH FITTING!

# Construction

Your foam board should be cut using calipers.  Measure the inside of the narrow side of the channel and lock the calipers off.  Then use the calipers to score the foamboad.  Cut carefully with a long metal straightedge.  Do both short sides first, then measure the inside with of the long edge between the two smaller foam board pieces and cut the wider sides.  You want to have the edges of the short side foam board in the corners and not the long sides.  This is important!  The length of these channels should be roughly half the the length of your reverse bowden, but it is wise to add 10%-15% extra just in case.  Usually the foamboard will friction fit and stay in place, however it's a good idea to glue them.

Even with the drag reduction from this system, it is still critically important that you not have any sharp corners in your bowden tubing.  Large graceful bends are your friend!  

It is also highly recommended that you use 2.5mm or 3mm inner diameter (4mm outer) PTFE tubing everywhere per the recommendation of @Ette the creator of the ERCF.

# Credits
The pulley used in this design was taken from the EnragedRabbitProject by Ette.  This was by design, as anyone who has built an ERCP and has issues like I had can reuse the part when they switch.
https://github.com/EtteGit/EnragedRabbitProject

Inspiration for this style of buffer was also taken from the TodWuff's Linear Buffer Project.  I actually would have made this buffer rather than designing my own, but the cable channel they used was backordered in Canada by several months.
https://github.com/TodWulff/-MHz-ERCF-Filament-Rack-Buffer-Tube-Assy



