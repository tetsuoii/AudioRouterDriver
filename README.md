# AudioRouterDriver
Virtual audio device for routing audio to multiple output devices



	OK, Rikard, da er vi i gang!
	
	Vi trenger WDK (Windows Driver Kit), ikke DDK som jeg sa.
	
	Det finnes et eksemepel som heter msvad (Microsoft Virtual
	Audio Driver) som vi kan bruke som utgangspunkt. Først må vi
	kompilere denne og se at den installerer i kontrollpanelet.
	
	Vi kopierer den rett inn i prosjektet, åpner den i VS og
	kompilerer i Release mode. Dersom den kopierer kan vi prøve
	å legge den til i device manager. Når dette fungerer og
	driveren finnes i Playback Devices er vi godt på vei.
	
	WDK:
	
	https://developer.microsoft.com/en-us/windows/hardware/windows-driver-kit
	
	
	Windows driver samples:
	
	https://github.com/Microsoft/Windows-driver-samples.git
	
	Hent eksemplene, lokaliser sysvad og kopier innholdet inn i vårt prosjekt.