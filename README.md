# tor-chrome
automate chrome with tor browser for anonymous work !

# Usage

## step 1

install and open tor bowser https://www.torproject.org/projects/torbrowser.html.en

## step 2 

Tor = TorChrome(r'path_to_Tor_Browser')
Tor.configure()

## step 3

br = Tor.chrome()
br.get('https://www.google.com')

## step 4 change ip 

br.change_ip()
