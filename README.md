# Intro
This is a simple Capacitor application, showing a basic html form.
The html form includes autocomplete hints, for filling user data with existing
user information.

# Setup
The web part is only an html and a css file, it must not be built. The capacitor 
config references the files directly. 

`npm install`

`npx cap sync`

`npx cap open android` |
`npx cap open ios`

# Android
## Preparation
- setup an autofill service
    - Google Pixel 6a, Android 13: _Passwords & accounts_ > _Autofill service_
- in my case I use the _Google_ Autofill service
- make sure, the _Autofill service_ is enabled and provides data (check the settings)


## Testing
- start the app
- begin typing in the fields
- ⚠️no autofill behaviour within the app 


# iOS
## Testing
- start the app
- begin typing in the fields
- ⚠️only some fields get autofill support