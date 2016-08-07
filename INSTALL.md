# Linux

	sudo apt-get install make gcc bison git python

	git clone https://github.com/bentley/rgbds
	cd rgbds
	sudo make install
	cd ..

	git clone --recursive https://github.com/marysiamzawka/pokered-PL
	cd pokered

By skompilować **pokered.gbc** i **pokeblue.gbc**:

	make

By skompilować każdy z osobna

	make red
	make blue


# Mac

W **Terminalu**:

	xcode-select --install

	git clone https://github.com/bentley/rgbds
	cd rgbds
	sudo make install
	cd ..

	git clone --recursive https://github.com/marysiamzawka/pokered-PL
	cd pokered

	make


# Windows

Zainstaluj [**Cygwin**](http://cygwin.com/install.html). Użyj ustawień domyślnych.

W instalatorze wybierz pakiety: `make` `git` `python` `gettext`

Pobierz najnowszą wersję [**rgbds**](https://github.com/bentley/rgbds/releases/).
Wypakuj archiwum i umieść `rgbasm.exe`, `rgblink.exe` oraz`rgbfix.exe` w `C:\cygwin\usr\local\bin`.

W **Terminalu Cygwina**:

	git clone --recursive https://github.com/marysiamzawka/pokered-PL
	cd pokered

	make
