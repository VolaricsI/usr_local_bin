# usr_local_bin

    Ide kerül minden scrip melyet valaha is írtam

##	0
	    Egy csontváz a jövőbeni script-ek számára

##	*.example
	    Minta állomány, a "*" nevű script használatához

##	TBS
	    A TBS álltal gyártott DVB-T/C tunerekhez fordítási script; 
	    valamint patch, hogy újabb kernelekkel is leforduljon

##	lid
	    A laptop fedél lecsukásakor kapcsolja ki a kijelzőt




##	btrfs-du
	    egy nagyon jó program:
		wget https://raw.githubusercontent.com/nachoparker/btrfs-du/master/btrfs-du -O /usr/local/sbin/btrfs-du
		chown +x /usr/local/sbin/btrfs-du
		fellelhetősége: https://ownyourbits.com/2017/12/06/check-disk-space-of-your-btrfs-snapshots-with-btrfs-du/
		csak kell hozzá a következő parancs:	btrfs quota enable
