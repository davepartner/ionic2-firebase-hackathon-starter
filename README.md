# Ionic2 Firebase3 Hackathon Starter Pack

## Notice

The updated version of this project with `geofire` and `geolocation` setup is [HERE](https://github.com/daveozoalor/Ionic3-firebase-authentication-geofire-geolocation). Dont forget to star it, I'm counting on you. Thanks!

This is a hackathon starter pack built with [Ionic 2](http://ionicframework.com) and [Firebase 3](https://firebase.google.com). 
It's a mobile template that comes complete with user registration, google login authentication, reset password, user profile and so on, so you don't have to go through that stress when next time you wish create a new Ionic2 app.  

## Tutorial

The video tutorials for this repo are on youtube, please do well and subscribe from [HERE](https://www.youtube.com/playlist?list=PLnBvgoOXZNCPxZJohnrdfR6Nlr1ilaHJO)

## Usage

To download and use this project, you need to have the following installed on your machine

* [NodeJs](http://nodejs.org)

* Create an account with [Firebase](http://firebase.google.com)

Once you have completed the above processes, you can then download this project directly or clone it using the following command
```
 git clone https://github.com/daveozoalor/ionic2-firebase-hackathon-starter
`````

After downloading/cloning it, change the directory and run `npm install` to pull in the project dependencies 
```
cd fireblogger
npm install
```

After doing so, you need to update the `app.ts` located in `app\app.ts` by putting your own firebase credentials that you obtained from firebase console of the project. It will look like this:

```
<script src="https://www.gstatic.com/firebasejs/3.3.0/firebase.js"></script>
<script>
  // Initialize Firebase
  // TODO: Replace with your project's customized code snippet
  var config = {
    apiKey: "<API_KEY>",
    authDomain: "<PROJECT_ID>.firebaseapp.com",
    databaseURL: "https://<DATABASE_NAME>.firebaseio.com",
    storageBucket: "<BUCKET>.appspot.com",
  };
  firebase.initializeApp(config);
</script>
```

That's all, you are good to go.

## How to thank me?

* Star this repo
Follow me on my social media handles
* Subscribe on [Youtube](http://youtube.com/c/braintemorg)
* Follow on [Twitter](http://twitter.com/braintem)
* Follow on [Instagram](http://instagram.com/daveozoalor)
* Like on [Facebook](http://fb.com/braintem)


## Contacts

* You can reach me on `daveozoalor@gmail.com`
* Just buzz me up on [facebook](http://facebook.com/daveozoalor)

## License

Fireblogger is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
