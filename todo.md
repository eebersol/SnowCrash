Must have :

- Lecteur pcap

	pcap «packet capture» est une interface de programmation permettant de capturer un trafic réseau.
	Elle est implémentée sous les systèmes GNU/Linux, FreeBSD, NetBSD, OpenBSD et Mac OS X par la bibliothèque libpcap. 
	WinPcap est le portage sous Windows de libpcap.

- gdb

	Debuggueur

- Jonh 

	Logicile pour craquer mot de pass

- Python/Ruby scripting

- Php/Perl/Lua scriptiong

- Shell scriptiong

Site : 
	- cloudshark.com
	- dcode.fr
	- duckduckgo.com

FLAG00 :

Cron est installé, cron.daily fait quelque chose avec les mots de passes.
Dans /usr/sbin/john, il y a "cdiiddwpgswtgt" => C'est encrypté en rot plus particulierement rot 11 = | cdiiddwpgswtgt == nottoohardhere |

FLAG01 : 

Le mot de passe est contenu dans /etc/passwd, il faut installer John et le run avec comme parametre le file contenant les passwd [resultat] -> mdp : abcedfg

su flag01
password : abcdefg
getflag 
token: f2av5il02puano7naaf6adaaf

LEVEL 03 et 12 sont dans /var/www



LEVEL 03 

- On nous donne un .pcap il va falloir utilier cloudshark










check xgilbert