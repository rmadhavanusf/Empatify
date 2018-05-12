# Empatify
Music recommended by your Heart

### Setup:

1. Clone/Download this repository.
2. Open the project in Android Studio.
3. Make sure you have valid API keys for Empatica and Spotify.
    Empatica API Key: https://developer.empatica.com/
    Spotify API Key: https://developer.spotify.com/
4. Edit `MainActivity.java` and assign your API keys to `EMPATICA_API_KEY` and `CLIENT_ID` respectively.
5. Build and run the project!

### Pre-built Binary

Don't feel like doing the setup? We've got you covered! Download and install `Empatify.apk` on your Android device. You can use `adb` to install the APK.

    adb install Empatify.apk

### Dataset

The dataset contains 1476 songs and their corresponding audio features, and was compiled from the [Kaggle Audio Features data](https://www.kaggle.com/aniruddhaachar/audio-features/data). You can find it [here](https://github.com/rmadhavanusf/Empatify/blob/master/app/src/main/res/raw/dataset.csv). 
