This is a Appman project like a pacman that makes easier to use of apt 



The configuration of it are 


Apman Version 1.0
apman basically clone like of pacman. It is basically 
do built a command case layer over apt and execute it.
Underhood basically its run shell command of apt.

Neumerus Argument present in here

All Flags shown in here.




	Type:	

		apman [MainFlag] [Working Instructable Flag] [yes/no Flag] [Installable App name Flag]


	for MainFlag:
	
		s  -- for all apt package install, listing, update etc.
		d  -- show the dist info
		el -- log info
		ac -- configuration of apt




	Working Instructable Flag:
	
	
	for s:
		lu    -- used for listed upgradeble program
		u     -- used for update
		ug    -- used for upgrade package
		yuu   -- used for update upgrade both with y flag
		uug   -- used for full system upgrade
		i     -- used for installing any program
		rr    -- used for fully removed unwanted
		r     -- used for removing unwanted program
		sr    -- used for removing unwanted program fully
		
		
	for d: 
		a     -- used for full system kernel info
		n     -- used for neofetch show
		pi    -- used for to show total number of installed package
		pc    -- used for to show installed package
		or    -- used for to show os release info
		hc    -- used for hositle show


	for ac:
		rp    -- used for to see repo list
	    	cr    -- used for to configure repo
		pr    -- used for to see control on repo
		cpr   -- used for to configure control file 
		acl   -- used for cleaning apt cache


	for el:
		cl    -- used for clear log
		sl    -- used for showing content of log
		rl    -- used for removing log from $log

				
		
		
		
