# esp2866insta
# Login Page with ESP8266
<p float="left">
  <img src="https://m.media-amazon.com/images/I/61UOyRccN0L._SL1000_.jpg" alt="Image 1" width="400" style="margin-right: 20px;">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Instagram_logo_2022.svg/225px-Instagram_logo_2022.svg.png" alt="Image 2" width="400">
</p>

This project demonstrates a Instagram login page implementation using ESP8266 programmed in C. The ESP8266 acts as an access point named "Free Wifi" and is hosted on the IP address `172.0.0.1`. Once a user successfully logs in, their login information is reflected on the IP `http://172.0.0.1/pass`.

## Functionality

The login page provides the following functionality:

- The ESP8266 sets up an access point named "Free Wifi" with the IP address `172.0.0.1`.
- Users can connect to the access point using their Wi-Fi enabled devices (such as smartphones or laptops).
- Upon connecting to the access point, users can access the login page by visiting `http://172.0.0.1` in their device's web browser.
- The login page prompts users to enter their login credentials (e.g., username and password).
- If the entered credentials are correct, the user is redirected to the URL `http://172.0.0.1/pass`, where their login information is displayed.

## Getting Started

To run this project on your ESP8266 device, follow these steps:

1. Set up the ESP8266 development environment.
2. Connect the ESP8266 to your computer.
3. Clone or download this repository.
4. Open the project in your preferred C programming IDE or text editor.
5. Configure the required settings such as Wi-Fi SSID, password, and login credentials in the code.
6. Compile and upload the code to the ESP8266 device.
7. Access the login page by connecting to the "Free Wifi" access point and visiting `http://172.0.0.1` in your web browser.
8. Enter the login credentials to test the functionality.

## Customization

You can customize the login page by modifying the HTML and CSS code in the ESP8266 C program. The HTML code for the login page can be found in the program file, and you can style it using embedded CSS or external CSS files.

## Limitations

- The login page is designed for demonstration purposes and may not provide robust security features. It is recommended to enhance the security measures according to your specific requirements if deploying this project in a production environment.
- The ESP8266 has limited processing power and memory, so complex operations and large-scale applications may not be feasible with this setup.
- This project assumes a basic understanding of C programming and ESP8266 development. Familiarity with ESP8266 SDK and tools will be beneficial when working on this project.

## License

This project is licensed under the [GNU License](LICENSE).
