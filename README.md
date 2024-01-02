# ipAddressInfo
In general, this code is designed to obtain and display information about IP addresses.

Defines a function get_info_by_ip() that takes an IP address as an argument (the default address is '127.0.0.1'). This function makes a request to the 'ip-api.com' service, which returns information about the given IP address. It then outputs the resulting data and creates a map using the folium library based on the geographic coordinates associated with that IP address. The map is saved in an HTML file with a name that includes the IP address and the city corresponding to that IP address.

Defines a main() function that prints the text 'IP INFO' in ASCII art style using the pyfiglet library. It then asks the user to enter the target IP address and passes it to the get_info_by_ip() function.
If this script is run as a main module (that is, not imported as a module), it calls the main() function to start the program.
