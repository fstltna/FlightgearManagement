# Flightgear Management Console (1.0)
Allows you to manage your Flightgear server with a text based GUI - 
Official support sites: [Official Github Repo](https://github.com/fstltna/FlightgearManagement) - [Official Forum](https://flightgearneo.gameplayer.club/index.php/forum/our-flightgear-tools)


---

Edit "fmmc" and change the settings at the top if your Flightgear server is not in /home/flightgear/fgms-0-x.

You will need to run cpan (as root) and install these modules:

- cpan -i UI::Dialog
- cpan -i Term::ReadKey
- cpan -i Term::ANSIScreen

You also need to have my Flightgear Startup Script installed.

I suggest you then add this to your /home/flightgear/.bashrc file:
	export PATH=/home/flightgear/bin:/home/flightgear/FlightgearManagement:$PATH

After that you should log out and back in and now "fmmc" should work.
