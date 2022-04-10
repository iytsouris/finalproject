# Getting the Files
1. Download files from source
2. Unzip files
3. Upload files to VSCode

# Setting up the API Key
- Our website utilizes a weather API so you will have to set an API Key
1. If you want to use our API key, it is 587d28134470496eba331008210212 and you can skip to step 7. If you want to use your own key, follow steps 2-6
2. Go to https://www.weatherapi.com/signup.aspx and make an account
3. Confirm your email address by clicking the provided link in the confirmation email
4. Log in with your new credentials
5. On the top of the screen there will be a box that says API Key: with your key
6. Copy the key
7. Once you have your key, execute "export API_KEY=(Your key)" in the command line terminal

# Running the website
1. Execute "flask run" and open the provided link

# How to use our website
1. At the home screen you will be directed to input a location
    - Formats accepted are US Zipcodes, UK Postcodes, Canada Postalcodes, IP addresses, Latitude/Longitude (decimal degree) and city names
    - There will also be an option to select preference for Fahrenheit or Celsius; fahrenheit is selected by default
2. Based on your input, you will be taken to a screen directing you how to dress
    - In addition to layering advice, the directed page will display the location inputted, the current temperature, the weather condition (e.g. sunny, overcast, light rain, etc), and additional advice as well as an animation if there is rain or snow
3. If you would like to go back to the homepage, you can do so at any time by clicking "Survival Guide to Layering" in the top left corner

# Link to our video:
https://youtu.be/WMGziNUqWhg